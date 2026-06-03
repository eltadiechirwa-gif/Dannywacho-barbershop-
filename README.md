<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>DannyWacho Barbershop</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
scroll-behavior:smooth;
}

body{
background:#111;
color:white;
}

header{
background:#000;
padding:15px 5%;
display:flex;
justify-content:space-between;
align-items:center;
position:sticky;
top:0;
z-index:1000;
border-bottom:2px solid gold;
}

.logo{
font-size:28px;
font-weight:bold;
color:gold;
}

nav a{
color:white;
text-decoration:none;
margin-left:20px;
}

nav a:hover{
color:gold;
}

.hero{
height:90vh;
background:url('https://images.unsplash.com/photo-1622286342621-4bd786c2447c?w=1200') center/cover;
display:flex;
justify-content:center;
align-items:center;
text-align:center;
}

.hero-content{
background:rgba(0,0,0,.75);
padding:40px;
border-radius:15px;
}

.hero h1{
font-size:60px;
color:gold;
}

.hero p{
margin:15px 0;
font-size:20px;
}

.btn{
display:inline-block;
padding:12px 25px;
background:gold;
color:black;
text-decoration:none;
font-weight:bold;
border-radius:5px;
}

section{
padding:80px 10%;
}

.section-title{
text-align:center;
font-size:40px;
margin-bottom:40px;
color:gold;
}

.about{
display:grid;
grid-template-columns:1fr 1fr;
gap:30px;
align-items:center;
}

.about img{
width:100%;
border-radius:10px;
}

.services{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.card{
background:#1e1e1e;
padding:25px;
border-radius:10px;
text-align:center;
transition:.3s;
}

.card:hover{
transform:translateY(-8px);
}

.card h3{
color:gold;
margin-bottom:10px;
}

.gallery{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.gallery img{
width:100%;
height:250px;
object-fit:cover;
border-radius:10px;
}

.booking{
max-width:700px;
margin:auto;
background:#1b1b1b;
padding:30px;
border-radius:10px;
}

.booking input,
.booking select,
.booking textarea{
width:100%;
padding:15px;
margin:10px 0;
border:none;
border-radius:5px;
}

.booking button{
width:100%;
padding:15px;
background:gold;
border:none;
font-weight:bold;
cursor:pointer;
}

#message{
margin-top:15px;
color:lightgreen;
font-weight:bold;
}

.contact{
text-align:center;
}

iframe{
width:100%;
height:450px;
border:none;
border-radius:10px;
}

footer{
background:black;
padding:25px;
text-align:center;
margin-top:30px;
border-top:1px solid gold;
}

.chatbot{
position:fixed;
bottom:20px;
right:20px;
width:280px;
background:#1b1b1b;
border:1px solid gold;
padding:15px;
border-radius:10px;
}

.chatbot input{
width:100%;
padding:10px;
margin-top:10px;
}

@media(max-width:768px){

header{
flex-direction:column;
}

nav{
margin-top:10px;
}

.about{
grid-template-columns:1fr;
}

.hero h1{
font-size:40px;
}
}
</style>
</head>

<body>

<header>
<div class="logo">💈 DannyWacho</div>

<nav>
<a href="#home">Home</a>
<a href="#about">About</a>
<a href="#services">Services</a>
<a href="#gallery">Gallery</a>
<a href="#booking">Booking</a>
<a href="#location">Location</a>
<a href="#contact">Contact</a>
</nav>
</header>

<section class="hero" id="home">
<div class="hero-content">
<h1>DannyWacho Barbershop</h1>
<p>Premium Cuts • Fresh Fades • Professional Grooming</p>
<a href="#booking" class="btn">Book Appointment</a>
</div>
</section>

<section id="about">
<h2 class="section-title">About Us</h2>

<div class="about">
<img src="https://images.unsplash.com/photo-1517832606299-7ae9b720a186?w=800">

<div>
<h3>Welcome to DannyWacho</h3>
<br>
<p>
We deliver world-class grooming services with modern styles,
clean fades and professional barbering.
</p>
<br>
<p>
Whether you want a classic haircut, beard trim or premium VIP
treatment, our team is ready to give you the perfect look.
</p>
</div>
</div>
</section>

<section id="services">
<h2 class="section-title">Services</h2>

<div class="services">

<div class="card">
<h3>Haircut</h3>
<p>Modern and classic styles.</p>
</div>

<div class="card">
<h3>Skin Fade</h3>
<p>Sharp clean fades.</p>
</div>

<div class="card">
<h3>Beard Trim</h3>
<p>Professional grooming.</p>
</div>

<div class="card">
<h3>Kids Cuts</h3>
<p>Stylish cuts for children.</p>
</div>

<div class="card">
<h3>Hair Wash</h3>
<p>Refresh and rejuvenate.</p>
</div>

<div class="card">
<h3>VIP Package</h3>
<p>Luxury grooming experience.</p>
</div>

</div>
</section>

<section id="gallery">
<h2 class="section-title">Gallery</h2>

<div class="gallery">

<img src="https://images.unsplash.com/photo-1503951914875-452162b0f3f1?w=800">
<img src="https://images.unsplash.com/photo-1512690459411-b0fd1c86b8a8?w=800">
<img src="https://images.unsplash.com/photo-1621605815971-fbc98d665033?w=800">
<img src="https://images.unsplash.com/photo-1521590832167-7bcbfaa6381f?w=800">

</div>
</section>

<section id="booking">
<h2 class="section-title">Book Appointment</h2>

<div class="booking">

<input id="name" placeholder="Full Name">
<input id="phone" placeholder="Phone Number">

<select id="service">
<option>Haircut</option>
<option>Skin Fade</option>
<option>Beard Trim</option>
<option>VIP Package</option>
</select>

<input id="date" type="date">

<textarea id="notes" rows="5" placeholder="Additional Notes"></textarea>

<button onclick="bookAppointment()">Book Now</button>

<div id="message"></div>

</div>
</section>

<section id="location">
<h2 class="section-title">Find Us</h2>

<iframe
src="https://maps.google.com/maps?q=Ngwere%20Complex,%20Shamva,%20Zimbabwe&t=&z=15&ie=UTF8&iwloc=&output=embed">
</iframe>
</section>

<section id="contact">
<h2 class="section-title">Contact Us</h2>

<div class="contact">
<h3>DannyWacho Barbershop</h3>
<br>
<p>📍 Ngwere Complex, Shamva, Zimbabwe</p>
<p>📞 +263 773 187 009</p>
<p>📧 davillephiri284@gmail.com</p>
<p>🕒 Monday - Sunday | 08:00 AM - 08:00 PM</p>
</div>
</section>

<footer>
<p>© 2026 DannyWacho Barbershop. All Rights Reserved.</p>
</footer>

<div class="chatbot">
<div id="chatreply">💈 Ask about haircuts, fades or prices.</div>
<input type="text" placeholder="Ask something..." onkeydown="chatBot(event)">
</div>

<script>

function bookAppointment(){

let name=document.getElementById("name").value;

document.getElementById("message").innerHTML=
"✅ Thank you "+name+
"! Your booking request has been received.";

}

function chatBot(e){

if(e.key==="Enter"){

let text=e.target.value.toLowerCase();
let reply="";

if(text.includes("fade")){
reply="🔥 Skin fades are one of our most popular styles.";
}
else if(text.includes("beard")){
reply="🧔 We offer professional beard trimming and shaping.";
}
else if(text.includes("price")){
reply="💈 Visit or call the shop for current pricing.";
}
else{
reply="💇 Welcome to DannyWacho Barbershop. We are ready to help.";
}

document.getElementById("chatreply").innerHTML=reply;
e.target.value="";
}
}

</script>

</body>
</html>
