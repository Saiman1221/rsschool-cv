<!DOCTYPE html>
<html>
<head>
	<title>My CV</title>
	<link rel="stylesheet" type="text/css" href="style/main.css">
	<link rel="preconnect" href="https://fonts.googleapis.com">
	<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
	<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500&display=swap" rel="stylesheet">
	<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Merriweather&display=swap" rel="stylesheet">
</head>
<body>
	<header class="header">
	</header>
	<section class="main">
		<div class="container">
			<div class="block">
				<a href="#" class="link_to_school">rsschool-cv</a>
			</div>
		</div>
		<div class="container">
			<div class="block">
				<h1 class="tittle_h1">Viacheslav Parubtsev</h1>
				<h3 class="tittle_h3">
					Man 18 y.o., 19 august 2003 
				</h3>
				<h3 class="tittle_h3">
					Junior Front-End Developer 
				</h3>
			</div>
			<div class="block">
				<h2 class="tittle_h2">Skills:</h2>
				<ul class="skills">
					<li class="skills_li"><p class="text">- HTML5</p></li>
					<li class="skills_li"><p class="text">- CSS3</p></li>
					<li class="skills_li"><p class="text">- JavaScript</p></li>
					<li class="skills_li"><p class="text">- Bootstrap</p></li>
					<li class="skills_li"><p class="text">- REACT.JS.</p></li>
					<li class="skills_li"><p class="text">- Work with Figma & Photoshop…</p></li>
				</ul>
			</div>
			<div class="block">
				<h2 class="tittle_h2">Education:</h2>
				<p class="text">Belarusian State University of Informatics and Radioelectronics: Faculty of Information Technologies and Management, Information Technologies and Management in Technical Systems
				</p>
			</div>
			<div class="block">
				<h2 class="tittle_h2">About me:</h2>
				<p class="text">Hi, I come from the city of Zhodino, Minsk region. I am a 2nd-year student of the Belarusian State University of Informatics and Radioelectronics. I am developing in the field of web technologies, namely Front-End development, because I like to work with code and logic, as well as immediately see the result of my work. In the future, I plan to work as a Fullstack developer. I am ready to work like hell and give myself completely to my studies and work
				</p>
			</div>
			<div class="block">
				<div class="block_code">
					<pre class="code">function myFunction() {
	var input, filter, ul, li, a, i, display;
	input = document.getElementById("mySearch");
	filter = input.value.toUpperCase();
	ul = document.getElementById("myMenu");
	li = ul.getElementsByClassName("li");
	for (i = 0; i < li.length; i++) {
		a = li[i].getElementsByClassName("a")[0];
		if (a.innerHTML.toUpperCase().indexOf(filter) > -1) {
			li[i].style.display = "";
		} else {
			li[i].style.display = "none";
		}
	}
}</pre>
				</div>
			</div>
			<div class="block">
				<h2 class="tittle_h2">Languages:</h2>
				<ul class="languages">
					<li class="languages_li"><p class="text">Russian: Native</p></li>
					<li class="languages_li"><p class="text">English: pre-intermidiate(A2)</p></li>
				</ul>
			</div>
			<div class="block">
				<h2 class="tittle_h2">Contacts:</h2>
				<ul class="contacts">
					<li class="contacts_li"><p class="text">Phone: +375 (33) 636-12-27</p></li>
					<li class="contacts_li"><p class="text">E-mail: slavaparybcev2003@gmail.com</p></li>
					<li class="contacts_li"><p class="text">Instagram: slava.parubcev</p></li>
					<li class="contacts_li"><p class="text">Telegram: @viacheslav_2003  <span class="text_spec"></p></li>
					<li class="contacts_li"><p class="text">Discord: Saiman(@Saiman1221)#5894</p></li>

				</ul>
			</div>
		</div>
	</section>
	<footer class="footer">
		<div class="container">
			
		</div>
	</footer>
</body>
</html>
