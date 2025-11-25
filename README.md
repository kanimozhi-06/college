# college<!DOCTYPE html>
<html>
<head>
    <title>Student Data Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 40px;
            background-color: #f5f5f5;
        }
        .container {
            width: 400px;
            padding: 20px;
            background: white;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        input, select {
            width: 100%;
            padding: 10px;
            margin: 8px 0;
            border-radius: 5px;
            border: 1px solid #ccc;
        }
        button {
            width: 100%;
            padding: 10px;
            background: #007bff;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background: #0056b3;
        }
    </style>
</head>

<body>
    <div class="container">
        <h2>Student Registration Form</h2>
        <form action="save_student.php" method="POST">
            <label>Full Name:</label>
            <input type="text" name="fullname" required>

            <label>Roll Number:</label>
            <input type="text" name="roll" required>

            <label>Email:</label>
            <input type="email" name="email" required>

            <label>Department:</label>
            <select name="department" required>
                <option value="">Select Department</option>
                <option value="Computer Science">Computer Science</option>
                <option value="Electronics">Electronics</option>
                <option value="Mechanical">Mechanical</option>
                <option value="Civil">Civil</option>
            </select>

            <label>Mobile Number:</label>
            <input type="text" name="mobile" required>

            <button type="submit">Save Student</button>
        </form>
    </div>
</body>
</html>


writing the code to save the students data into the details
