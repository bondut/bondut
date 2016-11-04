
<!DOCTYPE html>
<link href="style.css" type="text/css" rel="stylesheet">

<body>
  <div class="header">
    <h1>
Ario's Webpage
</h1>body {
  margin: 0;
  padding: 0;
  margin: 0px;
}

h1 {
  text-transform: uppercase;
  text-align: center;
  color: FireBrick;
  font-family: Arial, courier, serif;
  letter-spacing: 0.3em;
  margin: 0;
  padding-bottom: 10px;
  font-size: 25px;
}

h2 {
  font-style: italic;
  text-transform: uppercase;
  letter-spacing: 0.01em;
  text-align: center;
  color: FireBrick;
  margin: 0;
}

p {
  font-size: 13px;
  font-family: serif;
  font-weight: bold;
  line-height: 1.5em;
}

.target2 {
  font-size: 11px;
  margin: 0;
}

.target1 {
  font-size: 11px;
}

h3 {
  color: FireBrick;
  word-spacing: 0.3em;
  text-align: center;
  font-size: 17px;
  font-family: serif;
  padding-bottom: 5px;
}

#form {
  color: FireBrick;
}

.comment {
  background-image: -webkit-linear-gradient(#E0E80A, #ADE80E);
}

.header {
  background: yellow;
  padding: 30px 40px;
  border: 5px dashed;
}

div.body {
  border: 2px solid;
  padding: 10px 10px 20px 40px;
  margin: 40px;
  background-color: white;
}

* {
  box-sizing: border-box;
}

div.comment {
  border-width: 1px 1px 1px 5px;
  border-style: hidden hidden hidden solid;
  border-color: black;
  border-radius: 20px 0px 0px 20px;
  padding: 40px;
  width: 350px;
  float: right;
  font-family: serif;
}

body {
  background: url("https://static.pexels.com/photos/24114/pexels-photo-24114.jpg") no-repeat center center;
  background-size: cover;
  margin: 0px;
  background-attachment: fixed;
}

.body img {
  border-radius: 50%;
  width: 100px;
  height: 100px;
  display: block;
  margin: 0px auto;
  border: 2px solid black;
}
td, th, table {
  border: 1px solid black;
}
#span {
  font: 20px courier;
  text-align: center;
  color: red;
  font-weight: bold;
}
    <h2 id="welcome">
Welcome everyone !
</h2>
  </div>
  <div class="body">
    <img src="https://static.pexels.com/photos/218413/pexels-photo-218413.jpeg" />
    <p>
      Hi, I am Ario and this is my first webpage. Let's be a fullstack developer with hactiv8
    </p>
    <p>This is my target list</p>
    <ol class="target1">
      <li>Being fullstack developer</li>
      <li>Create wonderful website</li>
    </ol>
    <p>
      Here is my contact
    </p>
    <ul class="target2">
      <li>Email : a.ekowardhono@gmail.com</li>
      <li>Phone : 085285606848</li>
    </ul>
    <p>
    My Daily Routine
    </p>
    <table>
    <tr>
      <th></th>
      <th>Morning</th>
      <th>Afternoon</th>
      <th>Evening</th>
      <th>Night</th>
    </tr>
    <tr>
      <td>Monday</td>
      <td id="span" colspan="4" rowspan="7"> Eat, Coding, & Sleep</td>
    </tr>
    <tr>
      <td>Tuesday</td>
    </tr>
    <tr>
      <td>Wednesday</td>
    </tr>
    <tr>
      <td>Thursday</td>
    </tr>
    <tr>
      <td>Friday</td>
    </tr>
    <tr>
      <td>Saturday</td>
    </tr>
    <tr>
      <td>Sunday</td>
    </tr>
    </table>
    
  </div>
  <div class="comment">
    <h3>
Leave your comment below
</h3>
    <form id="form">
      <p>
        <label for="first-name">First Name :</label>
        <input name="first-name" type="text">
      </p>
      <p>
        <label for="last-name">Last Name :</label>
        <input name="last-name" type="text">
      </p>

      <p>
        <label for="gender">Gender:</label>
      </p>
      <p>
        <input type="radio" name="gender" value="male">Male</p>
      <p>
        <input type="radio" name="gender" value="female">Female</p>
      <p>
        <input type="radio" name="gender" value="other">Other</p>

      <p>
        <label for="favourite cars">Favourite Cars :</label>
      </p>
      <p>
        <input type="text" name="cars" list="car list" />
        <datalist id="car list">
          <label for="suggestion">suggestion</label>
          <select id="suggestion" name="altcars">
            <option value="Volvo">Volvo</option>
            <option value="BMW">BMW</option>
            <option value="Peugeot">Peugeot</option>
            <option value="Honda">Honda</option>
          </select>
        </datalist>
      </p>

      <label for="language spoken">Language spoken:</label>
      <p>
        <input type="checkbox" name="language" value="Bahasa Indonesia">Bahasa Indonesia</p>
      <p>
        <input type="checkbox" name="language" value="English">English</p>
      <label for="bio">Bio :</label>
      <p>
        <textarea name="bio" type="textarea" rows="12" cols=" 25"></textarea>
        <p>
          <input type="submit" value="submit">
        </p>
    </form>
  </div>
</body>
