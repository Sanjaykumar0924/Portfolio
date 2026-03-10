# Ex01 Portfolio
## Date: 10.3.26
## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the TML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
html
```
<!DOCTYPE html>
<html lang="en">
<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Sanjay Kumar Portfolio</title>

<link rel="stylesheet" href="port.css">

</head>

<body>


<header>

<nav>

<h2 class="logo">Sanjay Kumar</h2>

<ul>
<li><a href="#home">Home</a></li>
<li><a href="#about">About</a></li>
<li><a href="#skills">Skills</a></li>
<li><a href="#projects">Projects</a></li>
<li><a href="#contact">Contact</a></li>
</ul>

</nav>

</header>



<section id="home" class="home">

<h1>Hello I'm <span>Sanjay Kumar</span></h1>

<h3>Software Developer | Innovator</h3>

<p>
Passionate about building automation tools, intelligent systems,
and innovative technology solutions that solve real world problems.
</p>

<a href="#contact" class="btn">Contact Me</a>

</section>



<section id="about" class="about">

<h2>About Me</h2>

<p>
My name is Sanjay Kumar. I enjoy building smart applications,
automation tools using Python and Selenium,
and innovative technology solutions.
I believe technology should help humans become more productive
without making them lazy.
</p>

</section>



<section id="skills" class="skills">

<h2>Skills</h2>

<div class="skill-container">

<div class="skill">HTML</div>
<div class="skill">CSS</div>
<div class="skill">JavaScript</div>
<div class="skill">Python</div>
<div class="skill">Java</div>
<div class="skill">Selenium Automation</div>
<div class="skill">Computer Vision</div>
<div class="skill">Networking</div>

</div>

</section>



<section id="projects" class="projects">

<h2>Projects</h2>

<div class="project-container">

<div class="project">
<h3>AI Quality Automation</h3>
<p>
Developed an AI based visual inspection system for detecting
product defects and improving manufacturing quality checks.
</p>
</div>


<div class="project">
<h3>Bus Cache Tracking App</h3>
<p>
Designed a smart bus tracking system to improve public transport
efficiency and route monitoring.
</p>
</div>


<div class="project">
<h3>Seack Travel Planner</h3>
<p>
A travel planning application that suggests shortest routes,
rest stops, restaurants and petrol stations.
</p>
</div>

</div>

</section>



<section id="contact" class="contact">

<h2>Contact</h2>

<p>Email : sanjaykumar@email.com</p>
<p>Phone : +91 9876543210</p>
<p>Location : Chennai, India</p>
<p>GitHub : github.com/sanjaykumar</p>

</section>



<footer>

<p>© 2026 Sanjay Kumar Portfolio</p>

</footer>


</body>
</html>
```

css
```
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial;
scroll-behavior:smooth;
}

body{
background:#f4f4f4;
}

header{
background:#111;
padding:20px;
position:fixed;
width:100%;
top:0;
}

nav{
display:flex;
justify-content:space-between;
align-items:center;
width:90%;
margin:auto;
}

.logo{
color:white;
font-size:24px;
font-weight:bold;
}

nav ul{
display:flex;
list-style:none;
}

nav ul li{
margin-left:25px;
}

nav ul li a{
text-decoration:none;
color:white;
font-size:16px;
}

nav ul li a:hover{
color:#00d9ff;
}

section{
padding:100px 10%;
text-align:center;
}

.home{
height:100vh;
background:linear-gradient(to right,#141e30,#243b55);
color:white;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
}

.home h1{
font-size:50px;
}

.home span{
color:#00d9ff;
}

.home p{
margin-top:15px;
max-width:600px;
}

.btn{
display:inline-block;
margin-top:25px;
padding:12px 25px;
background:#00d9ff;
color:white;
text-decoration:none;
border-radius:5px;
}

.about{
background:white;
}

.skills{
background:#f0f0f0;
}

.skill-container{
display:flex;
flex-wrap:wrap;
justify-content:center;
margin-top:30px;
}

.skill{
background:#111;
color:white;
padding:12px 20px;
margin:10px;
border-radius:6px;
}

.projects{
background:white;
}

.project-container{
display:flex;
flex-wrap:wrap;
justify-content:center;
margin-top:30px;
}

.project{
background:#f4f4f4;
width:280px;
margin:15px;
padding:20px;
border-radius:6px;
box-shadow:0 3px 10px rgba(0,0,0,0.1);
}

.contact{
background:#f0f0f0;
}

.contact p{
margin:10px;
font-size:18px;
}

footer{
background:#111;
color:white;
padding:20px;
text-align:center;
}
```
## OUTPUT
<img width="1846" height="1078" alt="image" src="https://github.com/user-attachments/assets/d7c17d44-1400-4eed-9941-40428b5a35b2" />
<img width="1846" height="1083" alt="image" src="https://github.com/user-attachments/assets/0f0a1eb7-db80-4042-a72a-1dcefa01096b" />
<img width="1883" height="1083" alt="image" src="https://github.com/user-attachments/assets/45cea165-1850-42fe-96f9-6c980950c75b" />


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
