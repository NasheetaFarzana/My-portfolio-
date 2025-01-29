<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Company Recruitment Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            max-width: 600px;
            margin: 0 auto;
            padding: 20px;
        }
        .logo {
            max-width: 200px;
            height: auto;
        }
        form {
            background-color: #f4f4f4;
            padding: 20px;
            border-radius: 5px;
        }
        label {
            display: block;
            margin-top: 10px;
        }
        input[type="text"], input[type="email"], input[type="tel"], select {
            width: 100%;
            padding: 5px;
            margin-top: 5px;
        }
        input[type="submit"] {
            background-color: #4CAF50;
            color: white;
            padding: 10px 15px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            margin-top: 10px;
        }
    </style>
</head>
<body>
    <h1>TechCorp Recruitment</h1>
    <img src="https://example.com/techcorp-logo.png" alt="TechCorp Logo" class="logo">
    
    <form>
        <h2>Job Application Form</h2>
        
        <label for="position">Position applying for:</label>
        <select id="position" name="position" required>
            <option value="">Select a position</option>
            <option value="software_engineer">Software Engineer</option>
            <option value="data_analyst">Data Analyst</option>
            <option value="product_manager">Product Manager</option>
        </select>
        
        <label for="name">Full Name:</label>
        <input type="text" id="name" name="name" required>
        
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
        
        <label for="phone">Phone Number:</label>
        <input type="tel" id="phone" name="phone" required>
        
        <label>Gender:</label>
        <input type="radio" id="male" name="gender" value="male" required>
        <label for="male">Male</label>
        <input type="radio" id="female" name="gender" value="female" required>
        <label for="female">Female</label>
        <input type="radio" id="other" name="gender" value="other" required>
        <label for="other">Other</label>
        
        <label for="resume">Upload Resume:</label>
        <input type="file" id="resume" name="resume" accept=".pdf,.doc,.docx" required>
        
        <label for="agree">
            <input type="checkbox" id="agree" name="agree" required>
            I agree to the terms and conditions
        </label>
        
        <input type="submit" value="Submit Application">
    </form>
</body>
</html>
