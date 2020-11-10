<h1>waliullah</h1>
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>ngo_home</title>
	<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
   <link rel="stylesheet" href= "https://maxcdn.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css"> 
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/js/bootstrap.min.js"></script>
	
	<style type="text/css">
		*{
			padding: 0;
			margin: 0;
			text-decoration: none;
			list-style: none;
			box-sizing: border-box;
		}
		
		nav{
			position: ;
			background: #0082e6;
			height: 80px;
			width: 100%;
		}
		label.logo{
			color: white;
			font-size: 35px;
			line-height: 80px;
			padding: 0 100px;
			font-weight: bold;
		}
		nav .hul{
			float: right;
			margin-right: 20px;
		}
		nav .hul .hli {
			display: inline-block;
			line-height: 80px;
			margin: 0 5px;
		}
		nav .hul .hli a{
			color: black;
			font-size: 17px;

			padding: 7px 13px;
			border-radius: 3px;
			text-transform: uppercase; /* text transformation to upper case*/
		}
		a.active,a:hover{
			background: #1b9bff;
			transition: .5s;
		}
		.checkbtn{
			font-size: 30px;
			color: white;
			float: right;
			line-height: 80px;
			margin-right: 40px;
			cursor: pointer;
			display: none;
		}
		#check{
			display: none;
		}
		@media(max-width: 952px){
			label.logo{
				font-size: 25px;
				padding-left: 5px;
				
			}
			nav .hul .hli a{
				font-size: 16px;

			}
		}
		@media(max-width: 858px){
			.checkbtn{
				display: block;
			}
			.hul{
				position: fixed;
				width: 100%;
				height: 100vh;
				background: #2c3e50;
				top: 80px;
				left: -100%;
				
				text-align: center;
				transition: all .5s;
			}
			nav .hul .hli{
				display: block;
				margin: 40px 0;
				line-height: 30px;
			}
			nav .hul .hli a{
				font-size: 20px;
				font-weight: 100;
			} 
			 a.active , a:hover{
				background: none;
				color: #0082e6;
			}
			#check:checked ~ .hul{
				left: 0;
			}
		}

		section{
			background: url(htps://tse4.mm.bing.net/th?id=OIP.La19-SmX3qdymbPz7AXOPAHaE_&pid=Api&P=0&w=270&h=183) no-repeat;
			background-size: cover;
			height: calc(100vh - 80px);
			
		}
		
		@media(max-width: 858px){
			h1{
				font-size: 35px;
			}
		}


		/* search nav */
		

/* footer*/

	
section {
    padding: 60px 0;
}

section .section-title {
    text-align: center;
    color: #007b5e;
    margin-bottom: 50px;
    text-transform: uppercase;
}
#footer {
    background: #007b5e !important;
}
#footer h5{
	padding-left: 10px;
    border-left: 3px solid #eeeeee;
    padding-bottom: 6px;
    margin-bottom: 20px;
    color:#ffffff;
}
#footer a {
    color: #ffffff;
    text-decoration: none !important;
    background-color: transparent;
    -webkit-text-decoration-skip: objects;
}
#footer ul.social li{
	padding: 3px 0;
}
#footer ul.social li a i {
    margin-right: 5px;
	font-size:25px;
	-webkit-transition: .5s all ease;
	-moz-transition: .5s all ease;
	transition: .5s all ease;
}
#footer ul.social li:hover a i {
	font-size:30px;
	margin-top:-10px;
}
#footer ul.social li a,
#footer ul.quick-links li a{
	color:#ffffff;
}
#footer ul.social li a:hover{
	color:#eeeeee;
}
#footer ul.quick-links li{
	padding: 3px 0;
	-webkit-transition: .5s all ease;
	-moz-transition: .5s all ease;
	transition: .5s all ease;
}
#footer ul.quick-links li:hover{
	padding: 3px 0;
	margin-left:5px;
	font-weight:700;
}
#footer ul.quick-links li a i{
	margin-right: 5px;
}
#footer ul.quick-links li:hover a i {
    font-weight: 700;
}

@media (max-width:767px){
	#footer h5 {
    padding-left: 0;
    border-left: transparent;
    padding-bottom: 0px;
    margin-bottom: 10px;
}
}

.top2{
	margin-left: -15px;
}

.top_text_field {
  position: absolute;
  top: 50%;
  left: 30%;
  transform: translate(-50%, -50%);
  font-weight: 100;
  background: rgb(0, 0, 0);
  background: rgba(0, 0, 0, 0.6); 
  color: #f1f1f1;
  width: 60%;
  padding: 20px;
}

.buttom {
  position: relative;
  text-align: center;
  color: black;

}
.centered {
  position: absolute;
  top: 50%;
  left: 20%;
  transform: translate(-50%, -50%);
  font-weight: 100;
  background: rgb(0, 0, 0);
  background: rgba(0, 0, 0, 0.7); 
  color: #f1f1f1;
  width: 70%;
  padding: 20px;
}

.amount{
	width: 50%;
	height: 35px;
	border-radius: 10px 10px 10px 10px ;
	border: 1px solid;
  
  box-shadow: 1px 6px #888888;
}
.button {
  background-color: #75962d; 
  border: none;
  color: white;
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  cursor: pointer;
}

@media(max-width: 858px){
	h1{
		font-size: 25px;
		margin-left: 20px;
		padding-left: 20px
	}
	.button{
		padding-left: 5px;
		margin-left: 5px;
	}
	.top2{
		padding-left: 5px;
		margin-left: 5px;
	}
}




.newscursor{
	cursor: pointer;

}	
.newscursor:hover{
	text-decoration-color: blue;
	background-color: white;
}





	</style>




</head>
<body>
	<nav>
		<input type="checkbox" id="check">
		<label for="check" class="checkbtn">
			<i class="fa fa-align-justify"></i>
		</label>
		<label class="logo"><b> Hindustan Care</b></label>
		<ul class="hul">
			<li class="hli"><a class="active" href="home.html"><i class="fa fa-home"> Home</i></a></li>
			<li class="hli"><a href="about_us.html"><i class="fa fa-user"></i> About Us</a></li>
			<li class="hli"><a href="contact_us.html"><i class="glyphicon glyphicon-earphone"> Contact</i></a></li>
			<li class="hli"><a href="">Blogs</a></li>
			<li class="hli "><a href="donate.html" class="border border-dark bg-success"> <i class="fas fa-hand-holding-usd "></i><b style="color: white;">Donate</b> </a></li>
			<li class="hli">  <form class="form-inline">
    <input class="form-control mr-sm-2 border border-dark" type="search" placeholder="Search..." aria-label="Search">
    <button class="btn btn-outline-success my-2 my-sm-0 border border-white text-white" type="submit">Search</button>
  </form>
</li>
		</ul>
	</nav>
<hr >



<div class="row">
    <div class="col-xs-3 news" style="background-color: ; height: 500px;">
    	<div class=" " style="width: 100%; height: 100%;">
		<div style="padding: 20px">
			<fieldset style="padding: 14px; font-family: curier; ">
				<center>
					<legend style="background-image: linear-gradient(to right ; white, lightskyblue ,lightskyblue ,lightskyblue , white); font-size: 18px;">
						<b>NEWS & EVENTS</b>
					</legend>
				</center>
				<marquee direction="up" scrollamount="3" onmouseover="this.stop()" onmouseout="this.start()" height="320" class="anim">
					<h3>
						<img src="http://rdec.in/assets/images/new.gif" alt="new">
						<i>
							<a class="newscursor">""Requirement of book for students "</a>
						</i>
						<br><br>
					</h3>
					<h3>
						<img src="http://rdec.in/assets/images/new.gif" alt="new">
						<i>
							<a class="newscursor">""Seminar on 2nd dec in touw hall"</a>
						</i>
						<br><br>
					</h3>
					<h3>
						<img src="http://rdec.in/assets/images/new.gif" alt="new">
						<i>
							<a class="newscursor">"" hindustaam care thanks all who help and support us"</a>
						</i>
						<br><br>
					</h3>
					<h3>
						<img src="http://rdec.in/assets/images/new.gif" alt="new">
						<i>
							<a class="newscursor">""sunday is not holiday its fun day"</a>
						</i>
						<br><br>
					</h3>
				</marquee>
			</fieldset>
		</div>
	</div>
 	</div>
    
    <div class="col-xs-9 gal" style="background-color:green; height: 500px;">
	    <div class="top2">
		  <img src="educate.jpg" alt="Snow" style="width:100%; height: 500px;">
		  
		  <div class="top_text_field  "><h1><b>HELP CARE AND SUPPORT<br> <i style="color: #f2ec30;">HINDUSTAN CARE</i></b></h1>
		  	 	
		  	 	 
		  	 	 <i class="border border-dark"><a href="donate.html" class="button ">Donate Now</a></i>
		  	 	 
		  	 	

		  </div>
		  
		</div>
    </div>
	   
 </div>

<div class=" " style="width: 100%; height: 500px; background-color: gray;">
	<h1 class="text-center  text-white" style="padding-top: 230px;">blank field for discription </h1>
</div>



<div class="row ">
	<div class="card col-lg" style="width: rem;">
  <img class="card-img-top" src="education.jpg" alt="Card image cap">
  <div class="card-body">
    <h4 class="card-title">Education</h4>
    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
    <a href="#" class="btn btn-primary">Donate Now</a>
  </div>
</div>
<div class="card col-lg" style="width: rem;">
  <img class="card-img-top" src="health.jpg" alt="Card image cap">
  <div class="card-body">
    <h4 class="card-title">Health</h4>
    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
    <a href="#" class="btn btn-primary">Donate Now</a>
  </div>
</div>
<div class="card col-lg" style="width: rem;">
  <img class="card-img-top" src="food.jpg" alt="Card image cap">
  <div class="card-body">
    <h4 class="card-title">Food</h4>
    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
    <a href="#" class="btn btn-primary">Donate Now</a>
  </div>
</div>
<div class="card col-lg" style="width: rem;">
  <img class="card-img-top" src="things.jpg" alt="Card image cap">
  <div class="card-body">
    <h4 class="card-title">Things</h4>
    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
    <a href="#" class="btn btn-primary">Donate Now</a>
  </div>
</div>
</div>




<div class="buttom">
  <img src="cookingfood.jpg" alt="Snow" style="width:100%; height: 500px;">
  
  <div class="centered "><h1><b>HELP CARE AND SUPPORT<br> <i style="color:#9ef230;">HINDUSTAN CARE</i></b></h1>
  	 	<form>
  	 	<input type="number" id="amount" class="amount" name="amount" placeholder=" Enter any amount you wish to donate" required>
  	 	 <br><br>
  	 	 
  	 	 <a href="#" class="button">Donate Now</a>
  	 	 
  	 	</form>

  </div>
  
</div>


	<section id="footer">
		<div class="container">
			<div class="row text-center text-xs-center text-sm-left text-md-left">
				<div class="col-xs-12 col-sm-4 col-md-4">
					<h5>Quick links</h5>
					<ul class="list-unstyled quick-links">
						<li><a href=" "><i class="fa fa-angle-double-right"></i>Home</a></li>
						<li><a href=" "><i class="fa fa-angle-double-right"></i>About</a></li>
						<li><a href=" "><i class="fa fa-angle-double-right"></i>FAQ</a></li>
						<li><a href=" "><i class="fa fa-angle-double-right"></i>Get Started</a></li>
						<li><a href="https://www.fiverr.com/share/qb8D02"><i class="fa fa-angle-double-right"></i>Videos</a></li>
					</ul>
				</div>
				<div class="col-xs-12 col-sm-4 col-md-4">
					<h5>Quick links</h5>
					<ul class="list-unstyled quick-links">
						<li><a href=" "><i class="fa fa-angle-double-right"></i>Home</a></li>
						<li><a href=" "><i class="fa fa-angle-double-right"></i>About</a></li>
						<li><a href=" "><i class="fa fa-angle-double-right"></i>FAQ</a></li>
						<li><a href=" "><i class="fa fa-angle-double-right"></i>Get Started</a></li>
						<li><a href="https://www.fiverr.com/share/qb8D02"><i class="fa fa-angle-double-right"></i>Videos</a></li>
					</ul>
				</div>
				<div class="col-xs-12 col-sm-4 col-md-4">
					<h5>Quick links</h5>
					<ul class="list-unstyled quick-links">
						<li><a href=""><i class="fa fa-angle-double-right"></i>Home</a></li>
						<li><a href=""><i class="fa fa-angle-double-right"></i>About</a></li>
						<li><a href=""><i class="fa fa-angle-double-right"></i>FAQ</a></li>
						<li><a href=""><i class="fa fa-angle-double-right"></i>Get Started</a></li>
						<li><a href="https://wwwe.sunlimetech.com" title="Design and developed by"><i class="fa fa-angle-double-right"></i>Imprint</a></li>
					</ul>
				</div>
			</div>
			<div class="row">
				<div class="col-xs-12 col-sm-12 col-md-12 mt-2 mt-sm-5">
					<ul class="list-unstyled list-inline social text-center">
						<li class="list-inline-item"><a href=""><i class="fa fa-facebook"></i></a></li>
						<li class="list-inline-item"><a href=""><i class="fa fa-twitter"></i></a></li>
						<li class="list-inline-item"><a href=""><i class="fa fa-instagram"></i></a></li>
						<li class="list-inline-item"><a href=""><i class="fa fa-google-plus"></i></a></li>
						<li class="list-inline-item"><a href="" target="_blank"><i class="fa fa-envelope"></i></a></li>
					</ul>
				</div>
				<hr>
			</div>	
			<div class="row">
				<div class="col-xs-12 col-sm-12 col-md-12 mt-2 mt-sm-2 text-center text-white">
					<p><u><a href="https://www.nationaltransaction.com/">HINDUSTAN CARE </a> </p>
					<p class="h6">© All right Reversed.<a class="text-green ml-2" href="" target="_blank">Hindustan Care</a></p>
					<p><a href="developer.html">About developer</a></p>
				</div>
				<hr>
			</div>	
		</div>
	</section>
	
</body>
</html>
