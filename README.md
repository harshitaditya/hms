<html>
<!--#04aa6d-->
<style>
#reg{
margin: 0 auto;
background-color: lightgray;
width: 350px;
height: 600px;
border-radius: 10px;
font-size:20px;
padding-top: 5px;
padding-left:10px;
}

#submit, #reset {
background-color: #4CAF50;
color: black;
border: none;
cursor: pointer;
margin: 4px 2px;
font-size:20px;
border-radius: 5px;
}

.top { background-color:#04b861;
;overflow: hidden; }

.top a { float:left;
color: black;
text-align: center;
padding: 14px 16px;
text-decoration: none;
font-size:17px; }

.top a:hover {background-color: #302d2d;
color: white; }
</style>


<body style="background-color: rgb(10,100,40); background-image: url(https://img.freepik.com/free-vector/clean-medical-background_53876-97927.jpg?w=2000); background-repeat: no-repeat; background-size: 100%">
<div class="top">
		  <nav>
		  <a href="home.html"><b>Home</b></a>
		  <a href=""><b>About</b></a>
		  <a href=""><b>Contact</b></a>
		  <a href=""><b>Login</b></a>
		  </nav>
		  </div>
		  <hr>

<div id="reg">
<h1>Doctor's Registration</h1>
<form action="patreg.php" method="post">
Full Name: <input type="text" name="name" placeholder="Enter full Name" required>
<br><br>



<label for="gender">Gender:</label>
  <select name="gender" id="gender" required>
    <option value="Male">Male</option>
    <option value="Female">Female</option>
    <option value="Other">Other</option>
  </select>
  <br><br>
  
Age: <input type="age" id="age" name="age" required>
<br><br>

<label for="blood">Blood Group:</label>
  <select name="blood" id="blood" required>
    <option value="A+">A+</option>
    <option value="A-">A-</option>
    <option value="B+">B+</option>
	<option value="B-">B-</option>
	<option value="AB+">AB+</option>
	<option value="AB-">AB-</option>
	<option value="O+">O+</option>
	<option value="O-">O-</option>
  </select>
  <br>
  <br>
Department: <input type="text" name="address" id="address" style="height:30px;" required><br><br>
Mobile Number: <input type="number" id="mnum" name="mnum" maxlength="10" required>
<br><br>  
 Email: <input type="email" id="email" name="email" required>
<br><br>
Password: <input type="password" id="password" name="password" required>
<br><br>
<input type="submit" id="submit" value="Submit">
<input type="reset" id="reset">
</form>
</div>
</body>

</html>
