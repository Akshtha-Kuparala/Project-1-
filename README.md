<!DOCTYPE html>
<html>
<head>
<title>Potato Company - Application Form</title>
</head>
<body>

<table>
  <tr>
    <td colspan="2" align="center">
      <h1>Potato Company</h1>
      <h2>Application Form for Data Scientist Role</h2>
    </td>
  </tr>
  <tr>
    <td valign="top">
      <h3>Personal Details</h3>
      <table>
        <tr>
          <td>Name:</td>
          <td><input type="text" name="name"></td>
        </tr>
        <tr><td colspan="2"><br></td></tr>
        <tr>
          <td>Address:</td>
          <td><input type="text" name="address"></td>
        </tr>
        <tr><td colspan="2"><br></td></tr>
        <tr>
          <td>Phone:</td>
          <td><input type="text" name="phone"></td>
        </tr>
        <tr><td colspan="2"><br></td></tr>
        <tr>
          <td>Email:</td>
          <td><input type="email" name="email"></td>
        </tr>
        <tr><td colspan="2"><br></td></tr>
        <tr>
          <td>Age:</td>
          <td><input type="number" name="age"></td>
        </tr>
        <tr><td colspan="2"><br></td></tr>
        <tr>
          <td>Gender:</td>
          <td>
            <input type="radio" name="gender" value="male"> Male &nbsp;&nbsp;&nbsp; <input type="radio" name="gender" value="female"> Female
          </td>
        </tr>
        <tr><td colspan="2"><br></td></tr>
        <tr>
          <td>Attach CV:</td>
          <td><input type="file" name="cv"></td>
        </tr>
      </table>
    </td>
    <td valign="top">
      <h3>Checks</h3>
      <form>
        <p>
          <input type="checkbox" name="terms"> I Agree to Terms and Conditions of the Company<br>
          <input type="checkbox" name="data"> You will work with data privacy blah blah... <br>
          <input type="checkbox" name="accuracy"> I confirm that the information provided is accurate... <br>
        </p>
        <h3>Final Check</h3>
        <p>
          <input type="checkbox" name="knowledge"> All the data provided is true to my knowledge.
        </p>
        <input type="submit" value="Submit">
        <input type="reset" value="Reset">
      </form>
    </td>
  </tr>
</table>

</body>
</html>
