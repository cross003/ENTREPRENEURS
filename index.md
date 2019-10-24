<!DOCTYPE html>
<html>
<head>
<style>
* {
  box-sizing: border-box;
}

body {
  font-family: Arial;
  padding: 30px;
  background-image: url("eun.jpg");
  background-repeat: no-repeat, repeat;
  background-size: cover;
}

hr.line {
  border-top: 1px solid white;
}

/* Header */
.header {
  top: 50 px;
  padding: 100px;
  width: 500px;
  text-align: justify;
  text-align-last: center;
  background: gold;
  margin: 100px auto 150px auto;
  align-content: stretch;
}

p.big {
  line-height: 5;
  color: white;
}

.header h1 {
  font-size: 50px;
}

/* Style the top navigation bar */
.topnav {
  top: 0px;
  left: 0px;
  padding: 20px 20px; 
  position: absolute; 
  overflow: hidden;
  background-color: white;
  width:100%;
  height: 60px;
  opacity: 0.75;
}

.sticky
{
	padding: 10px 20px;
	position: fixed;
	top : 0;
	height : 200px;
	width: 100%;
}

/* Style the topnav links */
.topnav a {
  float: left;
  margin: 0px auto;
  display: inline;
  color: black;
  text-align: center;
  padding: 14px 16px 0px ;
  text-decoration: none; 
  outline-color: #f2f2f2;
}

/* Change color on hover */
.topnav a:hover {
  color: gold;
}

/* Create two unequal columns that floats next to each other */
/* Left column */
.leftcolumn {   
  float: center;
  width: 75%;
}

/* Right column */
.rightcolumn {
  float: left;
  width: 25%;
  background-color: #aaa;
  padding-left: 20px;
}

/* Add a card effect for articles */
.card {
  left: -40px;
  position: relative;
  width: 115%;
  background-color: white;
  outline-color: white;
  padding: 20px;
}

/* Add a card effect for articles */
.card2 {
  color: white;
  text-align: justify;
  text-align-last: center;
  left: -40px;
  position: relative;
  width: 115%;
  background-color: gold;
  outline-color: gold;
  padding: 20px;
}

/* Add a card effect for articles */
.card3 {
  text-align: justify;
  text-align-last: center;
  left: -40px;
  position: relative;
  width: 115%;
  background-color: gold;
  outline-color: gold;
  padding: 20px;
}


/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Footer */
.footer {
  position:absolute; 
  width:100%;  
  left: 0px;
  text-align: center;
  background: #ddd;
  margin: 0;
}
div.absolute {
  position: absolute;
  top: 80px;
  right: 0;
  width: 200px;
  height: 100px;
}

h1.b {
  font-stretch: expanded;
}

/* Responsive layout - when the screen is less than 800px wide, make the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 800px) {
  .leftcolumn, .rightcolumn {   
    width: 100%;
    padding: 0;
  }
}

/* Responsive layout - when the screen is less than 400px wide, make the navigation links stack on top of each other instead of next to each other */
@media screen and (max-width: 400px) {
  .topnav a {

    float: none;
    width: 80%;
  }
}
</style>
</head>
<body>

<div class="topnav">
  <div class ="sticky">
	<a href="https://cross003.github.io/ENTREPRENEURS/">Home</a>
	<a href="https://cross003.github.io/ENTREPRENEURS/Board.htm">Board</a>
	<a href="https://cross003.github.io/ENTREPRENEURS/Resources.htm">Resources</a>
	<a href="https://cross003.github.io/ENTREPRENEURS/Calender.htm">Calender</a>
	<a href="https://cross003.github.io/ENTREPRENEURS/Contact.htm" style="float:right">Contact Us</a>
  </div>
</div>

<h1></h1>


<div class="header">
  <h1 class ="b">UMBC</h1>
  <h1 class ="b">Entrepreneurs </h1>  
  <hr class="line">
  <p class = "big">HUSTLE | GRIND | INSPIRE </p>
</div>




<div class="row">
    <div class="card3">
	  <h2>Join the Email List for Events, Resources and Exclusive Access</h2>
    </div>
	<div class="card">
      <h5>WHEN /</h5>
	  <h2>WEDNESDAYS 12 PM - 1 PM DURING FREE HOUR</h2>
      <h5>WHERE /</h5>
	  <h2>PERFORMING ARTS AND HUMANITIES 220 </h2>
      <h5>ABOUT THE EVENT /</h5>
      <h2>UMBC Entrepreneurs are DISCIPLINED, AMBITIOUS, and INNOVATIVE. We welcome everyone, regardless of experience. Have ideas YOU want to make a reality? See what the HYPE is about.</h2>
    </div>
    <div class="card2">
      <h5>SCHEDULE /</h5>
	  <h2>FROM ENGINEER TO ENTREPRENEUR</h2>
      <h5>Monday, Febrauary 25, 2019 12:00 PM - 1:00 PM UC Ballroom</h5>

      <h2>FINDING THE RIGHT CLIENT</h2>
      <h5>Wednesday, March 6, 2019 12:00 PM - 1:00 PM UC 115</h5>

	  <h2>FROM SCIENTIST TO SERIAL ENTREPRENEUR</h2>
	  <h5>Wednesday, March 13, 2019. 12:00 PM - 1:00 PM UC 115</h5>

	  <h2>HOW TO GIVE A GOOD PITCH</h2>
	  <h5>Wednesday, March 27, 2019. 12:00 PM - 1:00 PM UC 115</h5>
    </div>
  
  
</div>

<div class="footer">	
		<h5>© 2019 by UMBC Entrepreneurs. Proudly created by UMBC eShip. For Questions /  Contact us at umbcentrepreneurs@gmail.com.</h5>
</div>

</body>
</html>
