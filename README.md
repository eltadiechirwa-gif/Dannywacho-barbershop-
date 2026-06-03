# Dannywacho-barbershop-
A barbershop 
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
    font-family:Arial, sans-serif;
}

body{
    background:#111;
    color:white;
}

header{
    background:linear-gradient(135deg,#000,#333);
    padding:20px;
    position:sticky;
    top:0;
    z-index:1000;
}

nav{
    display:flex;
    justify-content:space-between;
    align-items:center;
}

.logo{
    font-size:28px;
    font-weight:bold;
    color:gold;
}

nav ul{
    display:flex;
    list-style:none;
}

nav ul li{
    margin-left:20px;
}

nav ul li a{
    text-decoration:none;
    color:white;
    transition:.3s;
}

nav ul li a:hover{
    color:gold;
}

.hero{
    height:90vh;
    background:url('https://images.unsplash.com/photo-1622286342621-4bd786c2447c?w=1200') center/cover;
    display:flex;
    align-items:center;
    justify-content:center;
    text-align:center;
}

.hero-content{
    background:rgba(0,0,0,.7);
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
    border-radius:5px;
    font-weight:bold;
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
    background:#222;
    padding:25px;
    border-radius:10px;
    text-align:center;
    transition:.3s;
}

.card:hover{
    transform:translateY(-10px);
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
    background:#1b1b1b;
    border-radius:15px;
    padding:40px;
}

form{
    display:flex;
    flex-direction:column;
}

input,select,textarea{
    padding:15px;
    margin:10px 0;
    border:none;
    border-radius:5px;
}

button{
    background:gold;
    color:black;
    border:none;
    padding:15px;
    font-weight:bold;
    cursor:pointer;
}

.contact{
    text-align:center;
}

footer{
    background:black;
    text-align:center;
    padding:25px;
    margin-top:40px;
}

@media(max-width:768px){
    .about{
        grid-template-columns:1fr;
    }

    .hero h1{
        font-size:40px;
    }

    nav{
        flex-direction:column;
    }

    nav ul{
        margin-top:15px;
    }
}
</style>
</head>

<body>

<header>
<nav>
<div class="logo">DannyWacho Barbershop</div>

<ul>
<li><a href="#home">Home</a></li>
<li><a href="#about">About</a></li>
<li><a href="#services">Services</a></li>
<li><a href="#gallery">Gallery</a></li>
<li><a href="#booking">Booking</a></li>
<li><a href="#contact">Contact</a></li>
</ul>
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
<h3>Welcome to DannyWacho Barbershop</h3>
<br>
<p>
We provide world-class grooming services for gentlemen who appreciate style, confidence and professionalism.
</p>
<br>
<p>
Our experienced barbers specialize in modern fades, classic cuts, beard grooming and luxury treatments.
</p>
<br>
<p>
Your appearance is our priority.
</p>
</div>
</div>
</section>

<section id="services">
<h2 class="section-title">Our Services</h2>

<div class="services">

<div class="card">
<h3>Haircut</h3>
<p>Professional haircut with modern styling.</p>
</div>

<div class="card">
<h3>Skin Fade</h3>
<p>Clean and sharp fade cuts.</p>
</div>

<div class="card">
<h3>Beard Trim</h3>
<p>Expert beard shaping and grooming.</p>
</div>

<div class="card">
<h3>Hair Wash</h3>
<p>Refreshing wash and treatment.</p>
</div>

<div class="card">
<h3>Kids Haircuts</h3>
<p>Stylish cuts for young gentlemen.</p>
</div>

<div class="card">
<h3>VIP Package</h3>
<p>Haircut, beard trim and facial treatment.</p>
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

<form>

<input type="text" placeholder="Full Name" required>

<input type="email" placeholder="Email Address" required>

<input type="tel" placeholder="Phone Number" required>

<select>
<option>Select Service</option>
<option>Haircut</option>
<option>Skin Fade</option>
<option>Beard Trim</option>
<option>VIP Package</option>
</select>

<input type="date">

<textarea rows="5" placeholder="Additional Notes"></textarea>

<button type="submit">Book Now</button>

</form>

</div>
</section>

<section id="contact">
<h2 class="section-title">Contact Us</h2>

<div class="contact">
<h3>DannyWacho Barbershop</h3>
<br>
<p>Email: davillephiri284@gmail.com</p>
<p>Phone: +263 XX XXX XXXX</p>
<p>Open Monday - Sunday</p>
<p>08:00 AM - 08:00 PM</p>
</div>
</section>

<footer>
<p>© 2026 DannyWacho Barbershop. All Rights Reserved.</p>
</footer>

</body>
</html><!DOCTYPE html>
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
    font-family:Arial, sans-serif;
}

body{
    background:#111;
    color:white;
}

header{
    background:linear-gradient(135deg,#000,#333);
    padding:20px;
    position:sticky;
    top:0;
    z-index:1000;
}

nav{
    display:flex;
    justify-content:space-between;
    align-items:center;
}

.logo{
    font-size:28px;
    font-weight:bold;
    color:gold;
}

nav ul{
    display:flex;
    list-style:none;
}

nav ul li{
    margin-left:20px;
}

nav ul li a{
    text-decoration:none;
    color:white;
    transition:.3s;
}

nav ul li a:hover{
    color:gold;
}

.hero{
    height:90vh;
    background:url('https://images.unsplash.com/photo-1622286342621-4bd786c2447c?w=1200') center/cover;
    display:flex;
    align-items:center;
    justify-content:center;
    text-align:center;
}

.hero-content{
    background:rgba(0,0,0,.7);
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
    border-radius:5px;
    font-weight:bold;
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
    background:#222;
    padding:25px;
    border-radius:10px;
    text-align:center;
    transition:.3s;
}

.card:hover{
    transform:translateY(-10px);
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
    background:#1b1b1b;
    border-radius:15px;
    padding:40px;
}

form{
    display:flex;
    flex-direction:column;
}

input,select,textarea{
    padding:15px;
    margin:10px 0;
    border:none;
    border-radius:5px;
}

button{
    background:gold;
    color:black;
    border:none;
    padding:15px;
    font-weight:bold;
    cursor:pointer;
}

.contact{
    text-align:center;
}

footer{
    background:black;
    text-align:center;
    padding:25px;
    margin-top:40px;
}

@media(max-width:768px){
    .about{
        grid-template-columns:1fr;
    }

    .hero h1{
        font-size:40px;
    }

    nav{
        flex-direction:column;
    }

    nav ul{
        margin-top:15px;
    }
}
</style>
</head>

<body>

<header>
<nav>
<div class="logo">DannyWacho Barbershop</div>

<ul>
<li><a href="#home">Home</a></li>
<li><a href="#about">About</a></li>
<li><a href="#services">Services</a></li>
<li><a href="#gallery">Gallery</a></li>
<li><a href="#booking">Booking</a></li>
<li><a href="#contact">Contact</a></li>
</ul>
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
<h3>Welcome to DannyWacho Barbershop</h3>
<br>
<p>
We provide world-class grooming services for gentlemen who appreciate style, confidence and professionalism.
</p>
<br>
<p>
Our experienced barbers specialize in modern fades, classic cuts, beard grooming and luxury treatments.
</p>
<br>
<p>
Your appearance is our priority.
</p>
</div>
</div>
</section>

<section id="services">
<h2 class="section-title">Our Services</h2>

<div class="services">

<div class="card">
<h3>Haircut</h3>
<p>Professional haircut with modern styling.</p>
</div>

<div class="card">
<h3>Skin Fade</h3>
<p>Clean and sharp fade cuts.</p>
</div>

<div class="card">
<h3>Beard Trim</h3>
<p>Expert beard shaping and grooming.</p>
</div>

<div class="card">
<h3>Hair Wash</h3>
<p>Refreshing wash and treatment.</p>
</div>

<div class="card">
<h3>Kids Haircuts</h3>
<p>Stylish cuts for young gentlemen.</p>
</div>

<div class="card">
<h3>VIP Package</h3>
<p>Haircut, beard trim and facial treatment.</p>
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

<form>

<input type="text" placeholder="Full Name" required>

<input type="email" placeholder="Email Address" required>

<input type="tel" placeholder="Phone Number" required>

<select>
<option>Select Service</option>
<option>Haircut</option>
<option>Skin Fade</option>
<option>Beard Trim</option>
<option>VIP Package</option>
</select>

<input type="date">

<textarea rows="5" placeholder="Additional Notes"></textarea>

<button type="submit">Book Now</button>

</form>

</div>
</section>


<h2 class="section-title">Contact Us</h2>

<div class="find us">

<section id="location">
    <h2 class="section-title">Find Us</h2>

    <div style="width:100%;height:450px;border-radius:15px;overflow:hidden;">
        <iframe
            src="https://maps.google.com/maps?q=Ngwere%20Complex,%20Shamva,%20Zimbabwe&t=&z=15&ie=UTF8&iwloc=&output=embed"
            width="100%"
            height="450"
            style="border:0;"
            allowfullscreen=""
            loading="lazy">
        </iframe>
    </div>

    <div style="text-align:center;margin-top:20px;">
        <h3>DannyWacho Barbershop</h3>
        <p>Ngwere Complex, Shamva, Zimbabwe</p>
        <p>Phone: +263 773 187 009</p>
        <p>Email: davillephiri284@gmail.com</p>
    </div>
</section>
<footer>
<p>© 2026 DannyWacho Barbershop. All Rights Reserved.</p>
</footer>

</body>
</html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Dannywacho Barbershop PRO</title>

<style>
body {
margin: 0;
font-family: Arial;
background: #0b0b0b;
color: white;
}

header {
background: black;
padding: 15px;
text-align: center;
border-bottom: 2px solid gold;
}

h1 { color: gold; }

nav {
display: flex;
flex-wrap: wrap;
justify-content: center;
gap: 10px;
background: #111;
padding: 10px;
}

nav button {
background: transparent;
color: white;
border: 1px solid gold;
padding: 8px;
cursor: pointer;
}

nav button:hover {
background: gold;
color: black;
}

.page {
display: none;
padding: 20px;
}

.active {
display: block;
}

.card {
background: #1a1a1a;
padding: 15px;
margin: 10px 0;
border-radius: 10px;
}

.button {
background: gold;
border: none;
padding: 10px;
cursor: pointer;
font-weight: bold;
}

/* AI Chat */
.chatbox {
position: fixed;
bottom: 10px;
right: 10px;
width: 250px;
background: #111;
border: 1px solid gold;
padding: 10px;
border-radius: 10px;
}

input, select {
width: 100%;
padding: 8px;
margin-top: 5px;
}

iframe {
width: 100%;
height: 250px;
border: none;
}

/* Simple animation background */
.bg {
position: fixed;
width: 100%;
height: 100%;
z-index: -1;
background: linear-gradient(120deg, #000, #111, #222);
animation: bg 8s infinite alternate;
}

@keyframes bg {
from { filter: hue-rotate(0deg); }
to { filter: hue-rotate(40deg); }
}
</style>
</head>

<body>

<div class="bg"></div>

<header>
<h1>💈 DANNYWACHO BARBERSHOP</h1>
<p>Fresh Cuts • Clean Fades • Sharp Style</p>
</header>

<nav>
<button onclick="show('home')">Home</button>
<button onclick="show('booking')">Booking</button>
<button onclick="show('gallery')">Gallery</button>
<button onclick="show('admin')">Admin</button>
</nav>

<!-- HOME -->
<div id="home" class="page active">
<div class="card">
<h2>📍 Location</h2>
<iframe src="https://www.google.com/maps?q=dannywacho%20barbershop&output=embed"></iframe>
</div>

<div class="card">
<h2>📞 Contact</h2>
<p>077 318 7009</p>
<button class="button" onclick="location.href='tel:0773187009'">
Call Now
</button>
</div>

<div class="card">
<h2>💇 Services</h2>
<ul>
<li>Fade Haircuts</li>
<li>Beard Styling</li>
<li>Line Ups</li>
<li>Kids Cuts</li>
</ul>
</div>
</div>

<!-- BOOKING -->
<div id="booking" class="page">
<div class="card">
<h2>📅 Book Appointment</h2>

<input id="name" placeholder="Your Name">
<input id="date" type="date">

<select id="style">
<option>Fade</option>
<option>Taper</option>
<option>Beard Trim</option>
<option>Line Up</option>
</select>

<button class="button" onclick="book()">Submit Booking</button>
<p id="msg"></p>
</div>
</div>

<!-- GALLERY -->
<div id="gallery" class="page">
<div class="card"><h3>🔥 Fade Style</h3></div>
<div class="card"><h3>💈 Taper Cut</h3></div>
<div class="card"><h3>🧔 Beard Trim</h3></div>
<div class="card"><h3>✨ Line Up</h3></div>
</div>

<!-- ADMIN -->
<div id="admin" class="page">
<div class="card">
<h2>⚙️ Admin Dashboard</h2>
<div id="list"></div>
</div>
</div>

<!-- AI CHAT -->
<div class="chatbox">
<p id="chat">💈 Ask me about styles...</p>
<input placeholder="Type..." onkeydown="ai(event)">
</div>

<script>
function show(page){
document.querySelectorAll('.page').forEach(p => p.classList.remove('active'));
document.getElementById(page).classList.add('active');

if(page === "admin") loadAdmin();
}

// BOOKING SYSTEM
function book(){
let name = document.getElementById("name").value;
let date = document.getElementById("date").value;
let style = document.getElementById("style").value;

let data = JSON.parse(localStorage.getItem("bookings") || "[]");
data.push({name, date, style});
localStorage.setItem("bookings", JSON.stringify(data));

document.getElementById("msg").innerText =
"✅ Booking saved for " + name;
}

// ADMIN VIEW
function loadAdmin(){
let data = JSON.parse(localStorage.getItem("bookings") || "[]");
let html = "";

data.forEach(b => {
html += `
<div class="card">
👤 ${b.name}<br>
📅 ${b.date}<br>
💇 ${b.style}
</div>`;
});

document.getElementById("list").innerHTML = html || "No bookings yet.";
}

// AI CHATBOT
function ai(e){
if(e.key === "Enter"){
let msg = e.target.value.toLowerCase();
let reply = "";

if(msg.includes("fade")){
reply = "🔥 Try a low fade or skin fade for a clean look.";
}
else if(msg.includes("beard")){
reply = "🧔 Keep your beard sharp with a lineup.";
}
else if(msg.includes("price")){
reply = "💈 Prices are affordable — visit shop for details.";
}
else if(msg.includes("book")){
reply = "📅 Go to Booking section to schedule.";
}
else {
reply = "💈 I recommend a fade + lineup combo.";
}

document.getElementById("chat").innerText = reply;
e.target.value = "";
}
}
</script>

</body>
</html><section id="location">
    <h2 class="section-title">Find Us</h2>

    <div style="width:100%;height:450px;border-radius:15px;overflow:hidden;">
        <iframe
            src="https://maps.google.com/maps?q=Ngwere%20Complex,%20Shamva,%20Zimbabwe&t=&z=15&ie=UTF8&iwloc=&output=embed"
            width="100%"
            height="450"
            style="border:0;"
            allowfullscreen=""
            loading="lazy">
        </iframe>
    </div>

    <div style="text-align:center;margin-top:20px;">
        <h3>DannyWacho Barbershop</h3>
        <p>Ngwere Complex, Shamva, Zimbabwe</p>
        <p>Phone: +263 773 187 009</p>
        <p>Email: davillephiri284@gmail.com</p>
    </div>
</section>
