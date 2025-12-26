<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Tech Solution | Future Technology & Services</title>

<style>
*{box-sizing:border-box;}
body{
    margin:0;
    font-family: 'Segoe UI', sans-serif;
    line-height:1.6;
    background:#f4f6f8;
    scroll-behavior:smooth;
}
header{
    background:linear-gradient(135deg,#0f2027,#203a43,#2c5364);
    color:#fff;
    padding:100px 20px;
    text-align:center;
}
header h1{font-size:3.2rem;}
header h3{color:#00eaff;font-weight:400;}
header p{
    max-width:1000px;
    margin:20px auto;
    font-size:1.1rem;
}
.btn{
    display:inline-block;
    padding:14px 35px;
    background:#00eaff;
    color:#000;
    text-decoration:none;
    font-weight:bold;
    border-radius:30px;
    margin-top:25px;
}
section{
    padding:90px 20px;
    max-width:1200px;
    margin:auto;
}
h2{
    text-align:center;
    margin-bottom:50px;
    color:#203a43;
    font-size:2.3rem;
}
.grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
    gap:30px;
}
.card{
    background:#fff;
    padding:30px;
    border-radius:16px;
    box-shadow:0 10px 25px rgba(0,0,0,0.1);
}
.card h4{margin-bottom:10px;}
.contact{
    background:#203a43;
    color:#fff;
    border-radius:20px;
    padding:40px;
}
input,textarea{
    width:100%;
    padding:14px;
    margin:12px 0;
    border:none;
    border-radius:10px;
}
button{
    padding:14px 35px;
    background:#00eaff;
    border:none;
    border-radius:30px;
    font-weight:bold;
    cursor:pointer;
}
footer{
    background:#000;
    color:#aaa;
    text-align:center;
    padding:20px;
}
</style>
</head>

<body>

<!-- HERO -->
<header>
    <h1>Tech Solution</h1>
    <h3>Future Technology & Services</h3>
    <p>
        At Tech Solution, our Agentic AI-powered technology services go beyond traditional development
        by enabling self-optimizing applications, autonomous digital experiences, and data-driven
        business strategies for Industry 4.0 & 5.0 enterprises.
    </p>
    <a href="#contact" class="btn">Get in Touch</a>
</header>

<!-- ABOUT -->
<section>
    <h2>About Us</h2>
    <p style="text-align:center;max-width:1000px;margin:auto;">
        We deliver future-ready web, mobile, and enterprise solutions that accelerate growth,
        enhance customer engagement, and drive digital transformation using AI, automation,
        and cloud-native architectures.
    </p>
</section>

<!-- SERVICES -->
<section>
    <h2>Our Key Services</h2>
    <div class="grid">
        <div class="card"><h4>Intelligent Web Platforms</h4><p>Scalable, AI-powered web applications designed for performance and growth.</p></div>
        <div class="card"><h4>AI-Augmented Mobile Apps</h4><p>Smart mobile solutions with AI-driven personalization and automation.</p></div>
        <div class="card"><h4>Autonomous Process Consulting</h4><p>Optimizing business workflows using Agentic AI systems.</p></div>
        <div class="card"><h4>Digital Experience Design</h4><p>Next-generation UI/UX built for immersive customer engagement.</p></div>
        <div class="card"><h4>Voice & Conversational AI</h4><p>Chatbots and voice assistants for intelligent interaction.</p></div>
        <div class="card"><h4>Marketing Automation</h4><p>Data-driven marketing workflows to boost conversion rates.</p></div>
    </div>
</section>

<!-- TECHNOLOGY -->
<section>
    <h2>Technology Stack</h2>
    <div class="grid">
        <div class="card">HTML • CSS • JavaScript</div>
        <div class="card">React • Node.js</div>
        <div class="card">Python • AI / ML</div>
        <div class="card">API-First & Microservices</div>
        <div class="card">Cloud-Native Architecture</div>
        <div class="card">DevOps & Automation</div>
    </div>
</section>

<!-- CONTACT -->
<section id="contact">
    <h2>Contact Us</h2>
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
