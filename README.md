# web_dev_week2
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> </title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            background-color: #e3f5f1;
            opacity: 100%;
        }
        h2 {
            color: #333;
        }
        form {
            background: rgb(188, 197, 199);
            padding: 20px;
            border-radius: 5px;
            width: 400px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
        input, select, button {
            display: block;
            width: 100%;
            margin-top: 10px;
            padding: 8px;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
            background: rgb(236, 247, 218);
        }
        th, td {
            border: 1px solid black;
            padding: 10px;
            text-align: left;
        }
    </style>
</head>
<body>

    <h1>Welcome to My Web develoment assignment</h1>

    <h2>My Favorite Hobbies</h2>
    <ol type="I">
        <li>Reading Books</li>
        <li>Coding</li>
        <li>Traveling</li>
        <li>football</li>
        <li>Playing Chess</li>
    </ol>

    <h2>Beautiful Nature</h2>
    <div class="media-container">
        <img src="https://images.pexels.com/photos/674010/pexels-photo-674010.jpeg" alt="Beautiful Nature" width="300">
        <video width="300" controls>
            <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
        <audio controls>
            <source src="https://www.w3schools.com/html/horse.ogg" type="audio/ogg">
            Your browser does not support the audio tag.
        </audio>
    </div>
    <h2>Contact List</h2>
    <table>
        <tr>
            <th>Name</th>
            <th>Address</th>
            <th>Mobile</th>
            <th>Email</th>
        </tr>
        <tr>
            <td>John Obi</td>
            <td>No.4 nnadi street</td>
            <td>080 567 890</td>
            <td>johnobi@gmail.com</td>
        </tr>
        <tr>
            <td>Abdul Musa</td>
            <td>No.12c awolowo close</td>
            <td>090 678 901</td>
            <td>abdulmusa@gmail.com</td>
        </tr>
        <tr>
            <td>Emma Johnson</td>
            <td>No.7a aja street</td>
            <td>070 789 012</td>
            <td>emmajohnson@gmail.com</td>
        </tr>
        <tr>
            <td>Emily Brown</td>
            <td>101 Pine St, FL</td>
            <td>+12  890 123</td>
            <td>emilybrown@gmail.com</td>
        </tr>
        <tr>
            <td>Isah Babagida</td>
            <td>Amadu bello street</td>
            <td>080 901 234</td>
            <td>isahbaba@gmail.com</td>
        </tr>
    </table>

    <h2>Registration Form</h2>
    <form>
        <label for="name">Full Name:</label>
        <input type="text" id="name" name="name" placeholder="Enter your full name" required>

        <label for="email">Email Address:</label>
        <input type="email" id="email" name="email" placeholder="Enter your email" required>

        <label for="password">Password:</label>
        <input type="password" id="password" name="password" placeholder="Create a password" minlength="6" required>

        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" required>

        <label for="country">Select Country:</label>
        <select id="country" name="country" required>
            <option value="" disabled selected>Choose your country</option>
            <option value="nigeria">Nigeria</option>
            <option value="usa">United States</option>
            <option value="uk">United Kingdom</option>
            <option value="canada">Canada</option>
        </select>

        <label>Gender:</label>
        <input type="radio" id="male" name="gender" value="male" required>
        <label for="male">Male</label>
        
        <input type="radio" id="female" name="gender" value="female" required>
        <label for="female">Female</label>
        <br>
        <p>
        <label>Interests:</label>
        <input type="checkbox" id="coding" name="interests" value="coding">
        <label for="coding">Coding</label>

        <input type="checkbox" id="music" name="interests" value="music">
        <label for="music">Music</label>

        <input type="checkbox" id="sports" name="interests" value="sports">
        <label for="sports">Sports</label>
         </p>
        <button type="submit">Register</button>
    </form>

</body>
</html>
