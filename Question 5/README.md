# Create employee registration webpage using HTML form objects.
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Employee Registration Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            background-color: #f4f4f4;
        }
        .container {
            max-width: 600px;
            margin: auto;
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1 {
            text-align: center;
            color: #333;
        }
        label {
            display: block;
            margin-bottom: 8px;
            font-weight: bold;
        }
        input[type="text"],
        input[type="email"],
        input[type="number"],
        input[type="date"],
        select,
        textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        input[type="radio"],
        input[type="checkbox"] {
            margin-right: 10px;
        }
        .gender {
            margin-bottom: 15px;
        }
        button {
            width: 100%;
            padding: 10px;
            background-color: #28a745;
            color: white;
            border: none;
            border-radius: 4px;
            font-size: 16px;
            cursor: pointer;
        }
        button:hover {
            background-color: #218838;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Employee Registration Form</h1>
        <form action="#" method="post">
            <label for="fname">First Name:</label>
            <input type="text" id="fname" name="firstname" placeholder="Enter first name" required>

            <label for="lname">Last Name:</label>
            <input type="text" id="lname" name="lastname" placeholder="Enter last name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Enter email address" required>

            <label for="phone">Phone Number:</label>
            <input type="number" id="phone" name="phone" placeholder="Enter phone number" required>

            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob" required>

            <label for="position">Position:</label>
            <input type="text" id="position" name="position" placeholder="Enter position applied for" required>

            <label>Gender:</label>
            <div class="gender">
                <input type="radio" id="male" name="gender" value="male" required>
                <label for="male">Male</label>

                <input type="radio" id="female" name="gender" value="female">
                <label for="female">Female</label>

                <input type="radio" id="other" name="gender" value="other">
                <label for="other">Other</label>
            </div>

            <label for="department">Department:</label>
            <select id="department" name="department" required>
                <option value="hr">HR</option>
                <option value="engineering">Engineering</option>
                <option value="sales">Sales</option>
                <option value="marketing">Marketing</option>
                <option value="finance">Finance</option>
            </select>

            <label for="address">Address:</label>
            <textarea id="address" name="address" rows="4" placeholder="Enter your address" required></textarea>

            <label for="resume">Upload Resume:</label>
            <input type="file" id="resume" name="resume" accept=".pdf,.doc,.docx" required>

            <button type="submit">Register</button>
        </form>
    </div>

</body>
</html>

```

![Screenshot (38)](https://github.com/user-attachments/assets/b8e9830b-3213-4dae-a8a9-d6313c42d4db)
