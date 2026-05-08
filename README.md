<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Energia Solar</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
}

body{
font-family: Arial, sans-serif;
background:#f5f5f5;
line-height:1.6;
}

header{
background:linear-gradient(90deg,#ffb300,#ff9800);
color:white;
padding:40px;
text-align:center;
}

header h1{
font-size:40px;
}

nav{
background:#333;
padding:15px;
text-align:center;
position:sticky;
top:0;
}

nav a{
color:white;
margin:15px;
text-decoration:none;
font-weight:bold;
transition:0.3s;
}

nav a:hover{
color:#ffb300;
}

section{
padding:50px 20px;
text-align:center;
}

.cards{
display:flex;
justify-content:center;
gap:20px;
flex-wrap:wrap;
margin-top:30px;
}

.card{
background:white;
padding:20px;
width:260px;
border-radius:10px;
box-shadow:0 0 10px rgba(0,0,0,0.1);
transition:0.3s;
}

.card:hover{
transform:scale(1.05);
}

.info{
max-width:900px;
margin:auto;
text-align:left;
background:white;
padding:30px;
border-radius:10px;
box-shadow:0 0 10px rgba(0,0,0,0.1);
}

.info h2{
margin-top:20px;
color:#ff9800;
}

ul{
margin-left:20px;
margin-top:10px;
}

button{
background:#ff9800;
color:white;
border:none;
padding:12px 20px;
margin-top:20px;
border-radius:5px;
cursor:pointer;
font-size:16px;
transition:0.3s;
}

button:hover{
background:#e68900;
}

.galeria{
display:flex;
justify-content:center;
gap:20px;
flex-wrap:wrap;
margin-top:30px;
}

.galeria img{
width:300px;
border-radius:10px;
box-shadow:0 0 10px rgba(0,0,0,0.2);
}

footer{
background:#222;
color:white;
text-align:center;
padding:20px;
margin-top:40px;
}

</style>
</head>

<body>

<header>

<h1>Energia Solar</h1>

<p>Soluções inteligentes em energia renovável</p>

<button onclick="mostrarMensagem()">
Saiba Mais
</button>

</header>

<nav>
<a href="#inicio">Início</a>
<a href="#sobre">Sobre</a>
<a href="#vantagensTela">Vantagens</a>
<a href="#contato">Contato</a>
</nav>

<section id="inicio">

<h2>Por que escolher energia solar?</h2>

<div class="cards">

<div class="card">
<h3>Economia</h3>
<p>Reduza até 95% da conta de energia.</p>
</div>

<div class="card">
<h3>Sustentável</h3>
<p>Energia limpa e renovável para o planeta.</p>
</div>

<div class="card">
<h3>Valorização</h3>
<p>Seu imóvel pode valorizar com energia solar.</p>
</div>

<div class="card">
<h3>Durabilidade</h3>
<p>Painéis solares podem durar mais de 25 anos.</p>
</div>

</div>

</section>

<section class="info" id="sobre">

<h2>O que é energia solar?</h2>

<p>
A energia solar é uma fonte de energia renovável obtida através da luz e do calor do sol.
Ela é considerada uma das energias mais limpas do mundo.
</p>

<h2>Como funciona?</h2>

<p>
Os painéis solares captam a luz solar e transformam em energia elétrica.
Depois, um inversor converte essa energia para ser utilizada em casas e empresas.
</p>

<h2>Tipos de energia solar</h2>

<ul>
<li><b>Energia Solar Fotovoltaica:</b> gera eletricidade.</li>
<li><b>Energia Solar Térmica:</b> aquece água.</li>
<li><b>Energia Solar Concentrada:</b> usada em grandes usinas.</li>
</ul>

</section>

<section id="vantagensTela">

<h2>Vantagens da Energia Solar</h2>

<div class="cards">

<div class="card">
<h3>Economia</h3>
<p>
A energia solar pode reduzir muito o valor da conta de luz.
</p>
</div>

<div class="card">
<h3>Energia Limpa</h3>
<p>
Não polui o meio ambiente e ajuda na preservação da natureza.
</p>
</div>

<div class="card">
<h3>Baixa Manutenção</h3>
<p>
Os painéis solares precisam de pouca manutenção.
</p>
</div>

<div class="card">
<h3>Durabilidade</h3>
<p>
Os sistemas solares podem durar mais de 25 anos.
</p>
</div>

</div>

</section>

<section>

<h2>Galeria</h2>

<div class="galeria">

<img src="https://images.unsplash.com/photo-1509391366360-2e959784a276?q=80&w=1200&auto=format&fit=crop">

<img src="https://images.unsplash.com/photo-1497440001374-f26997328c1b?q=80&w=1200&auto=format&fit=crop">

<img src="https://images.unsplash.com/photo-1466611653911-95081537e5b7?q=80&w=1200&auto=format&fit=crop">

</div>

</section>

<section id="contato">

<h2>Contato</h2>

<p>Entre em contato para saber mais sobre energia solar.</p>

<button onclick="enviarMensagem()">
Entrar em contato
</button>

</section>

<footer>

<p>© 2026 Energia Solar | Todos os direitos reservados</p>

</footer>

<script>

function mostrarMensagem(){
alert("A energia solar ajuda você a economizar e preservar o meio ambiente!");
}

function enviarMensagem(){
alert("Obrigado pelo interesse em energia solar!");
}

</script>

</body>
</html>
