<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ayush Kedar | Resume</title>

<style>
.profile-photo{
width:140px;
height:140px;
border-radius:50%;
border:5px solid white;
box-shadow:0 6px 15px rgba(0,0,0,0.3);
object-fit:cover;
margin-bottom:10px;
}
html{
scroll-behavior:smooth;
}

body{
font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
margin:0;
background:linear-gradient(135deg,#dfe9f3,#ffffff);
color:#333;
}

/* HEADER */

header{
background:linear-gradient(120deg,#2c3e50,#4ca1af);
color:white;
text-align:center;
padding:40px 20px;
box-shadow:0 4px 10px rgba(0,0,0,0.2);
}

header h1{
margin:0;
font-size:40px;
letter-spacing:2px;
}

header p{
font-size:18px;
opacity:0.9;
}

/* NAVBAR */

nav{
background:#34495e;
padding:12px;
text-align:center;
position:sticky;
top:0;
z-index:1000;
}

nav a{
color:white;
text-decoration:none;
margin:0 18px;
font-weight:bold;
font-size:16px;
transition:0.3s;
}

nav a:hover{
color:#f1c40f;
}

/* MAIN CONTAINER */

.container{
width:85%;
margin:auto;
padding:30px;
}

/* SECTION CARD */

section{
background:white;
margin-bottom:30px;
padding:25px;
border-radius:12px;
box-shadow:0 5px 15px rgba(0,0,0,0.1);
transition:0.3s;
}

section:hover{
transform:translateY(-5px);
box-shadow:0 8px 25px rgba(0,0,0,0.15);
}

h2{
border-left:5px solid #4ca1af;
padding-left:10px;
}

/* PROFILE IMAGE */

img{
border-radius:50%;
border:4px solid #4ca1af;
margin-top:10px;
}

/* SKILLS */

ul{
list-style-type:square;
line-height:1.8;
}

/* PROJECT CARDS */

article{
background:#f9f9f9;
padding:15px;
margin-top:10px;
border-radius:8px;
transition:0.3s;
}

article:hover{
background:#ecf0f1;
}

/* CONTACT LINKS */

a{
color:#2980b9;
}

a:hover{
color:#e67e22;
}

/* BUTTON */

.download-btn{
display:inline-block;
margin-top:10px;
padding:10px 18px;
background:#4ca1af;
color:white;
text-decoration:none;
border-radius:6px;
transition:0.3s;
}

.download-btn:hover{
background:#2c3e50;
}

/* FOOTER */

footer{
text-align:center;
padding:18px;
background:#2c3e50;
color:white;
margin-top:20px;
}

</style>
</head>

<body>

<header>
<h1>Ayush Kedar</h1>
<p>Web Developer</p>
</header>

<nav>
<a href="#about">About</a>
<a href="#skills">Skills</a>
<a href="#education">Education</a>
<a href="#projects">Projects</a>
<a href="#contact">Contact</a>
</nav>

<div class="container">

<section id="about">
<h2>About Me</h2>
<img src="profile.jpg" width="150">
<p>
Motivated web developer with experience in building responsive websites
using HTML, CSS, and JavaScript.
</p>

<a href="resume.pdf" class="download-btn">Download Resume</a>
</section>

<section id="skills">
<h2>Skills</h2>

<ul>
<li>HTML</li>
<li>CSS</li>
<li>JavaScript</li>
<li>Python</li>
<li>Responsive Web Design</li>
</ul>

</section>

<section id="education">
<h2>Education</h2>

<p><strong>Bachelor of Computer Science</strong></p>
<p>XYZ University | 2021 - 2024</p>

</section>

<section id="projects">

<h2>Projects</h2>

<article>
<h3>Portfolio Website</h3>
<p>Personal portfolio website showcasing projects and skills.</p>
</article>

<article>
<h3>Task Manager App</h3>
<p>A simple web app for managing daily tasks using JavaScript.</p>
</article>

</section>

<section id="contact">

<h2>Contact</h2>

<p>Email: <a href="mailto:ayushkedar@email.com">ayushkedar@email.com</a></p>
<p>Phone: <a href="tel:+911234567890">+91 12345 67890</a></p>

<p>
LinkedIn:
<a href="https://linkedin.com" target="_blank">
linkedin.com/ayushkedar
</a>
</p>

</section>

</div>

<footer>
<p>© 2026 Ayush Kedar | All Rights Reserved</p>
</footer>

</body>
</html>