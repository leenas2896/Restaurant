<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta http-equiv="X-UA-Compatible" content = "IE=edge">
<meta name = "viewport" content="width=device-width, initial-scale=1">
<title>Santushti</title>
<link rel="stylesheet" href="bootstrap-3.4.1-dist/css/bootstrap.min.css">
<link rel="stylesheet" href="bootstrap-3.4.1-dist/css/styles.css">
<link href="https://fonts.googleapis.com/css2?family=Oxygen:wght@300;400;700&display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Niconne&family=Seaweed+Script&display=swap" rel="stylesheet">
	</head>
<body>
	<header>
		<nav id="header-nav" class ="navbar navbar-default">
			<div class="container">
				<div class ="navbar-header">
					<a href="Restro.html" class="pull-left visible-md visible-lg">
						<div id="logo-img" alt="Logo image"></div>
					</a>
					<div class="navbar-brand">
						<a href="Restro.html"><h1> Santushti Masala Mantra</h1> </a>
					</div>
					<button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#collapsable-nav" aria-expanded="false">
						<span class="sr-only">Toggle navigation</span>
						<span class="icon-bar"></span>
						<span class="icon-bar"></span>
						<span class="icon-bar"></span>
					</button>
				</div>

				<div id="collapsable-nav" class="collapse navbar-collapse">
					<ul id="nav-list" class="nav navbar-nav navbar-right">
						<li class="visible-xs active">
						<a href= "Restro.html">
							<span class="glyphicon glyphicon-home"></span>Home</a>

						</li>
						<li>
							<a href="menu-categories.html">
								<span class="glyphicon glyphicon-cutlery"></span><br class="hidden-xs"> Menu </a>
						</li>
						<li>
							<a href="#">
								<span class="glyphicon glyphicon-info-sign"></span><br class="hidden-xs">About</a>
						</li>
						<li>
							<a href="#">
								<span class="glyphicon glyphicon-certificate"></span><br class="hidden-xs">Awards</a>
						</li>
						<li id="phone" class="hidden-xs">
							<a href="tel:443-529-5008">
								<span>443-529-5008</span></a><div>*At your door</div>
						</li>

					</ul>

			</div>
		</nav>
	</header>


	<div id="call-btn" class="visible-xs">
		<a class="btn" href="tel:443-529-5008">
			<span class="glyphicon glyphicon-earphone"></span>
			443-529-5008
		</a>
	</div>
	<div id="xs-deliver" class="text-center visible-xs">At your door</div>


	<div id="main-content" class="container">
		<div class="jumbotron">
			<img src="bootstrap-3.4.1-dist/images/picture_768.jpg"  class="img-responsive visible-xs" alt= "Picture of restaurant">
		</div>

		<div id="home-tiles" class="row">
			<div class="col-md-4 col-sm-6 col-xs-12">
				<a href="menu-categories.html"><div id="menu-tile"><span>
				menu</span></div></a>
			</div>
			<div class="col-md-4 col-sm-6 col-xs-12">
				<a href="single-category.html"><div id="specials-tile"><span>
				specials</span></div></a>
			</div>

		<div class="col-md-4 col-sm-12 col-xs-12">
			<a href="https://goo.gl/maps/jmmGAK1AsboFuwcm9" target="blank">
				<div id="map-tile">
					<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3720.232886765995!2d81.33293641493529!3d21.182905585915034!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3a293cca2317c365%3A0x86850a4cb326d27d!2sSantushti%20Restaurant!5e0!3m2!1sen!2sus!4v1595976302917!5m2!1sen!2sus" width="100%" height="250" frameborder="0" style="border:0;" allowfullscreen="" aria-hidden="false" tabindex="0"></iframe>
					<span>map</span>
				</div>
			</a>
		</div>
	</div> 






	<footer class="panel-footer">
		<div class="container">
			<div class="row">
				<section id="hours" class="col-sm-4">
					<span> Hours:</span><br>
					Mon-Fri:10:00am-10:00pm<br>
					Sat-Sun:10:00am-11:30pm<br>
					<hr class="visible-xs">
				</section>
				<section id="address" class="col-sm-4">
					<span> Address:</span><br>
					Shop No-69, Zonal Market Road<br>
					Sector-10, Bhilai, Chhattisgarh<br>
					Pin-490006
					<p>*Delivery area within 3-4km, with minimum order
					of Rs.350 plus charge of Rs.50 for all deliveries.</p>
					<hr class="visible-xs">
				</section>
				<section id="testimonials" class="col-sm-4">
					<p> "Best Chicken Biryani I ever had!!"</p>
					<p> "Amazing Food! Great service"</p>
				</section>
			</div>
			<div class="text-center">&copy; Copyright Santushti Masala Mantra 2004
			</div>
		</div>
	</footer>
<script src="bootstrap-3.4.1-dist/js/jquery-2.1.4.js"></script>
<script src="bootstrap-3.4.1-dist/js/bootstrap.min.js"></script>
<script src="js/script.js"></script>
</body>
</html>

body{
	font-size: 16px;
	color:#fff;
	background-color:  #000000;
	font-family: 'Oxygen', sans-serif;
}


/**HEADER**/
#header-nav{
	background-color:#8B0000;
	border-radius: 0;
	border: 0;
}

#logo-img{
	background:url('../images/restaurant-logo1.jpg') no-repeat;
	width: 150px;
	height:150px;
	margin:10px 15px 10px 0;
}

.navbar-brand {
	padding-top:25px;
}

.navbar-brand h1{
	font-family: 'Niconne', cursive;

	color:  #FFFAFA;
	font-size:3em;
	text transform:uppercase;
	
	text-shadow: 1px 1px 1px #222;
	margin-top:0;
	margin-top:0;
	line-height:.75;
}
.navbar-brand a:hover, .navbar-brand a:focus{
	text-decoration: none;
}

#nav-list{
	margin-top:10px;
}

#nav-list a{
	color: #FFFF00;
	text-align: center;
}

#nav-list a:hover{
	background:  #2F4F4F;
}

#nav-list a span{
	font-size: 1.8em;
}

#phone{
	margin-top: 5px;

}

#phone a{
	text-align:right;
	padding-bottom: 0;

}

#phone div{
	color:#557c3e;
	text-align: right;
	padding-right: 15px;
}

.navbar-header button.navbar-toggle, .navbar-header .icon-bar{
	border: 1px solid  #FFFF00;
}

.navbar-header button.navbar-toogle{
	clear:both;
	margin-top:-30px;

}

/***End header***/

.panel-footer{
	margin-top:30px;
	padding-top:35px;
	padding-bottom: 30px;
	background-color: #222;
	border-top: 0;
}

.panel-footer div.row{
	margin-bottom:35px;

}


#hours, #address{
	line-height:2;
}

#hours > span, #address >span {
	font-size:1.3em;
}

#address p{
	color: #557c3e;
	font-size: .8em;
	line-height: 1.8;
}


#testimonials{
	font-style: italic;
}


#testimonials p:nth-child(){
	margin-top:25px;
}
/***HOME PAGE***/

.container .jumbotron{
	box-shadow:0 0 50px #3F0C1F;
	border: 2px solid #3F0C1F;
}

#menu-tile, #specials-tile, #map-tile{
	height: 250px;
	width:100%;
	margin-bottom: 15px;
	position: relative;
	border:2px solid #3F0C1F;
	overflow:hidden;
}

#menu-tile:hover, #specials-tile:hover, #map-tile:hover{
	box-shadow:0 1px 5px 1px #cccccc;
}

#menu-tile
{
	background:url('../images/menu1.jpg')no-repeat;
	background-position: center;
}

#specials-tile
{
	background:url('../images/special.jpg')no-repeat;
	background-position: center;
}

#menu-tile span, #specials-tile span, #map-tile span{
	position: absolute;
	bottom:0;
	right:0;
	width:100%;
	text-align: center;
	font-size:1.6em;
	text-transform: uppercase;
	background-color: #000;
	color: #fff;
	opacity: .8;
}


.category-tile{
	position: relative;
	border: 2px solid #3F0C1F;
	overflow:hidden;
	width: 200px;
	height: 200px;
	margin:0 auto 15px;
}


.category-tile span{
	position:absolute;
	bottom:0;
	right:0;
	width:100%;
	text-align: center;
	font-size: 1.2em;
	text-transform: uppercase;
	background-color: #000;
	color:#fff;
	opacity: .8;

}

.category-tile:hover{
	box-shadow:0 1px 5px 1px #cccccc;
}

#menu-categories-title + div{
	margin-bottom:50px;
}
/*END OF MENU CATEGORIES*/
/*Single CATEGOry page*/

.menu-item-tile{
	margin-bottom:25px;
}

.menu-item-tile hr{
	width:80%;
}

.menu-item-tile .menu-item-price{
	font-size:1.1em;
	text-align: right;
	margin-top: -15px;
	margin-right: -15px;
}

.menu-item-tile .menu-item-price span{
	font-size: .6em;
}

.menu-item-photo{
	position:relative;
	border: 2px solid #3F0C1F;
	overflow: hidden;
	padding: 0;
	margin-right: -15px;
	margin-left: auto;
	margin-bottom: 20px;
	max-width: 250px;
}


.menu-item-photo div{

	position: absolute;
	bottom:0;
	right:0;
	width:80px;
	background-color: #557c3e;
	text-align: center;
}


.menu-item-description{
	padding-right: 30px;
}


h3.menu-item-title{
	margin: 0 0 10px;
}

.menu-item-details{
	font-size: .9em;
	font-style: italic;
}

/***end single category page***/



/***Large devices only***/
@media(min-width:1200px){
.jumbotron{
	background:url('../images/picture(1).jpg')no-repeat;
	height:675px;
	box-shadow: 0 0 50px #3F0C1F;
	border: 2px solid #3F0C1F;
}
}


/***Medium devices only***/
@media(min-width: 992px) and (max-width: 1199px){
	#logo-img{
		background:url('../images/restaurant-logo2.jpg') no-repeat;
	width: 100px;
	height:100px;
	margin:5px 5px 5px 0;;
	}
	.jumbotron {
		background: url('../images/picture_880.jpg')no-repeat;
		height:558px;
		box-shadow:0 0 50px #3F0C1F;
		border:2px solid #3F0C1F ;
		background-size: cover;
	}
}


/***Small devices only***/
@media(min-width: 768px) and (max-width: 991px){
	.jumbotron{
		background: url('../images/picture_768.jpg')no-repeat;
		height:432px;
		box-shadow:0 0 50px #3F0C1F;
		border:2px solid #3F0C1F ;
	}
	
}


/***Extra Small devices only***/
@media(max-width: 767px){
	/*Header*/
	.navbar-brand{
		padding-top: 10px;
		height:80px;
	}

.navbar-brand h1{/*Restaurant Name*/
padding-top: 10px;
font-size: 5vw /*view width*/;}


#collapsable-nav a{
	font-size:1.2em;}


#collapsable-nav a span{
	font-size:1em;
margin-right:5px;}

#call-btn>a{
	font-size:1.5em;
	color: #FFD700;
	display: block;
	margin:0 20px;
	padding:10px;
	border:2px solid #fff;
	background-color: #8B0000;
}

#xs-deliver{
	margin-top: 5px;
	font-size: .7em;
	letter-spacing: .1em;
	text-transform: uppercase;
}


.panel-footer section{
	margin-bottom:30px;
	text-align:center;
}

.panel-footer section:nth-child(3){
	margin-bottom:0;
}

.panel-footer section hr{
	width:50%;
}
.container .jumbotron{
	margin-top: 30px;
	padding:0;
	box-shadow: 0 0 50px #3F0C1F;
	border: 2px solid #3F0C1F;
}

#menu-tile, #specials-tile{
	width:360px;
	margin:0 auto 15px;
}
}
/*Extra extra small devices*/

@media(max-width: 479px)
{
.navbar-brand h1{
	padding-top: 5px;
	font-size: 6vw;
}

	#menu-tile, #specials-tile{
	width:280 px;
	margin:0 auto 15px;} 


.col-xxs-12{
	position: relative;
	min-height: 1px;
	padding-right: 15px;
	padding-left: 15px;
	float:left;
	widht:100%;

	}}
