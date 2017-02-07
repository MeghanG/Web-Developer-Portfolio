<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8"/>
	<meta name="author" content="Meghan Grossman"/>
	<meta name="keywords" content="Remote Web Developer, Web Developer"/>
	<meta name="description" content="Welcome to my Web Developer Portfolio! Learn who I am and what I
	do."/>
	<title>Meghan Grossman: Remote Web Developer</title>
	<link rel="stylesheet" type="text/css" href="MeghanGrossman.css">
	<link href="https://fonts.googleapis.com/css?family=Arima+Madurai" rel="stylesheet">
	<link href="https://fonts.googleapis.com/css?family=Calligraffitti" rel="stylesheet">
	<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
	<script>
		$(function(){
			$("h1").fadeIn(3000);
			});
	</script>
	
</head>
<body>
	<header>
		<img src="Pictures/MGLogo.png" id="MGLogo" alt="MGLogo"/>
		<h5 class= "h5" id="animation">Meghan Grossman</h5>
			<nav>
				<ul>
					<li><a href="#home">Home</a></li>
					<li><a href="#education">Education</a></li>
					<li><a href="#skills">Skills</a></li>
					<li><a href="#projects">Projects</a></li>
					<li><a href="#aboutme">About Me</a></li>
					<li><a href="#contact">Contact</a></li>
				</ul>
			</nav>
	</header>
	<main>
		<h1 class="showfade" style="display:none;" id="home">Welcome!</h1>
		<article>
			<h3 id="education">Education</h3>
			<p>American Public University<br/>
			Associate's Degree in Web Publishing<br/>
			Graduation Date: April 4, 2017</p>
		</article>
		<section>
			<h3 id="skills">Skills</h3>
			<p>HTML, CSS, JavaScript, Web Analytics</p>
			<p>I have been strengthening my Web Developer skills for the past few years. Recently, 
			I enrolled in the Associate's program at the American Public University. I felt that 
			there was a gap in the theory of coding that I was learning through online boot camps. 
			I am pursuing a career as a remote Web Developer. I absolutely love coding with 
			HTML and CSS. I enjoy the challenge of creating a Website and I can use my artistic 
			mind to develop Websites with unique characteristics.</p>
		</section>
		<article>
			<h3 id="projects">Projects</h3>
				<p>Here are three Websites that I have built from scratch. Hunting Inspirations is
				an e-commerce shop for customized footwear. The Art of Fly Fishing shares my love,
				addiction and knowledge for fly fishing. The Web Developer Final Project is a Website
				that I created that includes the current responsibilities of a Web Developer and the
				career outlook.</p>

				<a href="HuntingInspirations/HuntingInspirations.html">
				<img src="Pictures/DolceHeels.jpg" alt="Camo Dolce Heels" id="DolceHeels"/></a>
				<h2>Hunting Inspirations</h2>
			
				<a href="TheArtofFlyFishing/TheArtofFlyFishing.html">
				<img src="Pictures/troutandrod.jpg" alt="Trout and Fly Rod" id="troutandrod" style= "width:150px; height:100px;"/></a>
				<h2>The Art of Fly Fishing</h2>
			
				<a href="WebDeveloperFinalProject/GrossmanMeghanFinalProject.html"> 
				<img src="Pictures/programmer.png" alt="Programmer" id="programmer" style= "width:150px; height:100px;"/></a>
				<h2>Web Developer Final Project</h2>
		</article>
		<article>
			<h3 id="aboutme">About Me</h3>
			<p>I'm an outdoor enthusiast! I occupy my time hunting, fishing, and all of that is
			wrapped around my family. I grew up hunting waterfowl, small game and large game.
			Now due to time restraints, I mainly focus my time afield on elk, deer, bear, and
			turkey. I love the adventure of elk hunting the most. I've drove to Craig, Colorado 
			for the past two years hunting cow elk. It is worth the long drive! During the spring 
			and summer, I head for the water with my fly rod and my daughter in tow. I've been fly 
			fishing and fly tying for over twenty years. I love fishing small streams in North 
			Central Pennsylvania for Native trout. When I'm not hunting or fishing, I'm spending
			time with my husband, daughter, and our pit bull, Trigger! </p>
		</article>
		<div class="aboutme" align="center">
			<img class="mySlides" src="Pictures/archery.jpg">
			<img class="mySlides" src="Pictures/treestand.jpg">
			<img class="mySlides" src="Pictures/gobbler.jpg">
			<img class="mySlides" src="Pictures/buck.jpg">
			<img class="mySlides" src="Pictures/bowseason.jpg">
			<img class="mySlides" src="Pictures/girls.jpg">
			<img class="mySlides" src="Pictures/Colorado.jpg">
			
			<a class="btn-floating-left" onclick="plusDivs(-1)">&#10094;
			</a>
			<a class="btn-floating-right" onclick="plusDivs(1)">&#10095;
			</a>
			<script>
				var slideIndex = 1;
				showDivs(slideIndex);

				function plusDivs(n) {
					showDivs(slideIndex += n);
				}

				function showDivs(n) {
					var i;
					var x = document.getElementsByClassName("mySlides");
					if (n > x.length) {slideIndex = 1}    
					if (n < 1) {slideIndex = x.length}
				for (i = 0; i < x.length; i++) {
					x[i].style.display = "none";  
				}
				x[slideIndex-1].style.display = "block";  
				}
			</script>
		</div>
		<article>
			<h3 id="contact">Let's Chat</h3>
				<p>I would enjoy talking with you about the skills, knowledge and characteristics that 
				I can bring to your company. It would be a great opportunity to put our heads together 
				and plan something great! I am excited about future opportunities to create Websites. 
				There are great technologies out there that need to be released in their full 
				potential. I can help in their release to reach their full potential to exceed your 
				company goals. Let's chat!</p>
				<p>My e-mail address is mnmboonies@gmail.com and I will promptly conact you in return!</p>
		</article>
	</main>
	<footer>
		<a href="GrossmanMeghan.html">
		<img src="Pictures/MGLogo.png" id="MLogo" alt="MGLogo"/></a>
		&copy; 2017 Meghan Grossman <br> mnmboonies@gmail.com
	</footer>
</body>
</html>
