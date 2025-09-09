<!doctype html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>forms</title>
</head>
<body>
  <h1>User Registration Form</h1>
  <form >
    <fieldset >
      <legend>
  <h4>Personal information</h4>
  </legend>
  <label for="first-name">First name:</label>
<input type="text" name="first-name" id="first-name" />
  <br>
<br>

<label for="Last name">Last name:</label>
<input type="text" name="last name" id="last name"  /><br>
<br>
<label for="Date of birth">Date of birth:</label>
  <input type="date" name="date of birth" id="dob" value="mm/dd/yyyy" /><br>
  <br>
  <label for="Age">Age:</label>
  <input type="number" name="age" id="age" /><br>
  <br>
  
<label for="Gender">Gender:</label><br>
<input type="radio" name="gender">
  <label for="Male">Male</label><br>
  <input type="radio" name="gender">
  <label for="Female">Female</label>
</select>
<br>
<br>
<label for="Profile photo">Profile photo:</label>
<input type="file" name="profile" id="profile photo" /><br>
</fieldset>
<fieldset>
  <legend>
    <h4>Contact and address information</h4>
    </legend>
    <label for="Email address">Email address:</label>
    <input type="email" name="email" id="email" /><br>
    <br>
    <label for="phone number">phone number:</label>
    <input type="tel" name="tel" id="phone number" /><br>
    <br>
    <label for="Personal website">Personal website:</label>
    <input type="url" name="website" id="personal website" placeholder="https://example.com" /><br>
    <br>
    <label for="Street address">Street address:</label>
    <input type="text" name="address" id="street address" /><br>
    <br>
    <label for="City">City:</label>
    <input type="text" name="city" id="city" /><br>
    <br>
    <label for="Country">country:</label><select name="country" id="country"><option value="selectcountry">selectcountry</option>
    <option value="Kenya">kenya</option>
    <option value="Tanzania">Tanzania</option>
    <option value="Rwanda">rwanda</option>
    <option value="Uganda">Uganda</option></select><br>
    <br>
    <label for="Zip/postal code">Zip/postal code:</label>
    <input type="text" name="zip" id="zip/postal code" value="" /><br>
    <br>
    <label for="Preferred contact time">Preferred contact time:</label><input type="time" name="time" id="time"/><br>
    </fieldset>
    <fieldset>
      <legend>
        <h4>Preferences & interests</h4>
      </legend>
      <label for="Favorite color">Favorite color:</label>
    <input type="color" name="fav color" id="favorite color" value="blue" /><br>
    <br>
    <label for="Experience level(1-10)">Experience level(1-10):</label>
    <input type="range" name="text" id="experience level" value="level"
    />
    <br>
    <br>
    <label for="Birth">Birth month</label>
    <input type="date" name="birth month" id="birth month" value="" /><br>
    <br>
    <label for="Available week">Available week:</label>
    <input type="week" name="week" id="available week"/><br>
    <br>
    <label for="Search keywords">Search keywords:</label><input type="text" name="keywords" id="search keywords" placeholder="enter keywords..." /><br>
    </fieldset>
    <fieldset>
      <legend><h4>
        Interests(select all that apply):</h4></legend>
        <input type="checkbox" />
        <label for="Technology">Technology</label><br>
        <input type="checkbox"/>
        <label for="Sports">Sports</label>
        <br>
          <input type="checkbox"/>
          <label for="Music">Music</label><br>
          <input type="checkbox"/>
          <label for="Travel">Travel</label><br>
          <input type="checkbox"/>
          <label for="Reading">Reading</label><br>
          <input type="checkbox"/>
          <label for="Cooking">Cooking</label><br>
          <br>
          <label for="Education level">Education level:</label>
          <select name="select education level" id="select education level">
          <option value="select education level">select education level</option>
          <option value="primary">primary</option>
          <option value="secondary">secondary</option>
          <option value="diploma">diploma</option>
          <option value="degree">degree</option>
          </select><br>
          <br>
          <label for="Create password">Create password:</label>
          <input type="password" name="confirm password" id="confirm password" required/><br>
          <br>
          <label for="Confirm password">Confirm password:</label>
          <input type="password" name="password" id="password=" />
          </fieldset>
          <fieldset>
          <legend>
             <h4> Feedback & additional information</h4></legend>
              <label for="Tell us about yourself">Tell us about yourself:</label>
              <input type="text" name="info" id="info" placeholder="write a brief description about yourself..."
              style="width: 300px;height: 90px;"
              <br>
              <br>
              <label for="Suggestions for improvement">Suggestions for improvement:</label>
          <input type="text" placeholder="Any suggestions or feedback..."
          style="width: 300px; height: 90px;"
          /><br>
          <br>
          <label for="Registration date &time">Registration date & time:</label>
          <input type="datetime-local" /><br>
          <br>
          <label for="How did you hear about us">How did you hear about us?</label>
          <select name="select source" id="select source">
              <option value="select source">select source</option>
          <option value="Google">Google</option>
          <option value="friend">friend</option>
          <option value="Browser">Browser</option>
          </select><br>
          <br>
          <label for="Upload resume(optional)">Upload resume(optional):</label>
          <input type="file" id="resume"/><br>
          <br>
          <input type="checkbox" />
          <label for="Subscribe to our newsletter">Subscribe to our newsletter</label><br>
          <br>
          <input type="checkbox"/>
          <label for="I agree to the terms and conditions">I agree to the terms and conditions</label><br>
          <br>
          <input type="checkbox" />
          <label for="I agree to the private policy">I agree to the private policy</label<br>
          <br>
          </fieldset>
          <br>
        <input type="submit"value="register" /><input type="reset"value="clear form" />
  </form>
</body>
</html>
