# Sris_wiehack2.0
This is website i have created for the animals who are suffering from diseases and are not getting food. This website will help you to give treatment to your animals at home with a option of lice chat
<!DOCTYPE html>
<html lang="en">
<head>
<title> ANIMAL CARE </title>
<link rel= "stylesheet"  href="style.css">
</head>
<body>
<header>
<div class="main" >
  <div class ="logo">
    <img src= "logo.jpg">
  </div>
<ul> 
<li> <a href=" # "> HOME </a></li>
<li> <a href=" # "> ABOUT </a></li>
<li> <a href=" # "> DISEASES </a></li>
<li> <a href=" # "> FIND A DOCTOR </a></li>
<li> <a href=" # "> EQUIPMENTS </a></li>
<li> <a href=" # "> FOOD FOR ANIMALS </a></li>
<li> <a href=" # "> TO DONATE </a></li>
<li> <a href=" # "> LIVE CHAT </a></li>
<li> <a href=" # "> CONTACT </a></li>
</ul>
</div> 
<div class= "title">
  <h1>  ANIMAL CARE </h1>
</div>
<div class ="button">
  <a href="#" class=" btn"> LEARN MORE </a>
  <a href="#" class="btn">  QUERIES </a>

</div>
</header>
</body>
</html>
 

STYLING CODEE
*{
	margin: 0;
	padding: 0;
	font-family: century gothic;

}
 body {
 	 background-image:  url("imge1.jpg");
 	 background-size: cover;
 	 background-repeat: no-repeat;
 	 height: 100vh;
 	 background-position: center;

 }
 ul {
 	float: right;
 	list-style-type: none;
    margin-top: 10px;
 }
 ul li {
 	 display: inline-block;  
 }
 ul li a{
 	text-decoration: none;
 	color: #000;
 	padding: 5px, 20px;
 	border: 2px solid #000;
 	transition: 0.6s ease;
 }
ul li a:hover {
	color: red;
}
.logo img {
	float: left;
	width: 150px;
	height: auto;
}
.main {
	max-width: 1200px;
	margin: auto;
}
.title{
	position: absolute;
	top: 50%;
	left:50%;
	transform:translate(-50%,-50%);
}

.title h1 {
 color: #000;
 font-size: 70px; 
}
 .button {
 	position: absolute;
	top: 60%;
	left:50%;
	transform:translate(-50%,-50%);
 }
 .btn {
 	border: 1px solid blue;
 	padding: 10px 30px;
 	color: red;
 	text-decoration: none;
 }
 .btn:hover {
 	color:#000;
 }
