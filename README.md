<!DOCTYPE html>
<html lang="ko">
<head>
	<meta charset="UTF-8">
	<title>Document</title>


	<!-- 부스트  -->
	<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
	

	<!-- 폰트  -->
	<link href="https://fonts.googleapis.com/css?family=Advent+Pro|Audiowide|Montserrat&display=swap" rel="stylesheet">

	<!--font-family: 'Advent Pro', sans-serif;
	font-family: 'Audiowide', cursive;
	font-family: 'Montserrat', sans-serif; -->
	<style>
		*{
			margin: 0;
			padding: 0;
			box-sizing: border-box;
		}

		body{
			background-image: url(https://i.postimg.cc/W4YrwRG8/bgimg.jpg);
			background-repeat: no-repeat;
			background-size: cover;
			background-position: center center;
		}


		.maininfo{
			font-family: 'Advent Pro', sans-serif;
			margin-top: 100px;
			text-align: center;
			color: white;
			margin-bottom: 30px;
		}
		

		.maininfo h2{
			display: inline-block;
			font-size: 50px;
			padding: 20px 30px;
			border: 4px solid white;
			margin-bottom: 30px;
		}
	

		.maininfo h1{
			font-size: 70px;
		}

		.white{
			background-color:white;
		}

		.navi{
			margin-left: auto;
			margin-right: auto;
			height: 60px;
			background-color: #323232;
			width: 100%;
		}

		.navi #menu{
			list-style: none;
		}

		.navi #menu li{
			width: 25%;
			float: left;
			line-height: 60px;	
			text-align: center;
		}

		.navi #menu li a{
			color: white;
			font-size: 14px;
			text-decoration: none;
			font-family: 'Montserrat', sans-serif;
			padding: 0px 20px;
		}

		.navi #menu li .white1{
			color: #454545;
			font-weight: bold;
		}

		.navi #menu li a:HOVER{
			display: block;
			color: #454545;
			font-weight: bold;
			background-color: white;
		}

		.navi h2{
				border:2px solid white;
				color: white;
				display: inline;
				line-height: 60px;
				padding: 5px 10px;
		}


		.footer{
			float: right;
			margin-bottom: -60px;
		}

		.footer a{
			float: left;
			line-height: 60px;
			margin-left: 20px;
			margin-right: 20px;
			text-decoration: none;
			visibility: hidden;
		}

		.footer a img{
			vertical-align: middle;	
		}


		.page{
			margin-left: auto;
			margin-right: auto;
			width: 100%;
		}


		.carousel-item{
			height: 400px;
			background-color: black;
		}


		@media (min-width: 992px){
			.navi{
				width: 80%;
			}

			.navi #menu li{
			width: 10%;
			float: left;
			}

			.page{
				width: 80%;
			}

			.maininfo{
			font-family: 'Advent Pro', sans-serif;
			margin-top: 150px;
			text-align: center;
			color: white;
			margin-bottom: 60px;
			}

			.maininfo h2{
			display: inline-block;
			font-size: 50px;
			padding: 20px 30px;
			border: 4px solid white;
			margin-bottom: 30px;
			}
	

			.maininfo h1{
			font-size: 120px;
			}

			.footer a{
			line-height: 60px;
			margin-left: 20px;
			margin-right: 20px;
			text-decoration: none;
			visibility: visible;
			}

			.carousel-item{
			background-color: black;
			height: 800px;
			position: center center;
			size: cover;
			}
			footer{
				height: 60px;
			}

			}
	</style>
</head>
<body>
	<div class="maininfo">
		<h2>B O U N G' S</h2>
		<h1>P O R T F O L I O</h1>
	</div>
	
	
	<!-- 네비바 -->
	<nav class="navi">

		<ui id="menu">
			<li class="white"><a href="#" class="white1">MAIN</a></li>
			<li><a href="MOTION.html">MOTION</a></li>
			<li><a href="product.html">PRODUCT</a></li>
			<li><a href="introduce.html">INTRODUCE</a></li>
		</ui>

		<div class="footer">
		<a href="https://ko-kr.facebook.com/"><img src="https://applets.imgix.net/https%3A%2F%2Fassets.ifttt.com%2Fimages%2Fchannels%2F36996033%2Ficons%2Fon_color_large.png%3Fversion%3D0?ixlib=rails-2.1.3&w=240&h=240&auto=compress&s=a2564b704df5acaa8d9da981be316963" width="20"></a>
		<a href="https://www.google.com"><img src="https://i.postimg.cc/j5ZKrv83/Untitled-1.png" width="20"></a>
		<a href="https://www.instagram.com/?hl=ko"><img src="https://applets.imgix.net/https%3A%2F%2Fassets.ifttt.com%2Fimages%2Fchannels%2F28%2Ficons%2Fon_color_large.png%3Fversion%3D0?ixlib=rails-2.1.3&w=240&h=240&auto=compress&s=edcfefd7633937ca3b3e0cf98a873f58" width="20"></a>
		</div>
	</nav>
	<!-- 본문내용 -->
	<div class="page">
		<!--상단 넘기기 바-->
				<div id="carouselExampleControls" class="carousel slide" data-ride="carousel">
				  <div class="carousel-inner">
				  	<!-- 펜이미지 -->
				    <div class="carousel-item active">
				      <img src="https://i.postimg.cc/qBPhhcHF/MAMA1.png" height="100%" width="auto" class="d-block w-100" alt="...">
				    </div>
				    <div class="carousel-item">
				      <img src="https://i.postimg.cc/qqLrjdgg/1111.png" height="100%" width="100%" class="d-block w-40" alt="...">
				    </div>
				    <!-- 펜이미지 -->
				    <div class="carousel-item">
				      <img src="https://i.postimg.cc/3JVDMVZd/Untitled-1-Recovered.png" height="100%" width="100%" class="d-block w-40" alt="...">
				    </div>
				    <div class="carousel-item">
				      <img src="https://i.postimg.cc/RhCyCJVV/2222.png" height="100%" width="100%" class="d-block w-40" alt="...">
				    </div>
				  </div>
				  <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
				    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
				    <span class="sr-only">Previous</span>
				  </a>
				  <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
				    <span class="carousel-control-next-icon" aria-hidden="true"></span>
				    <span class="sr-only">Next</span>
				  </a>
				</div>
				<footer></footer>
	</div>
	<!-- 본문내용끝 -->
	<!-- ---------------------------------------------------------------- -->
	














	<!-- 스크립트 -->
	<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
	<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
	<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
</body>
</html>
