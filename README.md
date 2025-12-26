<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Tech Solution | Smart Digital Services</title>

<style>
body{
    margin:0;
    font-family: 'Segoe UI', sans-serif;
    scroll-behavior: smooth;
}
header{
    background: linear-gradient(135deg,#0f2027,#203a43,#2c5364);
    color:#fff;
    padding:80px 20px;
    text-align:center;
}
header h1{
    font-size:3rem;
}
header p{
    font-size:1.2rem;
}
.btn{
    display:inline-block;
    padding:12px 30px;
    background:#00eaff;
    color:#000;
    text-decoration:none;
    margin-top:20px;
    border-radius:25px;
    font-weight:bold;
}
section{
    padding:70px 20px;
    max-width:1100px;
    margin:auto;
}
h2{
    text-align:center;
    margin-bottom:40px;
    color:#203a43;
}
.about, .services, .tech, .why{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}
.card{
    background:#f9f9f9;
    padding:25px;
    border-radius:12px;
    box-shadow:0 8px 15px rgba(0,0,0,0.1);
    text-align:center;
}
.contact{
    background:#203a43;
    color:#fff;
    border-radius:15px;
    padding:40px;
}
input, textarea{
    width:100%;
    padding:12px;
    margin:10px 0;
    border:none;
    border-radius:8px;
}
button{
    padding:12px 30px;
    border:none;
    background:#00eaff;
    font-weight:bold;
    border-radius:25px;
    cursor:pointer;
}
footer{
    background:#000;
    color:#aaa;
    text-align:center;
    padding:15px;
}
</style>
</head>

<body>

<header>
    <h1>Tech Solution</h1>
    <p>Innovative AI, Web & Automation Services</p>
    <a href="#contact" class="btn">Get Started</a>
</header>

<section id="about">
    <h2>About Us</h2>
    <div class="about">
        <div class="card">
            <p>We are a modern tech solution company providing smart digital services using AI, Web Development and Automation technologies.</p>
        </div>
        <div class="card">
            <p>Our mission is to help businesses grow with innovative, scalable and cost-effective solutions.</p>
        </div>
    </div>
</section>

<section id="services">
    <h2>Our Services</h2>
    <div class="services">
        <div class="card">🌐 Web Development</div>
        <div class="card">🤖 AI Solutions</div>
        <div class="card">⚙ Automation</div>
        <div class="card">📊 Data Analytics</div>
    </div>
</section>

<section id="tech">
    <h2>Technologies We Use</h2>
    <div class="tech">
        <div class="card">HTML • CSS • JavaScript</div>
        <div class="card">React • Node.js</div>
        <div class="card">Python • AI/ML</div>
        <div class="card">Cloud & DevOps</div>
    </div>
</section>

<section id="why">
    <h2>Why Choose Us?</h2>
    <div class="why">
        <div class="card">✔ Skilled Professionals</div>
        <div class="card">✔ Latest Technologies</div>
        <div class="card">✔ Affordable Pricing</div>
        <div class="card">✔ 24/7 Support</div>
    </div>
</section>

<section id="contact">
    <h2 style="color:white">Contact Us</h2>
    <div class="contact">
        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea rows="4" placeholder="Your Message"></textarea>
            <button type="submit">Send Message</button>
        </form>
    </div>
</section>

<footer>
    <p>© 2025 Tech Solution. All Rights Reserved.</p>
</footer>

</body>
</html>
