<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<link rel="stylesheet" type="text/css" href="style.css">
	<!-- <link rel="stylesheet" type="text/css" href="2style.css"> -->
	<title>Web 3.0 Project</title>
</head>


<style>
a{

	color: #008;
	text-decoration: none;
}

#menu ul li a:hover{
	

	color: #455acc;
	font-size: 20px;
}

#poll 

#poll p:hover{

	color: #008;
}



.container{

		min-height: 1000px;
		background: #f1f1f1;
		width: 1200px;
		height: auto;
		margin: 0px auto;
	}

	.header{

		width: 100%;
		background: #fff;
		position: relative;
		height: 150px;
	}

	.section1{

		width: 100%;
		position: relative;
		height: 450px;
		background: #fff;
	}

	.section2{

		width: 100%;
		position: relative;
		background: #fff;
		height: 400px;
	}

	#logo{

		position: absolute;
		width: 130px;
		height: 110px;
		background: #fff;
		left: 45px;
		top: 20px;
	}

	#logo img{

		width: 100%;
		height: 100%;
		border-radius: 50%
	}

	#menu{

		position: relative;
		/*background: #fff;*/
		width:60%;
		height: 50px;
		top: 50px;
		left: 450px;
		
	}

	#menu ul{

		list-style: none;
		margin: 0px;
		position: relative;
		top: 15px;
		left: 100px;
		}

	#menu ul li{

		display: inline;
		font-size: 20px;
		font-weight: bold;
		/*border-right: 2px solid #000;*/
		padding-left: 25px;
		padding-right: 15px;
		color: #000;
	}

	#sect-1-box{

		position: relative;
		width: 650px;
		height: 150px;
		background: #fff;
		left: 30px;
		top: 20px;
	}

	#sect-1-box img{

		position: absolute;
		width: 650px;
		top: 0px;

	}

	#block{

		position: absolute;
		background: #fff;
		width: 250px;
		height: 120px;
		left: 50px;
		top: 315px;
	}

	#block h2{

		color: #000;
		font-weight: bold;
		font-size: 35px;
		margin: 0px;
		position: absolute;
		text-transform: uppercase;
	}

	#box{

		position: absolute;
		/*background: #fff;*/
		width: 300px;
		height: 128px;
		left: 350px;
		top: 305px;
	}

	#box h2{

		position: absolute;
		color: #000;
		font-size: 18px;
		margin: 0px;
		top: 10px;
	}

	#box button{

		top: 105px;
		color: #000;
		text-transform: uppercase;
		font-size: 20px;
		position: absolute;
		border-color: pink;
		background-color: pink;
	}

	#bud{

		position: relative;
		background: #234;
		width: 350px;
		height: 500px;
		left: 850px;
		/*top: 0px;*/
		bottom: 135px;
	}

	#bud h1{

		position: absolute;
		color: gold;
		text-transform: uppercase;
		font-size: 30px;
		font-weight: bold;
		margin: 0px;
		left: 10px;
		top: 10px;
	}

	#cone{

		/*background: #000;*/
		position: relative;
		width: 280px;
		height: 100px;
		top: 50px;
		display: inline-block;
		padding-bottom: 17px;
	}

	#cone p{

		font-size: 18px;
		color: #fff;
		position: relative;
		font-weight: bold;
		left: 10px;
	}

	#cone h2{

		color: #ccc;
		font-size: 19px;
		position: relative;
		/*font-style: serif;*/
		left: 10px;
	}

	#poll{

		background: #fff;
		width: 380px;
		height: 250px;
		position: relative;
		left: 30px;
		top: 90px;
		display: inline-block;
	}

	#poll img{

		position: absolute;
		width: 110px;
		height: 200px;

	}

	#poll h3{

		color: #ccc;
		font-size: 29px;
		left: 120px;
		position: absolute;
		top: 0px;

	}

	#poll p{

		color: #000;
		font-size:18px;
		position: absolute;
		top: 50px;
		left: 120px;
		font-weight: bold;
		text-transform: uppercase;

	}

	#poll h1{

		color: #000;
		font-size: 18px;
		position: absolute;
		left: 120px;
		top: 100px;
		font-weight: bold;

	}

	.sidebar{

		height: 100%;
		width: 0;
		position: fixed;
		z-index: 1;
		top: 0;
		left: 0;
		background-color: #234;
		overflow-x: hidden;
		padding-top: 60px;
		transition: 0.5s;
	}	

.sidebar a {

		padding: 8px 8px 8px 32px;
		text-decoration: none;
		font-size: 40px;
		color: #818181;
		display: block;
		transition: 0.3s;
		padding-bottom: 20px;
	}

	.sidebar a:hover{

		color: #f1f1f1;
	}

	.sidebar .closebtn {

		position: absolute;
		top: 0;
		right: 25px;
		font-size:px;
		margin-left: 50px;
	}

	.openbtn{

		font-size: 20px;
		cursor: pointer;
		background-color: #111;
		color: white;
		padding: 10px 15px;
		border: none;	

	}

	.openbtn:hover{

		background-color: #444;
	}

	#main{

		transition: margin-left .5s;

		padding: 20px;
	}

	@media screen and (max-height: 450px){

		.sidebar {padding-top: 15px;}
		.sidebar a {font-size: 18px;}
	}
  
  </style>

<body>
	<div class="container">
		<div class="header">
			<div id="logo">
				<div id="mysidebar" class="sidebar">
					<a href="javascript:void(0)" class="closebtn" onclick="closeNav()">&times;</a>
					<a href="#">Home</a>
					<a href="#">New</a>
					<a href="#">Popular</a>
					<a href="#">Trending</a>
					<a href="#">Categories</a>
				</div>

				<div #main>
					<button class="openbtn" onclick="openNav()">&#9776;</button>
				</div>
				<img src="assets/images/logo.png">
			</div>

			<div id="menu">
				<ul>
					<li><a href="index1.html" style="color: #455aac">Home</a></li>
					<li><a href="new.html" style></a>New</li>
					<li><a href="popular.html"></a>Popular</li>
					<li><a href="trending.html"></a>Trending</li>
					<li style="border: none;" ><a href="Categories.html"></a>Categories</li>
				</ul>
			</div>
		</div>
		<div class="section1">
			<div id="sect-1-box">
				<img src="assets/images/maze.jpg">
			</div>

			<div id="block">
				<h2>The bright future of Web3.0 ?</h2>
			</div>
			<div id="box">
				<h2>We dive into the next evolution of the web that claims to power of the platform into the hands of the people. But, is it really fufilling its promise?</h2>
				<button>Read More</button>
			</div>
			<div id="bud">
				<h1>New</h1>
				<div id="cone">
					<p>Hydrogen VS ELECTRICAL CAR</p>
					<h2>Will hydrogen-fueled cars ever catch up with EVS ?</h2>
				</div>
				<div id="cone">
					<p>THE DOWNSIDE OF AI ARTISTRY</p>
					<h2>What are the possible adverse effects of on-demand AI mage generation ?</h2>
				</div>
				<div id="cone">
					<p>Is VC Funding Drying Up ?</p>
					<h2>Private funding by VC firms is down by 50% YOY. We'll take a look what that means</h2>
				</div>
			</div>
		</div>
		<div class="section2">
			<div id="poll">
				<img src="assets/images/gamebox.jpg">
				<h3>01</h3>
				<p>Reviving retro PCs</p>
				<h1>What happens when old PC are given modern upgrade ?</h1>
			</div>
			<div id="poll">
				<img src="assets/images/laptop.jpg">
				<h3>02</h3>
				<p>Top ten laptop of 2022</p>
				<h1>Our best picks for various needs and budget</h1>
			</div>
			<div id="poll">
				<img src="assets/images/gamepad.jpg">
				<h3>03</h3>
				<p>The growth of gaming</p>
				<h1>How the pandemic has sparked fresh opportunities</h1>
			</div>
		</div>

		<script type="text/javascript">
		function openNav() {
			 document.getElementById("mysidebar").style.width = "250px";
			 document.getElementsById("main").style.marginLeft = "250px";		
			}

			function closeNav(){

				document.getElementById("mysidebar").style.width = "0";
				document.getElementById("main").style.marginLeft = "0";
			}
	</script>
	</div>
</body>
</html>
