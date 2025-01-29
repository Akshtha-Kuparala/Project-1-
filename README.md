<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rock your Life - Data Analyst Recruitment</title>
</head>
<body>
    <div class="container" style="margin: 20px; padding: 20px;">
        <h1 id="company-name" style="margin-bottom: 10px;">Rock your Life</h1>
        <h2 id="form-title" style="margin-bottom: 20px;">Data Analyst Recruitment Form</h2>
        <form id="recruitment-form">
            <div class="form-group" style="margin-bottom: 15px;">
                <label for="name">Full Name:</label><br>
                <input type="text" id="name" name="name" required>
            </div>
            
            <div class="form-group" style="margin-bottom: 15px;">
                <label for="age">Age:</label><br>
                <input type="number" id="age" name="age" required>
            </div>
            
            <div class="form-group" style="margin-bottom: 15px;">
                <label for="email">Email:</label><br>
                <input type="email" id="email" name="email" required>
            </div>
            
            <div class="form-group" style="margin-bottom: 15px;">
                <label for="contact">Contact Number:</label><br>
                <input type="tel" id="contact" name="contact" required>
            </div>
            
            <div class="form-group" style="margin-bottom: 15px;">
                <label for="address">Address:</label><br>
                <input type="text" id="address" name="address">
            </div>
            
            <div class="form-group" style="margin-bottom: 15px;">
                <label>Gender:</label><br>
                <input type="radio" id="male" name="gender" value="Male" required> <label for="male">Male</label>
                <input type="radio" id="female" name="gender" value="Female" required> <label for="female">Female</label>
                <input type="radio" id="other" name="gender" value="Other" required> <label for="other">Other</label>
            </div>
            
            <div class="form-group" style="margin-bottom: 15px;">
                <label for="resume">Upload Resume:</label><br>
                <input type="file" id="resume" name="resume" required>
            </div>
            
            <div class="form-group" style="margin-bottom: 15px;">
                <input type="checkbox" id="terms" name="terms" required>
                <label for="terms">I agree to the terms and conditions</label>
            </div>
            
            <div class="form-group" style="margin-bottom: 15px;">
                <button type="submit">Submit Application</button>
            </div>
        </form>
    </div>
</body>
</html>
