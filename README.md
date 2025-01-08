# reservation
<!DOCTYPE html>
<html lang="en">
<head>
<title>Pacific Trails Resort :: Reservations</title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link rel="icon" href="favicon.ico" type="image/x-icon"> 
<link href="pacific.css" rel="stylesheet">
</head>
<body>
  <header>
    <h1><a href="index.html">Pacific Trails Resort</a></h1>
  </header>
  <nav>
    <ul>
      <li><a href="index.html">Home</a></li>
      <li><a href="yurts.html">Yurts</a></li>
      <li><a href="activities.html">Activities</a></li>
      <li><a href="reservations.html">Reservations</a></li>
	</ul>
  </nav>
  <div id="wrapper">
  <div id="reshero">
  </div>
  <main>
    <h2>Reservations at Pacific Trails</h2>
    <h3>Contact Us</h3>
	<p>Required fields are marked with an asterisk *</p>
	 <form method="post" action="https://webdevbasics.net/scripts/pacific.php">
       <label for="myFName">*First Name: </label><input type="text" id="myFName" name="myFName" required>
       <label for="myLName">*Last Name: </label><input type="text" id="myLName" name="myLName" required>
       <label for="myEmail">*E-mail: </label><input type="email" id="myEmail" name="myEmail" required>
       <label for="myPhone">Phone: </label><input type="tel" id="myPhone" name="myPhone">
       <label for="myDate">Arrival Date: </label><input type="date" id="myDate" name="myDate">
       <label for="myNights">Nights: </label><input type="number" id="myNights" name="myNights" min="1" max="14">
       <label for="myComments">*Comments: </label><textarea id="myComments" name="myComments" rows="2" cols="20" required></textarea>
       <input type="submit" id="mySubmit" value="Submit">
	  </form>
  </main>
  <footer>
Copyright &copy; 2020 Pacific Trails Resort<br>
<a href="mailto:yourfirstname@yourlastname.com">yourfirstname@yourlastname.com</a>
  </footer>
</div>
</body>
</html>
