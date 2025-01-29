<form action="#" method="post">
        <img src="placeholder_logo.png" alt="Company Logo" class="company-logo">
        <h2>Company Name</h2>
        <h3>Position: Software Engineer</h3>

        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required><br>

        <label for="contact">Contact No:</label>
        <input type="tel" id="contact" name="contact" required><br>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required><br>

        <label>Gender:</label>
        <label for="male">
            <input type="radio" id="male" name="gender" value="male" required> Male
        </label>
        <label for="female">
            <input type="radio" id="female" name="gender" value="female"> Female
        </label>
        <label for="other">
            <input type="radio" id="other" name="gender" value="other"> Other
        </label><br><br>

        <label for="skills">Skills (Check all that apply):</label><br>
        <label for="java">
            <input type="checkbox" id="java" name="skills[]" value="java"> Java
        </label>
        <label for="python">
            <input type="checkbox" id="python" name="skills[]" value="python"> Python
        </label>
        <label for="javascript">
            <input type="checkbox" id="javascript" name="skills[]" value="javascript"> JavaScript
        </label><br><br>

        <label for="resume">Resume:</label>
        <input type="file" id="resume" name="resume" accept=".pdf, .doc, .docx"><br><br>

        <button type="submit">Submit</button>
    </form>
