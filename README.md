<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Community Impact</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family:Arial,Helvetica,sans-serif;
    color:#333;
    line-height:1.6;
    background:#fafafa;
}

header{
    position:sticky;
    top:0;
    background:#fff;
    z-index:100;
    box-shadow:0 2px 8px rgba(0,0,0,.08);
}

nav{
    max-width:1200px;
    margin:auto;
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:18px 30px;
}

.logo{
    color:#d92d27;
    font-size:28px;
    font-weight:bold;
}

nav ul{
    display:flex;
    gap:25px;
    list-style:none;
}

nav a{
    text-decoration:none;
    color:#444;
    font-weight:600;
}

.hero{
    height:70vh;
    background:url("https://images.unsplash.com/photo-1529156069898-49953e39b3ac?auto=format&fit=crop&w=1600&q=80") center/cover;
    display:flex;
    align-items:center;
}

.hero-content{
    max-width:1200px;
    margin:auto;
    color:white;
    padding:40px;
}

.hero h1{
    font-size:58px;
    margin-bottom:20px;
}

.hero p{
    max-width:650px;
    font-size:20px;
}

.btn{
    display:inline-block;
    margin-top:30px;
    background:#d92d27;
    color:white;
    padding:16px 30px;
    border-radius:40px;
    text-decoration:none;
    font-weight:bold;
}

section{
    max-width:1200px;
    margin:auto;
    padding:80px 30px;
}

.split{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:50px;
    align-items:center;
}

.split img{
    width:100%;
    border-radius:12px;
}

.split h2{
    font-size:38px;
    margin-bottom:20px;
}

.stats{
    background:#d92d27;
    color:white;
}

.stats-grid{
    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:30px;
    text-align:center;
}

.stat h2{
    font-size:54px;
}

.cards{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
    gap:25px;
}

.card{
    background:white;
    border-radius:12px;
    overflow:hidden;
    box-shadow:0 6px 20px rgba(0,0,0,.08);
}

.card img{
    width:100%;
    height:220px;
    object-fit:cover;
}

.card-content{
    padding:25px;
}

.cta{
    background:#222;
    color:white;
    text-align:center;
}

footer{
    background:#111;
    color:#aaa;
    text-align:center;
    padding:35px;
}

@media(max-width:900px){

.hero h1{
    font-size:42px;
}

.split{
    grid-template-columns:1fr;
}

.stats-grid{
    grid-template-columns:1fr;
}
}
</style>

</head>
<body>

<header>

<nav>

<div class="logo">Community Impact</div>

<ul>
<li><a href="#">Home</a></li>
<li><a href="#">Our Work</a></li>
<li><a href="#">Programs</a></li>
<li><a href="#">Contact</a></li>
</ul>

</nav>

</header>

<section class="hero">

<div class="hero-content">

<h1>Building Stronger Communities Together</h1>

<p>
Working alongside local organizations and volunteers to create opportunities,
support families, and strengthen communities through meaningful partnerships.
</p>

<a href="#" class="btn">Learn More</a>

</div>

</section>

<section>

<div class="split">

<img src="https://images.unsplash.com/photo-1517486808906-6ca8b3f04846?auto=format&fit=crop&w=1200&q=80">

<div>

<h2>Supporting Local Communities</h2>

<p>
We partner with community organizations to improve access to education,
healthcare, food security, and social services. Every initiative is designed
to create lasting impact and stronger neighbourhoods.
</p>

<br>

<p>
Together with volunteers, donors, and local leaders, we help people build
better futures through sustainable community programs.
</p>

</div>

</div>

</section>

<section class="stats">

<div class="stats-grid">

<div class="stat">
<h2>250+</h2>
<p>Community Projects</p>
</div>

<div class="stat">
<h2>15K</h2>
<p>Lives Supported</p>
</div>

<div class="stat">
<h2>500+</h2>
<p>Volunteers</p>
</div>

</div>

</section>

<section>

<h2 style="text-align:center;margin-bottom:50px;font-size:40px;">
Our Focus Areas
</h2>

<div class="cards">

<div class="card">

<img src="https://images.unsplash.com/photo-1522202176988-66273c2fd55f?auto=format&fit=crop&w=900&q=80">

<div class="card-content">

<h3>Education</h3>

<p>
Creating opportunities for lifelong learning and youth development.
</p>

</div>

</div>

<div class="card">

<img src="https://images.unsplash.com/photo-1505751172876-fa1923c5c528?auto=format&fit=crop&w=900&q=80">

<div class="card-content">

<h3>Health</h3>

<p>
Improving access to wellness programs and community health initiatives.
</p>

</div>

</div>

<div class="card">

<img src="https://images.unsplash.com/photo-1488521787991-ed7bbaae773c?auto=format&fit=crop&w=900&q=80">

<div class="card-content">

<h3>Food Security</h3>

<p>
Supporting families with essential resources and local food programs.
</p>

</div>

</div>

</div>

</section>

<section class="cta">

<h2 style="font-size:42px;margin-bottom:20px;">
Together We Can Create Lasting Change
</h2>

<p style="max-width:700px;margin:auto;">
Join our community of partners, volunteers, and supporters working together to
build stronger and more inclusive communities.
</p>

<a class="btn" href="#" style="margin-top:35px;">
Get Involved
</a>

</section>

<footer>

© 2026 Community Impact Foundation • Demo Landing Page

</footer>

</body>
</html>
