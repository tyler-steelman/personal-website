<!doctype html>
<html>
<head>
<meta charset="UTF-8">
<title>Tyler S. Steelman</title>
<meta name="description" content="Tyler Steelman's personal website.">
<link rel="stylesheet" href="styles1.css">
		<style>
	section#hero{
		height: 300px;
	}
	section#hero > div {
		width: 100%;
		height: 100%;
		position: absolute;
		background-size: cover;
		transition: opacity .75s ease;
	}
	#line{
		background-image: url("images/line.jpg");
		opacity: 1;
	}
	#noline{
		background-image: transparent;
		opacity: 0;
	}
	#me{
		heigh: 30px;
		width: 10px;
		background-image: url("images/logo.jpg");
		background-size: cover;
	}

</style>
</head>

<body>
	<header>
		<!--<img class="me" src="images/logo.jpg" alt="my_pic" height="100px">-->
		<nav>
			<ul>
				<li><strong>HOME</strong></li>
				<li><a href=files/cv.pdf target="_blank">CV</a></li>
				<li><a href=dissertation.html>DISSERTATION</a></li>
			  <li><a href=research.html>RESEARCH</a></li>
				<li><a href=teaching.html>TEACHING</a></li>
				<li><a href=contact.html>CONTACT</a></li>
			</ul>
		</nav>		
	</header>
	
	
	
	<main>
		<div class="hero-box1">
			<h1>Tyler S. Steelman</h1>
			<h2>Doctoral Candidate</h2>
			<h2><a href="https://twitter.com/tyler_steelman?ref_src=twsrc%5Etfw" class="twitter-follow-button" data-show-count="false">Follow @tyler_steelman</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script></h2>
		</div>
		
		<div class="hero-box4";
		</div>
		
	  <div class="whitespace">
		</div>
		
		<section id="hero">
<!--		  <div id="line"></div>
          <div id="noline"></div>-->
			<p class="maintext"> I am currently a doctoral candidate (ABD) at The University of North Carolina at Chapel Hill. I hold an M.A. in Political Science from Appalachian State University as well as a B.A. in Music Performance from High Point University.  <br>
         	<br>
			My dissertation research focuses on surrogate representation--a form of political representation where Americans and their representatives do not share a legal, territorial district. Surrogate representation theorizes that Americans seek out representatives from across the United States with whom they share an identity, a interest in specific policies, or both. My dissertation demonstrates that surrogate representation is extremely prevalent in American politics and is utilized by both Democrats and Republicans who feel underrepresented in their home districts. <br>
			<br>
			Using the navigation options above, you can learn more about my disseration research, explore my other research interests, view teaching documents, and contact me for more information.</p>
		</div>
		
	</main>
	
	<br>
	<br>
	
<!--<script>
		const heroElem = document.querySelector('#hero');
		const lineElem = document.querySelector('#line');
		const nolineElem = document.querySelector('#noline');
		const scrollAmount = -300;
		window.addEventListener('scroll', (event) => {
			const { top } = heroElem.getBoundingClientRect();
			const heroInView = top - window.innerHeight < scrollAmount;
			lineElem.style.opacity = heroInView ? 0 : 1;
			nolineElem.style.opacity = heroInView ? 1 : 0;
		});
	</script>-->
	
	
	<br>
	<br>
	<br>
	
	<footer class="footer">
		<p>Copyright © 2020 Tyler S. Steelman</p>
	</footer>
	

</body>
</html>
