<DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DStedent Registration Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f7f7f8;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }

        .form-container {
            width: 400px;
            max-width: 90%;
            background-color: white;
            border-radius: 15px;
            box-shadow: 0px 0px 15px rgba(0,0,0,0.2);
            padding: 20px;
        }

        h2 {
            text-align: center;
            margin-bottom: 20px;
        }

        label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
        }

        input[type="text"], input[type="email"], input[type="password"] {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }

        button {
            width: 100%;
            padding: 10px;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
            font-size: 16px;
        }

        button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <div class="form-container">
        <h2>Student Registration</h2>
        <form action="/submit_registration" method="POST">
            <label for="name">Full Name</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email Address</label>
            <input type="email" id="email" name="email" required>

            <label for="password">Password</label>
            <input type="password" id="password" name="password" required>
            
            <label for="student_number">Student Number</label>
            <input type="text" id="student_number" name="student_number" required>

            <label for="phone_number">Phone Number</label>
            <input type="text" id="phone_number" name="phone_number" required>c

            <button type="submit">Register</button>
        </form>
    </div>
</body>
</html>
