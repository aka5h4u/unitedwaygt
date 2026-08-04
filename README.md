<html lang="en">

<head>

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1, minimum-scale=1">

<title>United Way Greater Toronto</title>


<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}


body{
    font-family:Arial, Helvetica, sans-serif;
    color:#333;
    background:#fafafa;
    line-height:1.6;
}


/* HEADER */

header{
    position:sticky;
    top:0;
    background:#fff;
    z-index:100;
    box-shadow:0 2px 10px rgba(0,0,0,.12);
}


nav{

    max-width:1200px;
    margin:auto;
    height:85px;
    padding:0 30px;

    display:flex;
    align-items:center;
    justify-content:space-between;

}


/* LOGO */

.logo img{

    height:60px;
    width:auto;

}


/* MENU */

nav ul{

    display:flex;
    gap:35px;
    align-items:center;
    list-style:none;

}


nav a{

    text-decoration:none;
    color:#333;
    font-weight:600;

}


nav a:hover{

    color:#d92d27;

}



/* HERO */

.hero{

    min-height:75vh;

    background:
    linear-gradient(
        rgba(0,0,0,.55),
        rgba(0,0,0,.55)
    ),
    url("https://images.unsplash.com/photo-1529156069898-49953e39b3ac?auto=format&fit=crop&w=1600&q=80")
    center/cover;


    display:flex;
    align-items:center;

}



.hero-content{

    max-width:1200px;
    width:100%;
    margin:auto;

    padding:50px 30px;

    color:white;

}



.hero h1{

    font-size:60px;
    line-height:1.2;
    max-width:800px;

    margin-bottom:25px;

}



.hero p{

    max-width:700px;

    font-size:20px;

}



.btn{

    display:inline-block;

    margin-top:30px;

    background:#d92d27;

    color:white;

    padding:15px 35px;

    border-radius:40px;

    text-decoration:none;

    font-weight:bold;

}



/* SECTIONS */


section{

    max-width:1200px;
    margin:auto;
    padding:80px 30px;

}



/* ABOUT */

.split{

    display:grid;

    grid-template-columns:1fr 1fr;

    gap:50px;

    align-items:center;

}



.split img{

    width:100%;
    border-radius:15px;

}



.split h2{

    font-size:40px;

    margin-bottom:20px;

}




/* STATS */


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

    font-size:55px;

}




/* CARDS */


.cards{

    display:grid;

    grid-template-columns:
    repeat(auto-fit,minmax(260px,1fr));

    gap:30px;

}



.card{

    background:white;

    border-radius:15px;

    overflow:hidden;

    box-shadow:0 8px 25px rgba(0,0,0,.08);

}



.card img{

    width:100%;

    height:220px;

    object-fit:cover;

}



.card-content{

    padding:25px;

}



/* CTA */


.cta{

    background:#222;

    color:white;

    text-align:center;

}


.cta h2{

    font-size:42px;

}



/* FOOTER */


footer{

    background:#111;

    color:#aaa;

    text-align:center;

    padding:35px;

}



/* MOBILE */

@media(max-width:900px){


nav{

    height:auto;

    flex-direction:column;

    padding:20px;

}



nav ul{

    margin-top:20px;

    flex-wrap:wrap;

    justify-content:center;

}



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


<div class="logo">

<!-- Put your logo file in the same folder -->

<img src="logo.png" alt="United Way Greater Toronto Logo">

</div>



<ul>

<li>
<a href="#">Home</a>
</li>


<li>
<a href="#work">Our Work</a>
</li>


<li>
<a href="#programs">Programs</a>
</li>


<li>
<a href="#contact">Contact</a>
</li>


</ul>


</nav>


</header>





<section class="hero">


<div class="hero-content">


<h1>
Building a GTA for all
</h1>


<p>

It takes unwavering determination and hard work to ensure the issues facing our community today don't define our future. Together, we are building stronger communities across Peel, Toronto and York Region.

</p>



<a class="btn" href="#work">

Learn More

</a>


</div>


</section>





<section id="work">


<div class="split">


<img src="https://images.unsplash.com/photo-1517486808906-6ca8b3f04846?auto=format&fit=crop&w=1200&q=80">


<div>


<h2>
Supporting Local Communities
</h2>


<p>

We partner with community organizations to improve access to education, healthcare, food security, and social services.

</p>


<br>


<p>

Together with volunteers, donors and local leaders, we create lasting impact.

</p>


</div>


</div>


</section>





<section class="stats">


<div class="stats-grid">


<div class="stat">

<h2>
250+
</h2>

<p>
Community Projects
</p>

</div>



<div class="stat">

<h2>
15K
</h2>

<p>
Lives Supported
</p>

</div>



<div class="stat">

<h2>
500+
</h2>

<p>
Volunteers
</p>

</div>


</div>


</section>






<section id="programs">


<h2 style="text-align:center;font-size:40px;margin-bottom:50px">

Our Focus Areas

</h2>



<div class="cards">


<div class="card">

<img src="https://images.unsplash.com/photo-1522202176988-66273c2fd55f?auto=format&fit=crop&w=900&q=80">


<div class="card-content">

<h3>
Education
</h3>

<p>
Creating opportunities for lifelong learning and youth development.
</p>


</div>

</div>




<div class="card">

<img src="https://images.unsplash.com/photo-1505751172876-fa1923c5c528?auto=format&fit=crop&w=900&q=80">


<div class="card-content">

<h3>
Health
</h3>

<p>
Improving access to wellness programs and community services.
</p>


</div>

</div>




<div class="card">

<img src="https://images.unsplash.com/photo-1488521787991-ed7bbaae773c?auto=format&fit=crop&w=900&q=80">


<div class="card-content">

<h3>
Food Security
</h3>

<p>
Supporting families with essential resources.
</p>


</div>

</div>


</div>


</section>






<section class="cta">


<h2>
Together We Can Create Lasting Change
</h2>


<p>

Join our community of partners, volunteers, and supporters.

</p>


<a href="#" class="btn">

Get Involved

</a>


</section>






<footer id="contact">

© 2026 United Way Greater Toronto • AI Demo Page

</footer>





<!-- ===================================== -->
<!-- Salesforce Embedded Messaging -->
<!-- Must be before closing body tag -->
<!-- ===================================== -->


<script type='text/javascript'>

function initEmbeddedMessaging() {

    try {

        embeddedservice_bootstrap.settings.language = 'en_US';


        embeddedservice_bootstrap.init(

            '00DgL00000OQ3nd',

            'Github_Messaging_Setting',

            'https://saastrion-dev-ed.develop.my.site.com/ESWGithubMessagingSetti1776887653761',

            {
                scrt2URL:
                'https://saastrion-dev-ed.develop.my.salesforce-scrt.com'
            }

        );


    } catch (err) {

        console.error(
            'Error loading Embedded Messaging: ',
            err
        );

    }

}

</script>



<script 

type='text/javascript'

src='https://saastrion-dev-ed.develop.my.site.com/ESWGithubMessagingSetti1776887653761/assets/js/bootstrap.min.js'

onload='initEmbeddedMessaging()'>

</script>



</body>

</html>
