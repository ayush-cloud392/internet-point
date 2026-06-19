<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Internet Point - Cyber Cafe</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Segoe UI',sans-serif;
}

body{
    background:#f5f7fa;
    color:#333;
}

header{
    background:#0066cc;
    color:white;
    padding:15px 50px;
    display:flex;
    justify-content:space-between;
    align-items:center;
    position:sticky;
    top:0;
}

.logo{
    font-size:28px;
    font-weight:bold;
}

nav a{
    color:white;
    text-decoration:none;
    margin-left:20px;
    font-weight:500;
}

.hero{
    background:linear-gradient(rgba(0,0,0,.6),rgba(0,0,0,.6)),
    url('https://images.unsplash.com/photo-1516321318423-f06f85e504b3?auto=format&fit=crop&w=1600&q=80');
    background-size:cover;
    background-position:center;
    color:white;
    text-align:center;
    padding:120px 20px;
}

.hero h1{
    font-size:50px;
    margin-bottom:15px;
}

.hero p{
    font-size:20px;
    margin-bottom:25px;
}

.btn{
    background:#00c853;
    color:white;
    text-decoration:none;
    padding:12px 25px;
    border-radius:5px;
}

.section{
    padding:70px 20px;
    max-width:1200px;
    margin:auto;
}

.section-title{
    text-align:center;
    margin-bottom:40px;
    color:#0066cc;
    font-size:35px;
}

.about{
    text-align:center;
    line-height:1.8;
}

.services{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.card{
    background:white;
    padding:25px;
    border-radius:10px;
    text-align:center;
    box-shadow:0 3px 10px rgba(0,0,0,.1);
    transition:.3s;
}

.card:hover{
    transform:translateY(-5px);
}

.card h3{
    color:#0066cc;
    margin-bottom:10px;
}

.contact{
    background:#0066cc;
    color:white;
    text-align:center;
    padding:60px 20px;
}

.contact p{
    margin:10px 0;
}

.whatsapp{
    position:fixed;
    right:20px;
    bottom:20px;
    background:#25D366;
    color:white;
    padding:15px 20px;
    border-radius:50px;
    text-decoration:none;
    font-weight:bold;
}

footer{
    background:#003366;
    color:white;
    text-align:center;
    padding:15px;
}

@media(max-width:768px){
    header{
        flex-direction:column;
    }

    nav{
        margin-top:10px;
    }

    .hero h1{
        font-size:35px;
    }
}
</style>
</head>

<body>

<header>
    <div class="logo">Internet Point</div>

    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section class="hero" id="home">
    <h1>Welcome to Internet Point</h1>
    <p>Your Trusted Cyber Cafe & Online Service Center</p>

    <a href="https://wa.me/919308486190" class="btn">
        Contact Now
    </a>
</section>

<section class="section" id="about">
    <h2 class="section-title">About Us</h2>

    <div class="about">
        <p>
            Internet Point is a trusted cyber cafe located in
            Nehru Nagar, Buxar, Bihar.
            We provide all types of online services, document
            printing, resume creation, online form filling and
            many other digital services at affordable prices.
        </p>
    </div>
</section>

<section class="section" id="services">
    <h2 class="section-title">Our Services</h2>

    <div class="services">

        <div class="card">
            <h3>🖨 Print Out</h3>
            <p>Black & White and Color Printing Services.</p>
        </div>

        <div class="card">
            <h3>📄 Online Form Filling</h3>
            <p>Government & Private Application Forms.</p>
        </div>

        <div class="card">
            <h3>📝 Bio Data / Resume</h3>
            <p>Professional Resume & CV Creation.</p>
        </div>

        <div class="card">
            <h3>🌐 All Online Work</h3>
            <p>Registration, Updates, Downloads & More.</p>
        </div>

        <div class="card">
            <h3>📷 Scan & Upload</h3>
            <p>Document Scanning & Online Upload.</p>
        </div>

        <div class="card">
            <h3>💻 Internet Services</h3>
            <p>Fast Internet and Digital Assistance.</p>
        </div>

    </div>
</section>

<section class="contact" id="contact">
    <h2>Contact Us</h2>

    <p><strong>Mobile:</strong> 9308486190</p>

    <p>
        Nehru Nagar, Buxar, Bihar<br>
        Ward No. 32, PIN - 802101
    </p>

    <p>Open Daily - Online Services Available</p>
</section>

<a class="whatsapp"
href="https://wa.me/919308486190"
target="_blank">
WhatsApp
</a>

<footer>
    © 2026 Internet Point | All Rights Reserved
</footer>

</body>
</html>
