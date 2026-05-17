# AUTEC-DO-BRASIL
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Autec | Automação Industrial e Engenharia Elétrica</title>

<meta name="description" content="Automação industrial, painéis elétricos, adequação NR12, retrofit de máquinas e engenharia elétrica industrial.">

<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">

<link href="https://fonts.googleapis.com/css2?family=Rajdhani:wght@500;700&family=Roboto:wght@300;400;500;700&display=swap" rel="stylesheet">

<style>

:root{
--bg:#0b0f14;
--panel:#121820;
--accent:#00ffc3;
--text:#c9d1d9;
--white:#ffffff;
}

body{
background:var(--bg);
color:var(--text);
font-family:'Roboto',sans-serif;
overflow-x:hidden;
}

h1,h2,h3,h4{
font-family:'Rajdhani',sans-serif;
text-transform:uppercase;
letter-spacing:1px;
font-weight:700;
}

.navbar{
background:rgba(11,15,20,0.92);
backdrop-filter:blur(12px);
border-bottom:1px solid #222b36;
}

.navbar-brand{
font-size:2rem;
font-weight:700;
color:var(--white)!important;
}

.navbar-brand span{
color:var(--accent);
}

.nav-link{
color:var(--text)!important;
transition:.3s;
}

.nav-link:hover{
color:var(--accent)!important;
}

.hero{
height:100vh;
display:flex;
align-items:center;
background:
linear-gradient(to right, rgba(11,15,20,1) 0%, rgba(11,15,20,.5) 100%),
url('https://images.unsplash.com/photo-1565008447742-97f6f38c985c?q=80&w=1920&auto=format&fit=crop') center/cover;
}

.hero h1{
font-size:4.5rem;
max-width:800px;
}

.hero h1 span{
color:var(--accent);
}

.hero p{
font-size:1.2rem;
max-width:650px;
margin:25px 0;
}

.btn-custom{
border:2px solid var(--accent);
padding:14px 34px;
color:var(--accent);
text-decoration:none;
font-weight:700;
text-transform:uppercase;
transition:.3s;
display:inline-block;
}

.btn-custom:hover{
background:var(--accent);
color:#000;
box-shadow:0 0 20px var(--accent);
}

.section-title{
margin-bottom:60px;
}

.section-title span{
color:var(--accent);
}

.service-card{
background:var(--panel);
padding:35px;
border-radius:10px;
border:1px solid #222b36;
height:100%;
transition:.4s;
}

.service-card:hover{
transform:translateY(-10px);
border-color:var(--accent);
box-shadow:0 10px 25px rgba(0,255,195,.15);
}

.service-icon{
font-size:3rem;
color:var(--accent);
margin-bottom:25px;
}

.projects img{
border-radius:10px;
border:1px solid #2f3945;
transition:.4s;
}

.projects img:hover{
transform:scale(1.03);
}

.stats{
background:var(--panel);
border-top:1px solid #222b36;
border-bottom:1px solid #222b36;
}

.stat-box h2{
font-size:3rem;
color:var(--accent);
}

footer{
background:#06080b;
border-top:1px solid #222b36;
padding:40px 0;
}

.whatsapp-float{
position:fixed;
bottom:25px;
right:25px;
width:65px;
height:65px;
background:#25D366;
border-radius:50%;
display:flex;
align-items:center;
justify-content:center;
font-size:2rem;
color:#fff;
text-decoration:none;
box-shadow:0 0 20px rgba(0,0,0,.4);
z-index:999;
transition:.3s;
}

.whatsapp-float:hover{
transform:scale(1.1);
color:#fff;
}

@media(max-width:768px){

.hero h1{
font-size:2.8rem;
}

.hero{
text-align:center;
}

}

</style>
</head>

<body>

<nav class="navbar navbar-expand-lg fixed-top">
<div class="container">

<a class="navbar-brand" href="#">
AUT<span>EC</span>
</a>

<button class="navbar-toggler" data-bs-toggle="collapse" data-bs-target="#menu">
<i class="fas fa-bars" style="color:var(--accent);"></i>
</button>

<div class="collapse navbar-collapse justify-content-end" id="menu">

<ul class="navbar-nav">

<li class="nav-item">
<a class="nav-link" href="#servicos">Serviços</a>
</li>

<li class="nav-item">
<a class="nav-link" href="#projetos">Projetos</a>
</li>

<li class="nav-item">
<a class="nav-link" href="#contato">Contato</a>
</li>

</ul>

</div>

</div>
</nav>

<section class="hero">

<div class="container">

<h1>
AUTOMAÇÃO E ENGENHARIA
<span>INDUSTRIAL</span>
</h1>

<p>
Especialistas em adequação NR12, painéis elétricos, retrofit de máquinas, infraestrutura industrial e sistemas de automação.
</p>

<a href="#contato" class="btn-custom">
Solicitar orçamento
</a>

</div>

</section>

<section class="py-5" id="servicos">

<div class="container py-5">

<div class="section-title text-center">
<h2>
Soluções de <span>Alta Performance</span>
</h2>
</div>

<div class="row g-4">

<div class="col-md-4">
<div class="service-card text-center">

<i class="fas fa-microchip service-icon"></i>

<h4>Automação Industrial</h4>

<p>
Integração de CLPs, IHMs, sensores, redes industriais e lógica de automação para máquinas e processos industriais.
</p>

</div>
</div>

<div class="col-md-4">
<div class="service-card text-center">

<i class="fas fa-shield-halved service-icon"></i>

<h4>Adequação NR12</h4>

<p>
Projetos de segurança de máquinas com relés de segurança, bimanual, cortina de luz e validação técnica.
</p>

</div>
</div>

<div class="col-md-4">
<div class="service-card text-center">

<i class="fas fa-bolt service-icon"></i>

<h4>Painéis Elétricos</h4>

<p>
Montagem de painéis elétricos, CCMs, retrofit industrial e infraestrutura elétrica conforme normas técnicas.
</p>

</div>
</div>

</div>

</div>

</section>

<section class="stats py-5">

<div class="container">

<div class="row text-center">

<div class="col-md-4 stat-box">
<h2>NR12</h2>
<p>Segurança e conformidade industrial</p>
</div>

<div class="col-md-4 stat-box">
<h2>CLP</h2>
<p>Automação inteligente de máquinas</p>
</div>

<div class="col-md-4 stat-box">
<h2>24/7</h2>
<p>Suporte técnico especializado</p>
</div>

</div>

</div>

</section>

<section class="projects py-5" id="projetos">

<div class="container py-5">

<div class="section-title text-center">
<h2>
Projetos e <span>Engenharia</span>
</h2>
</div>

<div class="row g-4">

<div class="col-md-4">
<img src="https://images.unsplash.com/photo-1581092580497-e0d23cbdf1dc?q=80&w=800&auto=format&fit=crop" class="img-fluid">
</div>

<div class="col-md-4">
<img src="https://images.unsplash.com/photo-1517048676732-d65bc937f952?q=80&w=800&auto=format&fit=crop" class="img-fluid">
</div>

<div class="col-md-4">
<img src="https://images.unsplash.com/photo-1563770660941-20978e870e26?q=80&w=800&auto=format&fit=crop" class="img-fluid">
</div>

</div>

</div>

</section>

<section class="py-5" id="contato">

<div class="container py-5 text-center">

<h2 class="mb-4">
Solicite um orçamento técnico
</h2>

<p class="mb-5">
Entre em contato para projetos industriais, adequações elétricas e automação.
</p>

<div class="d-flex justify-content-center gap-3 flex-wrap">

<a href="https://wa.me/5500000000000"
target="_blank"
class="btn-custom"
style="background:var(--accent);color:#000;">

<i class="fab fa-whatsapp me-2"></i>
WhatsApp

</a>

<a href="mailto:contato@autec.com.br"
class="btn-custom">

<i class="fas fa-envelope me-2"></i>
E-mail

</a>

</div>

</div>

</section>

<footer>

<div class="container">

<div class="row align-items-center">

<div class="col-md-6 text-center text-md-start mb-3 mb-md-0">

<h5 style="color:var(--accent);font-weight:700;">
AUTEC
</h5>

<small>
Automação Industrial e Engenharia Elétrica
</small>

</div>

<div class="col-md-6 text-center text-md-end">

<small>
© 2026 AUTEC - Todos os direitos reservados
</small>

</div>

</div>

</div>

</footer>

<a href="https://wa.me/5500000000000"
target="_blank"
class="whatsapp-float">

<i class="fab fa-whatsapp"></i>

</a>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>
