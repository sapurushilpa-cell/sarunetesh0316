<!DOCTYPE html>
<html>
<head>
<title>12 Jyotirlingas of India</title>



<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial,sans-serif;
}

body{
    background:
    linear-gradient(rgba(5,5,40,0.75), rgba(10,10,50,0.85)),
    url("thrishul.png");

    background-size:cover;
    background-position:center;
    background-repeat:no-repeat;
    background-attachment:fixed;
}

/* Header */

header{
    background:rgba(0,0,0,0.5);
    backdrop-filter:blur(10px);
    padding:15px 40px;
    display:flex;
    justify-content:space-between;
    align-items:center;
    position:sticky;
    top:0;
    z-index:1000;
}

.logo{
    font-size:30px;
    color:white;
    font-weight:bold;
}

/* Navbar */

nav ul{
    list-style:none;
    display:flex;
    gap:25px;
}

nav a{
    text-decoration:none;
    color:white;
    font-weight:bold;
    transition:0.3s;
}

nav a:hover{
    color:#c77dff;
}

/* Hero Section */

.hero{
    height:500px;

    background:
    linear-gradient(rgba(0,0,0,0.4),
    rgba(20,0,40,0.7)),
    url("shiva1.png");

    background-size:cover;
    background-position:center;

    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    color:white;

    border-radius:0 0 30px 30px;
    margin-bottom:30px;
}

.hero h1{
    font-size:75px;
    text-shadow:3px 3px 15px black;
}

.hero p{
    font-size:28px;
    margin-top:10px;
    text-shadow:2px 2px 10px black;
}

/* Section Title */

.section-title{
    text-align:center;
    color:white;
    margin:40px 0;
    font-size:45px;
    text-shadow:2px 2px 10px black;
}

/* Jyotirlinga Cards */

.jyoti-container{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
    gap:25px;
    padding:30px;
}

.card{
    background:rgba(12,25,95,0.9);
    border-radius:20px;
    padding:15px;
    text-align:center;
    color:white;
    box-shadow:0 0 20px rgba(255,255,255,0.2);
    transition:0.4s;
}

.card:hover{
    transform:translateY(-10px);
}

.card img{
    width:100%;
    height:220px;
    object-fit:cover;
    border-radius:15px;
}

.card h3{
    margin-top:10px;
    font-size:25px;
}

.card p{
    margin-top:8px;
}

.card button{
    margin-top:12px;
    background:#7b2cbf;
    color:white;
    border:none;
    padding:10px 18px;
    border-radius:10px;
    cursor:pointer;
    transition:0.3s;
}

.card button:hover{
    background:#9d4edd;
}

/* Info Sections */

.info-section{
    background:rgba(10,20,90,0.85);
    margin:25px auto;
    padding:30px;
    border-radius:20px;
    text-align:center;
    color:white;
    width:90%;
    box-shadow:0 0 15px rgba(255,255,255,0.2);
}

.info-section h2{
    margin-bottom:15px;
    color:#ffffff;
}

.info-section p{
    margin:10px 0;
    font-size:18px;
}

.info-section button{
    margin-top:15px;
    background:#7b2cbf;
    color:white;
    border:none;
    padding:12px 20px;
    border-radius:10px;
    cursor:pointer;
}

.info-section button:hover{
    background:#9d4edd;
}

/* Popup */

.popup{
    display:none;
    position:fixed;
    top:0;
    left:0;
    width:100%;
    height:100%;
    background:rgba(0,0,0,0.8);
    justify-content:center;
    align-items:center;
    z-index:1000;
}

.popup-content{
    background:white;
    padding:30px;
    border-radius:20px;
    text-align:center;
    width:500px;
    max-height:80vh;
    overflow-y:auto;
}

.popup-content h2{
    color:#6a0dad;
    margin-bottom:20px;
}

.popup-content button{
    margin:8px;
    background:#7b2cbf;
    color:white;
    border:none;
    padding:10px 18px;
    border-radius:10px;
    cursor:pointer;
}

.popup-content button:hover{
    background:#9d4edd;
}

.close-btn{
    float:right;
    font-size:35px;
    cursor:pointer;
    font-weight:bold;
}

/* Footer */

footer{
    background:rgba(0,0,0,0.7);
    color:white;
    text-align:center;
    padding:25px;
    margin-top:30px;
}

</style>


</head>

<body>

<header>

    <div class="logo">12 JYOTIRLINGAS</div>

    <nav>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#jyotirlingas">Jyotirlingas</a></li>
            <li><a href="#about">About</a></li>
        </ul>
    </nav>

</header>

<section class="hero">

    <div>
        <h1>12 Jyotirlingas</h1>
        <p>Divine Abodes of Lord Shiva</p>
    </div>

</section>

<section class="info-section">

    <h2>Welcome to 12 Jyotirlingas of India</h2>

    <p>
        This website is dedicated to the sacred 12 Jyotirlingas of Lord Shiva,
        located across different parts of India.
    </p>

    <p>
        Explore temple information, locations, interesting facts,
        festivals, travel guidance, and online booking facilities.
    </p>

    <p>
        The website helps devotees and travelers discover the divine
        spiritual heritage of India in one place.
    </p>

    <h3 style="color:#6a0dad; margin-top:15px;">
        Har Har Mahadev!
    </h3>

</section>

<h2 class="section-title" id="jyotirlingas">
    The 12 Jyotirlingas
</h2>

<div class="jyoti-container">

<div class="card">
    <img src="somnath.png">
    <h3>Somnath</h3>
    <p>Veraval, Gujarat</p>
    <p>First Jyotirlinga near the Arabian Sea.</p>
    <a href="https://en.wikipedia.org/wiki/Somnath_temple" target="_blank">
        <button>More Information</button>
    </a>
</div>

<div class="card">
    <img src="mallikarjuna.png">
    <h3>Mallikarjuna</h3>
    <p>Srisailam, Andhra Pradesh</p>
    <p>Located on the Krishna River banks.</p>
    <a href="https://en.wikipedia.org/wiki/Mallikarjuna_Temple,_Srisailam" target="_blank">
        <button>More Information</button>
    </a>
</div>

<div class="card">
    <img src="mahakaleshwar.png">
    <h3>Mahakaleshwar</h3>
    <p>Ujjain, Madhya Pradesh</p>
    <p>Famous for sacred Bhasma Aarti.</p>
    <a href="https://en.wikipedia.org/wiki/Mahakaleshwar_Jyotirlinga" target="_blank">
        <button>More Information</button>
    </a>
</div>

<div class="card">
    <img src="omkareshwar.png">
    <h3>Omkareshwar</h3>
    <p>Khandwa, Madhya Pradesh</p>
    <p>Island shaped like the Om symbol.</p>
    <a href="https://en.wikipedia.org/wiki/Omkareshwar_Temple" target="_blank">
        <button>More Information</button>
    </a>
</div>

<div class="card">
    <img src="kedarnath.png">
    <h3>Kedarnath</h3>
    <p>Uttarakhand</p>
    <p>Located in the Himalayas.</p>
    <a href="https://en.wikipedia.org/wiki/Kedarnath_Temple" target="_blank">
        <button>More Information</button>
    </a>
</div>

<div class="card">
    <img src="bhimashankar.png">
    <h3>Bhimashankar</h3>
    <p>Maharashtra</p>
    <p>Surrounded by forests.</p>
    <a href="https://en.wikipedia.org/wiki/Bhimashankar_Temple" target="_blank">
        <button>More Information</button>
    </a>
</div>

<div class="card">
    <img src="kashi.png">
    <h3>Kashi Vishwanath</h3>
    <p>Varanasi</p>
    <p>One of the holiest Shiva temples.</p>
    <a href="https://en.wikipedia.org/wiki/Kashi_Vishwanath_Temple" target="_blank">
        <button>More Information</button>
    </a>
</div>

<div class="card">
    <img src="trimbakeshwar.png">
    <h3>Trimbakeshwar</h3>
    <p>Nashik</p>
    <p>Near Godavari River origin.</p>
    <a href="https://en.wikipedia.org/wiki/Trimbakeshwar_Shiva_Temple" target="_blank">
        <button>More Information</button>
    </a>
</div>

<div class="card">
    <img src="vaidyanth.png">
    <h3>Vaidyanath</h3>
    <p>Jharkhand</p>
    <p>Also called Baidyanath Dham.</p>
    <a href="https://en.wikipedia.org/wiki/Baidyanath_Temple" target="_blank">
        <button>More Information</button>
    </a>
</div>

<div class="card">
    <img src="nageshwar.png">
    <h3>Nageshwar</h3>
    <p>Dwarka, Gujarat</p>
    <p>Known for giant Shiva statue.</p>
    <a href="https://en.wikipedia.org/wiki/Nageshvara_Jyotirlinga" target="_blank">
        <button>More Information</button>
    </a>
</div>

<div class="card">
    <img src="rameshwaram.png">
    <h3>Rameshwaram</h3>
    <p>Tamil Nadu</p>
    <p>Connected with Ramayana.</p>
    <a href="https://en.wikipedia.org/wiki/Ramanathaswamy_Temple" target="_blank">
        <button>More Information</button>
    </a>
</div>

<div class="card">
    <img src="grishneshwar.png">
    <h3>Grishneshwar</h3>
    <p>Maharashtra</p>
    <p>Near Ellora Caves.</p>
    <a href="https://en.wikipedia.org/wiki/Grishneshwar_Temple" target="_blank">
        <button>More Information</button>
    </a>
</div>

</div>

<section class="info-section" id="about">

    <h2>Interesting Facts</h2>

    <p>Kedarnath is the highest Jyotirlinga.</p>
    <p>Somnath is near the Arabian Sea.</p>
    <p>Kashi Vishwanath is among the most visited temples.</p>
    <p>Grishneshwar is near Ellora Caves.</p>

</section>

<section class="info-section">

    <h2>Major Festivals</h2>

    <p>Maha Shivaratri</p>
    <p>Shravan Month Celebrations</p>
    <p>Kartik Purnima</p>

</section>

<section class="info-section">

    <h2>Travel Information</h2>

    <p>Airports available near major temples.</p>
    <p>Railway connectivity available.</p>
    <p>Hotels and pilgrim accommodation nearby.</p>
    <p>Best season: October–March.</p>

</section>

<section class="info-section">

    <h2>Accommodation</h2>

    <p>Budget Hotels Available</p>
    <p>Temple Guest Houses</p>
    <p>Online Hotel Booking</p>

    <a href="https://www.booking.com/" target="_blank">
        <button>Book Hotels</button>
    </a>

</section>

<section class="info-section">

    <h2>Temple Ticket Booking</h2>

    <p>Book Darshan Tickets for all 12 Jyotirlingas</p>

    <button onclick="openPopup()">Book Tickets</button>

</section>

<div id="bookingPopup" class="popup">

    <div class="popup-content">

        <span class="close-btn" onclick="closePopup()">&times;</span>

        <h2>12 Jyotirlinga Booking</h2>

        <a href="https://somnath.org/" target="_blank"><button>Somnath</button></a>
        <a href="https://www.srisailadevasthanam.org/" target="_blank"><button>Mallikarjuna</button></a>
        <a href="https://shrimahakaleshwar.com/" target="_blank"><button>Mahakaleshwar</button></a>
        <a href="https://omkareshwar.org/" target="_blank"><button>Omkareshwar</button></a>
        <a href="https://registrationandtouristcare.uk.gov.in/" target="_blank"><button>Kedarnath</button></a>
        <a href="https://bhimashankar.in/" target="_blank"><button>Bhimashankar</button></a>
        <a href="https://www.shrikashivishwanath.org/" target="_blank"><button>Kashi Vishwanath</button></a>
        <a href="https://trimbakeshwartrust.com/" target="_blank"><button>Trimbakeshwar</button></a>
        <a href="https://www.baidyanathdham.com/" target="_blank"><button>Vaidyanath</button></a>
        <a href="https://www.dwarkadhish.org/" target="_blank"><button>Nageshwar</button></a>
        <a href="https://www.rameswaramtemple.org/" target="_blank"><button>Rameshwaram</button></a>
        <a href="https://grishneshwar.org/" target="_blank"><button>Grishneshwar</button></a>

    </div>

</div>

<footer>

    © 2026 12 Jyotirlingas of India <br>
    Har Har Mahadev

</footer>

<script>

function openPopup(){
    document.getElementById("bookingPopup").style.display = "flex";
}

function closePopup(){
    document.getElementById("bookingPopup").style.display = "none";
}

</script>

</body>
</html>
