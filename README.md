# -bigbrainltnl <!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Big Brain LTNL Moving Services</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    line-height:1.6;
    color:#333;
}

header{
    background:#0b1f3a;
    color:white;
    padding:20px 5%;
    position:sticky;
    top:0;
}

nav{
    display:flex;
    justify-content:space-between;
    align-items:center;
    flex-wrap:wrap;
}

.logo{
    font-size:28px;
    font-weight:bold;
    color:#ffd700;
}

nav ul{
    list-style:none;
    display:flex;
    gap:20px;
}

nav a{
    color:white;
    text-decoration:none;
    font-weight:bold;
}

.hero{
    background:linear-gradient(rgba(0,0,0,.5),rgba(0,0,0,.5)),
    url('https://images.unsplash.com/photo-1600518464441-9154a4dea21b?auto=format&fit=crop&w=1400&q=80');
    background-size:cover;
    background-position:center;
    color:white;
    text-align:center;
    padding:120px 20px;
}

.hero h1{
    font-size:3rem;
    margin-bottom:15px;
}

.hero p{
    font-size:1.2rem;
    margin-bottom:25px;
}

.btn{
    display:inline-block;
    background:#ffd700;
    color:#000;
    padding:12px 24px;
    text-decoration:none;
    border-radius:5px;
    font-weight:bold;
}

section{
    padding:70px 10%;
}

.section-title{
    text-align:center;
    margin-bottom:40px;
    color:#0b1f3a;
}

.services{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.card{
    background:#f8f8f8;
    padding:25px;
    border-radius:10px;
    box-shadow:0 2px 10px rgba(0,0,0,.1);
}

.card h3{
    margin-bottom:10px;
    color:#0b1f3a;
}

.about{
    background:#f4f4f4;
}

.why-us{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
    gap:20px;
    text-align:center;
}

.feature{
    padding:20px;
    background:white;
    border-radius:10px;
}

.quote-form{
    max-width:700px;
    margin:auto;
}

.quote-form input,
.quote-form textarea{
    width:100%;
    padding:12px;
    margin-bottom:15px;
    border:1px solid #ccc;
    border-radius:5px;
}

.quote-form button{
    background:#0b1f3a;
    color:white;
    border:none;
    padding:15px 25px;
    border-radius:5px;
    cursor:pointer;
}

.contact{
    background:#0b1f3a;
    color:white;
    text-align:center;
}

footer{
    background:#061225;
    color:white;
    text-align:center;
    padding:20px;
}

@media(max-width:768px){
    nav{
        flex-direction:column;
        gap:15px;
    }

    nav ul{
        flex-wrap:wrap;
        justify-content:center;
    }

    .hero h1{
        font-size:2rem;
    }
}
</style>
</head>

<body>

<header>
<nav>
<div class="logo">Big Brain LTNL</div>

<ul>
<li><a href="#home">Home</a></li>
<li><a href="#services">Services</a></li>
<li><a href="#about">About</a></li>
<li><a href="#quote">Quote</a></li>
<li><a href="#contact">Contact</a></li>
</ul>
</nav>
</header>

<section class="hero" id="home">
<h1>Big Brain LTNL Moving Services</h1>
<p>Moving Smart. Moving Strong.</p>
<a href="#quote" class="btn">Get Free Quote</a>
</section>

<section id="services">
<h2 class="section-title">Our Moving Services</h2>

<div class="services">

<div class="card">
<h3>Residential Moving</h3>
<p>Professional home and apartment moving services with care and efficiency.</p>
</div>

<div class="card">
<h3>Commercial Moving</h3>
<p>Office and business relocation with minimal downtime.</p>
</div>

<div class="card">
<h3>Packing & Unpacking</h3>
<p>We protect and organize your belongings from start to finish.</p>
</div>

<div class="card">
<h3>Loading & Unloading</h3>
<p>Need help with a rental truck? Our crew can handle the heavy lifting.</p>
</div>

<div class="card">
<h3>Furniture Assembly</h3>
<p>Disassembly and reassembly of furniture for hassle-free moves.</p>
</div>

<div class="card">
<h3>Long Distance Moves</h3>
<p>Reliable moving services throughout New Jersey and beyond.</p>
</div>

</div>
</section>

<section class="about" id="about">
<h2 class="section-title">About Us</h2>

<p style="text-align:center;max-width:800px;margin:auto;">
Big Brain LTNL Moving Services is dedicated to providing dependable,
affordable, and stress-free moving solutions. Our trained team treats
every move with professionalism and attention to detail, helping families
and businesses relocate safely and efficiently.
</p>
</section>

<section>
<h2 class="section-title">Why Choose Us?</h2>

<div class="why-us">

<div class="feature">
<h3>Affordable Pricing</h3>
<p>Competitive rates with no hidden fees.</p>
</div>

<div class="feature">
<h3>Reliable Team</h3>
<p>Professional movers you can trust.</p>
</div>

<div class="feature">
<h3>Fast Service</h3>
<p>On-time arrivals and efficient moves.</p>
</div>

<div class="feature">
<h3>Customer Focused</h3>
<p>Your satisfaction is our priority.</p>
</div>

</div>
</section>

<section id="quote">
<h2 class="section-title">Request a Free Quote</h2>

<form class="quote-form">
<input type="text" placeholder="Full Name" required>
<input type="tel" placeholder="Phone Number" required>
<input type="email" placeholder="Email Address" required>
<input type="date">
<input type="text" placeholder="Pickup Location">
<input type="text" placeholder="Destination">
<textarea rows="5" placeholder="Tell us about your move"></textarea>

<button type="submit">Request Quote</button>
</form>
</section>

<section class="contact" id="contact">
<h2>Contact Big Brain LTNL</h2>

<br>

<p>📞 (555) 123-4567</p>
<p>📧 info@bigbrainltnl.com</p>
<p>📍 New Jersey</p>

<br>

<p>Monday - Friday: 8 AM - 7 PM</p>
<p>Saturday: 9 AM - 5 PM</p>
<p>Sunday: By Appointment</p>
</section>

<footer>
<p>© 2026 Big Brain LTNL Moving Services. All Rights Reserved.</p>
</footer>

</body>
</html>