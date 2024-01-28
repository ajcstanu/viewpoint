# viewpoint

<html lang="en">
<head>


<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>How to create a website using HTML and CSS</title>
<link rel="stylesheet" href="css/style.css">
</head>
<body>

<header>
<nav>
<ul>
<li><a href="#intro">Home</a></li>
<li><a href="#about">About</a></li>
<li><a href="#contact">Contact</a></li>
</ul>
</nav>
</header>
<main>
<section id="intro">
<div class="Container">
<img src="C:\Users\HP\OneDrive\Pictures\viewpoint\me.jpg" 
width="400" 
height="500" />
<!--<img src="C:\Users\HP\OneDrive\Pictures\viewpoint\me.jpg "alt="display picture ">-->
<h2>My name is Tanisha</h2>
</div> 
</section>

<section id="about">
<div class="container">
<h1><u>About Me</u></h1><br>
<p><h2>I am a computer science student</h2></p>
<ul>
<li>Btech Student </li>
<li>Software Engineer</li>

</ul>
</div>
</section>

<section id="contact">
<div class="container">
<h1><u>Contact me</u></h1><br>
<p><h2>Kolar road Bhopal</h2></p>
<ul>
<li>Email ID</li><p>tanishag821@gmail.com</p>
<li>LinkedIn ID</li><p>www.linkedin.com/in/tanishagupta-g</p>
</ul>
</div>
</section>

</main>
<footer>
<p>© tanishagupta02226@gmail.com</p>
</footer>
</body>
</html>
 56 changes: 56 additions & 0 deletions56  
viewpointcss.css
@@ -0,0 +1,56 @@
*{
padding: 0;
margin: 0;
}

header{
height: 45px;
}
header nav ul{
display: flex;
margin-left: 70%;
list-style: none;
}

header nav ul li{
padding-left: 10%;
}

header a{
text-decoration: none;
color: brown;

}

section{
height: 100vh;
border: 1px solid grey;
display: flex;
justify-content: center;
align-items: center;
}




.Container img{
height: 300px;
border-radius: 50%;
}

.Container h2{
margin-top: 2%;
font-size: 3em;
font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
}
.Container p, ul{
margin-top: 2%;
font-size: 1.5rem;
}

footer {
line-height: 40px;
display: flex;
justify-content: center;
font-size: 1rem;
}
