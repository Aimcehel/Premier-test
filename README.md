** start of undefined **

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <title>Registration Form</title>
    <link rel="stylesheet" href="styles.css" />
  </head>

  <body>
    <h1 id="title">freeCodeCamp Survey Form</h1>
    <p id="description" ><em>Thank you for taking the time to help us improve the platform </em></p>
    <form id="survey-form">
     
      <fieldset>
        <label class="question" id="name-label">Name <input id="name" type="text" Placeholder="Enter your name" required></label>
        <label class="question" id="email-label">Email <input id="email" type="email" Placeholder="Enter your Email" required></label>
        <label class="question" id="number-label">Age (optional) <input id="number" type="number" min="10" max="99" Placeholder="Age">
        <label class="question">Which option best describes your current role?</label>
        <select id="dropdown">
          <option value="1">Select current role</option>
          <option value="2">Student</option>
          <option value="3">Full Time Job</option>
          <option value="4">Full Time Learner</option>
          <option value="5">Prefer not to say</option>
          <option value="6">Other</option>
        </select>
        <label class="question">Would you recommend freeCodeCamp to a friend?</label>
        <label><input type="radio" name="recommand" class="inline" value="1"/>Definitely</label>
        <label><input type="radio" name="recommand" class="inline" value="2"/>Maybe</label>
        <label><input type="radio" name="recommand" class="inline" value="3"/>Not sure</label>
        <label class="question">What is your favorite feature of freeCodeCamp?</label>
          <select id="dropdown2">
          <option value="1">Select an option</option>
          <option value="2">Challenges</option>
          <option value="3">Projects</option>
          <option value="4">Community</option>
          <option value="5">Open Source</option>
          </select>
        <label class="question">What would you like to see improved? (Check all that apply)</label>
          <label><input type="checkbox" class="inline" value="1"/>Front-end Projects</label>
          <label><input type="checkbox" class="inline" value="2"/>Back-end Projects</label>
          <label><input type="checkbox" class="inline" value="3"/>Data Visualization</label>
          <label><input type="checkbox" class="inline" value="4"/>Challenges</label>
          <label><input type="checkbox" class="inline" value="5"/>Open Source Community</label>
          <label><input type="checkbox" class="inline" value="6"/>Gitter help rooms</label>
          <label><input type="checkbox" class="inline" value="7"/>Videos</label>
          <label><input type="checkbox" class="inline" value="8"/>City Meetups</label>
          <label><input type="checkbox" class="inline" value="9"/>Wiki</label>
          <label><input type="checkbox" class="inline" value="10"/>Forum</label>
          <label><input type="checkbox" class="inline" value="11"/>Additional Courses</label>
        <label class="question">Any comments or suggestions?</label>
          <textarea Placeholder="Enter your comment here..."></textarea>
        <input type="submit" id="submit" value="Submit">

      </fieldset>
    </form>
  </body>
</html>

** end of undefined **

** start of undefined **

body{
  width: 100%;
  height: 100vh;
  background-color: #4a4063;
  font-family: Verdana;
  color: white;
  font-color:#434343;
}

h1{
  margin-top: 50px;
}
h1,p{
  text-align: center;
}

form {
  background-color:#2c2148;
  width: 50%;
  height: auto;
  margin: auto;
  margin-top: 50px;
}

fieldset{
  border: none;
}

label {
  display: block;
  margin: 0.5rem 0;
}

input{
  width: 100%;
  display: block;
  margin: 0.5rem 0;
  Placeholder-color: #999999;
}
.question{
  padding-top: 1em;
}

.inline {
  width: unset;
  margin: 0 0.5em 0 0;
  vertical-align: middle;
  display: unset;
}

textarea, select{
  width: 100%
}

** end of undefined **
