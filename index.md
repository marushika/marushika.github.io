<!doctype html>
<html>
<head>
<title>module2 assignment</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>


body {
  background-color: lightblue;
}
div{
position:relative;
border:2px solid black;
padding:10px;
margin:1%;
background-color:gray;
width:29%;
 float:left;
}
header{
position: absolute;
top:0px;
right: 0px;
text-align:"center";
background-color:tomato;
width:25%;
border:2px solid black;
text-align:center;
}
/* Extra small devices (phones, 767px and down) */
@media only screen and (max-width: 767px) {
div{
float:center;
width:90%;
text-align:center;
 }
}

/* Small devices (portrait tablets and large phones, 600px and up) */
@media only screen and (min-width: 768px) and (max-width:991px) {
div{
width:40%;
float:left;
}
.sushi{
  width:96%;
}
}

/* Large devices (laptops/desktops, 1024px and up) */
@media only screen and (min-width: 992px) {
div{
width:28%;
float:left;
}
} 

</style>
</head>
<body background-color:"MediumSeaGreen";>
<h2 style="text-align:center;">Our Menu</h2>
<div>
   <header>chicken</header>
<p>"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."</p>
</div>
<div>
<header>beef</header>
<p>"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."</p>
</div>
<div class="sushi">
<header>sushi</header>
<p>"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."</p>
</div>
</body>
</html>
