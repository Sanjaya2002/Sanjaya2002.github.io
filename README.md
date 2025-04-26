<html lang="en">

	<head>
	 <title>personal portfolio</title>
	 <meta charset="utf-8">
	 <meta name="viewport" content="width=device-width, initial-scale=1.0">
	 <style>
	 body {margin:0;}
		* {
			box-sizing: border-box;
		}
		.topnav{
		   background-color:#3cacd7;
		   overflow:hidden;
		   position:fixed;
		   width:100%;
		   top:0;
		   z-index:5;
		}
		.topnav a{
		   float:right;
		   display:block;
		   color:#f2f2f2;
		   text-align:center;
		   padding:14px 16px;
		   text-decoration:none;
		   font-family:Helvetic,sans-serif;
   		}
	
		.topnav a:hover{
		   background-color:#ddd;
		   color:black;
		}
		
		.content{
		   background-image:url("sky-mvehfqz6w2ges2dj.jpg");
		   
		   font-family:Arial Black,sans-serif;
		   padding:10px;
		   height:600px;
		   z-index:4;
		}
		
		.text1{
		   position:absolute;
		   top:250px;
		   left:250px;
		   color:#f8fafb;
		}
		.text2{
		   position:absolute;
		   top:240px;
		   left:250px;
		   color:#f8fafb;
		}
		.text3{
		   position:absolute;
		   top:350px;
		   font-size:80%;
		   left:250px;
		   color:#f8fafb;
		   font-family:Helvetic,sans-serif;
		}
		.new{
		   position:absolute;
		   top:150px;
		   left:900px;
		}
		
		
		
		.column{
		   float:left;	
		   width:33.33%;
		   padding:10px;
		   height:200px;
		}
		
		.column1{
		   float:left;	
		   width:50%;
		   padding:10px;
		   height:200px;
		}
		
		.row:after {
			content: "";
			display: table;
			clear: both;
		}
		
		.about{
			background-image:url("ss.jpg");
			height:500px;
			padding:10px;
			z-index:3;
			
		}
		
		.contact{;
			background-color:black;
			padding:10px;
			height:250px;
			z-index:1;
		}
		.Edu{;
			background-color:#0C243C;
			padding:10px;
			height:450px;
			z-index:2;
		}
		
		.contacttext{
			color:#C9D1D5;
			font-family:Helvetica,sans-serif;
			font-size:90%;
			text-align:center;
		}
		.mask1 {
			-webkit-mask-image: linear-gradient(black, transparent);
			mask-image: linear-gradient(black, transparent);
			position:absolute;
			left:60px;
		}

	 </style>
	
	</head>


	<body>
	 <div class="topnav">
	   <a href="#contactpage">Contact</a>
	   <a href="#education">Education</a>
	   <a href="#about">About</a>
	   <a href="#home">Home</a>
	 </div>
	 
	 <div class ="content" id="home">
	    <p class="text2">HELLO,</p>
	    <h1 class="text1">I am Sanjaya Weerakoon👋</h1>
		<img src="me.jpg" width="400px" class="new" style="border-radius:50%">
		<p class="text3">I am a university student.<br> I love do sports and travelling🏋️‍♂️✌️</p>
	 </div>
	 
	 <div class="about" id="about">
		<h1 style="font-family:Helvetica,sans-serif;font-style;color:white;">ABOUT ME</h1>
		<hr style="height:2px;color:white;">
		<div class="row">
			<div class="column1">
				
				<p style="font-family:Arial,sans-serif;color:#C9D1D5;padding:5px font-size:80%"><b>HELLO! I am Sanjaya Weerakoon,</b> I am a junior video creater and <br>software developer from Sri Lanka.I have rich experience about video creating<br> and software developing.I like to talk with you about your projects.</p>
				<div class="mask1">
					<img src="developer.jpg" height="250px" width="440px">
				</div>
			</div>
			<div class="column1">
				<p style="Color:#808080;position:absolute;left:900px;font-family:Helvetica,sans-serif;"><b>Age:</b><span style="position:absolute;left:300px;color:white;">22</p><br><br>
				<p style="Color:#808080;position:absolute;left:900px;font-family:Helvetica,sans-serif;"><b>Address:</b><span style="position:absolute;left:300px;color:white;">5/24,Katulanda,Dekatana</p><br><br>
				<p style="Color:#808080;position:absolute;left:900px;font-family:Helvetica,sans-serif;"><b>Country:</b><span style="position:absolute;left:300px;color:white;">SriLanka</p>
			</div>
		</div>
	 </div>
	<div class="Edu" id="education">
	<h1 style="color:#40e0d0;font-family:Helvetica,sans-serif;font-style;">Education</h1><hr>
	 <div class="row">
		<div class="column">
			<p style="color:#40e0d0; font-family:Helvetic,sans-serif">Primary Education:</p>
			<p style="color:#C9D1D5; font-family:Helvetic,sans-serif; font-size:80%; position:absolute; left:40px;">•Dekatana Primary School</p>
		</div>
		<div class="column">
			<p style="color:#40e0d0; font-family:Helvetic,sans-serif">Secondary Education:</p>
			<p style="color:#C9D1D5; font-family:Helvetic,sans-serif; font-size:80%; position:absolute; left:540px;">•Ananda College, Colomo 10<br><br>•Got "A" passes for all subjects in Ordinary Level Examination<br><br>•Got 1.611 Zscore for Advanced level Examination</p>
			<img src ="usj.jpg" width="100px" style="border-radius:50%; position:relative; top:150px; left:100px">
		</div>
		<div class="column">
			<p style="color:#40e0d0; font-family:Helvetic,sans-serif">Higher Studies:</p>
			<p style="color:#C9D1D5; font-family:Helvetic,sans-serif; font-size:80%; position:absolute; left:1040px;">•University Of Sri Jayawardenepura(Undergraduate)</p>
		</div>
	 </div>
	</div>
	 <div class="contact" id="contactpage">
		<h1 style="color:#C9D1D5;font-family:Helvetica,sans-serif;">CONTACT</h1>
		<hr>
		<p class="contacttext">070-2119289</p>
		<p class="contacttext">sanjayaanandacollege@gmail.com</p><hr>
		<img src ="wp.jpg" width="30px" style="border-radius:50%">
		<img src ="gmail.jpg" width="40px" height="30px" style="position:absolute;left:60px">
	 </div>
	 
	 </body>
</html>
