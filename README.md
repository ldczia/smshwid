
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title></title>
	<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css" integrity="sha384-xOolHFLEh07PJGoPkLv1IbcEPTNtaed2xpHsD9ESMhqIYd0nLMwNLD69Npy4HI+N" crossorigin="anonymous">
	<script src="https://cdn.jsdelivr.net/npm/jquery@3.7.1/dist/jquery.slim.min.js"></script>
	<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
	<script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/js/bootstrap.bundle.min.js"></script>
	<style type="text/css">
		h5
		{
			color: black;
			font-size: 30px;
			text-decoration: none;
		}
		h4
		{
			color: black;
			font-size: 30px;
			text-decoration: none;
		}
		.deneme:hover
		{
			background-color: lightgrey;
		}
	</style>
</head>
<body>
	<nav class="navbar navbar-expand-md bg-dark navbar-dark">
		<a class="navbar-brand" href="#">SEAT Car</a>
		<button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#collapsibleNavbar">
			<span class="navbar-toggler-icon"></span>
		</button>
		<div class="collapse navbar-collapse" id="collapsibleNavbar">
			<ul class="navbar-nav">
				<li class="nav-item">
					<a class="nav-link" href="index.html">SEAT</a>
				</li>
				<li class="nav-item">
					<a class="nav-link" href="iletisim.htlm">İletişim</a>
				</li>
				<li class="nav-item">
					<a class="nav-link" href="destek.html">Destek</a>
				</li>    
			</ul>
		</div>  
	</nav>
	<br>

	<div class="container">
		<div class="row">
			<div id="demo" class="carousel slide" data-ride="carousel">

				<!-- Indicators -->

				<ul class="carousel-indicators">
					<li data-target="#demo" data-slide-to="0" class="active"></li>
					<li data-target="#demo" data-slide-to="1"></li>
					<li data-target="#demo" data-slide-to="2"></li>
				</ul>

				<!-- The slideshow -->
				<div class="carousel-inner">
					<div class="carousel-item active">
						<img src="resimler/la.jpg" alt="Los Angeles" width="1140" height="600">
					</div>
					<div class="carousel-item">
						<img src="resimler/chicago.jpg" alt="Chicago" width="1140" height="600">
					</div>
					<div class="carousel-item">
						<img src="resimler/ny.jpg" alt="New York" width="1140" height="600">
					</div>
					<a class="carousel-control-prev" href="#demo" data-slide="prev">
						<span class="carousel-control-prev-icon"></span>
					</a>
					<a class="carousel-control-next" href="#demo" data-slide="next">
						<span class="carousel-control-next-icon"></span>
					</a>
				</div>
			</div>
			
			<h2>Modeller</h2>
		</div>
		<div class="row mb-5">
			<div class="col-md-6 col-lg-4">
				<a href ="kesfet1.html"><img src="resimler/seat1.png" class="deneme"> </a>
				<h4>Seat Ibiza</h4>
				<h5>Keşfedin  ></h5>
			</div>
			<div class="col-md-6 col-lg-4" >
				<a href ="kesfet2.html"><img src="resimler/seat2.png" class="deneme"> </a>
				<h4>Seat Arona</h4>
				<h5>Keşfedin  ></h5>
			</div>
			<div class="col-md-6 col-lg-4" >
				<a href ="kesfet3.html"><img src="resimler/seat3.png" class="deneme"> </a>
				<h4>Seat Leon</h4>
				<h5>Keşfedin  ></h5>
			</div>
			<div class="col-md-6 col-lg-4">
				<a href ="kesfet4.html"><img src="resimler/seat4.png" class="deneme"> </a>
				<h4>Seat Tarraco</h4>
				<h5>Keşfedin  ></h5>
			</div>
		</div>
		
	</div>
</div>
</body>
</html>

