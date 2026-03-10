DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>VapePod Store</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial, Helvetica, sans-serif;
}

body{
background:#0e0e0e;
color:white;
}

header{
background:black;
padding:20px;
text-align:center;
}

header h1{
color:#00ff9d;
}

nav{
background:#1a1a1a;
padding:12px;
text-align:center;
}

nav a{
color:white;
margin:15px;
text-decoration:none;
font-weight:bold;
}

.hero{
text-align:center;
padding:60px;
background:linear-gradient(black,#222);
}

.hero h2{
font-size:32px;
margin-bottom:10px;
}

.produtos{
display:flex;
flex-wrap:wrap;
justify-content:center;
gap:30px;
padding:40px;
}

.card{
background:#1c1c1c;
border-radius:12px;
padding:20px;
width:220px;
text-align:center;
transition:0.3s;
}

.card:hover{
transform:scale(1.05);
}

.card img{
width:100%;
border-radius:10px;
margin-bottom:10px;
}

.preco{
color:#00ff9d;
font-size:20px;
margin:10px 0;
}

button{
background:#00ff9d;
border:none;
padding:10px 15px;
border-radius:6px;
cursor:pointer;
font-weight:bold;
}

button:hover{
background:#00cc7a;
}

footer{
background:black;
text-align:center;
padding:20px;
margin-top:30px;
}

</style>
</head>

<body>

<header>
<h1>VapePod Store</h1>
<p>Loja de Pods EletrÃ´nicos</p>
</header>

<nav>
<a href="#">InÃ­cio</a>
<a href="#">Produtos</a>
<a href="#">PromoÃ§Ãµes</a>
<a href="#">Contato</a>
</nav>

<section class="hero">
<h2>Os Melhores Pods de 2026</h2>
<p>Qualidade, potÃªncia e estilo</p>
</section>

<section class="produtos">

<div class="card">
<img src="https://via.placeholder.com/200">
<h3>Pod Vapex Pro</h3>
<p class="preco">R$149</p>
<button onclick="comprar()">Comprar</button>
</div>

<div class="card">
<img src="https://via.placeholder.com/200">
<h3>Pod Nano X</h3>
<p class="preco">R$179</p>
<button onclick="comprar()">Comprar</button>
</div>

<div class="card">
<img src="https://via.placeholder.com/200">
<h3>Pod Turbo Max</h3>
<p class="preco">R$199</p>
<button onclick="comprar()">Comprar</button>
</div>

<div class="card">
<img src="https://via.placeholder.com/200">
<h3>Pod Slim Vape</h3>
<p class="preco">R$129</p>
<button onclick="comprar()">Comprar</button>
</div>

</section>

<footer>
<p>Â© 2026 VapePod Store</p>
</footer>

<script>

function comprar(){
alert("Produto adicionado! Configure pagamento para vender.");
}

</script>

</body>
</html>