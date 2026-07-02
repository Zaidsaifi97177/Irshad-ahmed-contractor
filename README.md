# Irshad-ahmed-contractor
This is website is for construction work and steel fabrication or interior works.
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Irshad Ahmed Contractor Ltd.</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
scroll-behavior:smooth;
}

body{
background:#f5f5f5;
color:#333;
}

header{
background:#111;
color:white;
padding:18px 8%;
display:flex;
justify-content:space-between;
align-items:center;
position:sticky;
top:0;
z-index:999;
}

header h2{
color:#FFD700;
}

nav a{
color:white;
text-decoration:none;
margin-left:25px;
font-weight:500;
}

nav a:hover{
color:#FFD700;
}

.hero{
height:90vh;
background:url('https://images.unsplash.com/photo-1504307651254-35680f356dfd?auto=format&fit=crop&w=1500&q=80');
background-size:cover;
background-position:center;
display:flex;
align-items:center;
justify-content:center;
text-align:center;
position:relative;
}

.hero::before{
content:"";
position:absolute;
left:0;
top:0;
width:100%;
height:100%;
background:rgba(0,0,0,.6);
}

.hero-content{
position:relative;
color:white;
max-width:800px;
padding:20px;
}

.hero h1{
font-size:55px;
margin-bottom:15px;
}

.hero p{
font-size:20px;
margin-bottom:30px;
}

.btn{
display:inline-block;
background:#FFD700;
padding:15px 35px;
text-decoration:none;
color:black;
font-weight:bold;
border-radius:30px;
}

section{
padding:80px 10%;
}

.section-title{
text-align:center;
font-size:38px;
margin-bottom:50px;
color:#111;
}

.about{
display:grid;
grid-template-columns:1fr 1fr;
gap:40px;
align-items:center;
}

.about img{
width:100%;
border-radius:15px;
}

.services{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
gap:30px;
}

.card{
background:white;
padding:25px;
border-radius:15px;
box-shadow:0 10px 20px rgba(0,0,0,.1);
text-align:center;
}

.card img{
width:100%;
height:220px;
object-fit:cover;
border-radius:10px;
margin-bottom:20px;
}

.gallery{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
gap:20px;
}

.gallery img{
width:100%;
height:250px;
object-fit:cover;
border-radius:10px;
}

.contact{
background:#111;
color:white;
text-align:center;
}

.contact h2{
margin-bottom:25px;
}

.phone{
font-size:22px;
margin:15px 0;
}

footer{
background:#000;
color:white;
text-align:center;
padding:20px;
}

@media(max-width:768px){

.hero h1{
font-size:38px;
}

.about{
grid-template-columns:1fr;
}

header{
flex-direction:column;
}

nav{
margin-top:15px;
}

}

</style>

</head>
<body>

<header>

<h2>Irshad Ahmed Contractor Ltd.</h2>

<nav>

<a href="#about">About</a>
<a href="#services">Services</a>
<a href="#gallery">Gallery</a>
<a href="#contact">Contact</a>

</nav>

</header>

<section class="hero">

<div class="hero-content">

<h1>Building Excellence with Quality & Trust</h1>

<p>
Professional Interior Works, Steel Fabrication & Construction Services.
Delivering durable, modern and high-quality projects across residential,
commercial and industrial sectors.
</p>

<a class="btn" href="#contact">Contact Us</a>

</div>

</section>

<section id="about">

<h2 class="section-title">About Our Company</h2>

<div class="about">

<img src="https://images.unsplash.com/photo-1505693416388-ac5ce068fe85?auto=format&fit=crop&w=1200&q=80">

<div>

<h2>Irshad Ahmed Contractor Ltd.</h2>

<br>

<p>

Irshad Ahmed Contractor Ltd. is a trusted name in the construction industry,
specializing in Interior Works, Steel Fabrication, Civil Construction,
Commercial Projects, Residential Buildings and Renovation Services.

<br><br>

Our experienced team is committed to delivering high-quality workmanship,
using modern techniques and premium materials to ensure every project
meets the highest standards.

<br><br>

Customer satisfaction, timely delivery and honest pricing have helped us
build long-term relationships with our clients.

</p>

</div>

</div>

</section>

<section id="services">

<h2 class="section-title">Our Services</h2>

<div class="services">

<div class="card">

<img src="https://images.unsplash.com/photo-1484154218962-a197022b5858?auto=format&fit=crop&w=1000&q=80">

<h3>Interior Works</h3>

<p>

Home Interiors, Office Interiors,
False Ceiling, Modular Kitchen,
Wood Work, Painting,
Flooring and Renovation.

</p>

</div>

<div class="card">

<img src="https://images.unsplash.com/photo-1517048676732-d65bc937f952?auto=format&fit=crop&w=1000&q=80">

<h3>Steel Fabrication</h3>

<p>

Industrial Fabrication,
Steel Structure,
Sheds,
Railings,
Gates,
Warehouse Fabrication,
MS & SS Work.

</p>

</div>

<div class="card">

<img src="https://images.unsplash.com/photo-1541888946425-d81bb19240f5?auto=format&fit=crop&w=1000&q=80">

<h3>Construction Work</h3>

<p>

Residential Construction,
Commercial Buildings,
Industrial Projects,
Civil Work,
Renovation,
Repair &
Turnkey Construction.

</p>

</div>

</div>

</section>

<section id="gallery">

<h2 class="section-title">Our Projects</h2>

<div class="gallery">

<img src="https://images.unsplash.com/photo-1511818966892-d7d671e672a2?auto=format&fit=crop&w=1000&q=80">

<img src="https://images.unsplash.com/photo-1489515217757-5fd1be406fef?auto=format&fit=crop&w=1000&q=80">

<img src="https://images.unsplash.com/photo-1523413651479-597eb2da0ad6?auto=format&fit=crop&w=1000&q=80">

<img src="https://images.unsplash.com/photo-1504307651254-35680f356dfd?auto=format&fit=crop&w=1000&q=80">

<img src="https://images.unsplash.com/photo-1494526585095-c41746248156?auto=format&fit=crop&w=1000&q=80">

<img src="https://images.unsplash.com/photo-1503387762-592deb58ef4e?auto=format&fit=crop&w=1000&q=80">

</div>

</section>

<section id="contact" class="contact">

<h2>Contact Us</h2>

<p>Let's build your dream project together.</p>

<div class="phone">📞 +91 8588077183</div>

<div class="phone">📞 +91 9717760814</div>

<br>

<a class="btn" href="tel:+918588077183">Call Now</a>

</section>

<footer>

© 2026 Irshad Ahmed Contractor Ltd. All Rights Reserved.

</footer>

</body>
</html>
