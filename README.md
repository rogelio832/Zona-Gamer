# Zona-Gamer<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>GAMER UNIVERSE</title>

<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
scroll-behavior:smooth;
font-family:'Orbitron', sans-serif;
}

body{
background:linear-gradient(135deg,#050505,#0d0d0d,#1b0029);
color:white;
overflow-x:hidden;
}

/* FONDO */
body::before{
content:'';
position:fixed;
width:200%;
height:200%;
background:
radial-gradient(circle,#00ffff22 1px, transparent 1px);
background-size:40px 40px;
animation:fondo 20s linear infinite;
z-index:-1;
}

@keyframes fondo{
0%{
transform:translate(0,0);
}
100%{
transform:translate(-100px,-100px);
}
}

/* HEADER */

header{
text-align:center;
padding:50px 20px;
border-bottom:3px solid cyan;
box-shadow:0 0 20px cyan;
}

header h1{
font-size:65px;
color:cyan;
text-shadow:0 0 20px cyan;
}

header p{
margin-top:15px;
font-size:18px;
color:#ccc;
}

/* MENU */

nav{
display:flex;
justify-content:center;
flex-wrap:wrap;
gap:20px;
padding:25px;
}

nav a{
text-decoration:none;
color:white;
padding:12px 25px;
border:2px solid cyan;
border-radius:15px;
transition:.3s;
box-shadow:0 0 10px cyan;
}

nav a:hover{
background:cyan;
color:black;
transform:scale(1.1);
}

/* SECCIONES */

.seccion{
padding:70px 25px;
max-width:1200px;
margin:auto;
}

.card{
background:#111;
border:2px solid #ff00ff;
border-radius:25px;
overflow:hidden;
margin-bottom:40px;
box-shadow:0 0 20px #ff00ff66;
transition:.4s;
}

.card:hover{
transform:translateY(-10px);
box-shadow:0 0 35px #ff00ff;
}

.card img{
width:100%;
height:350px;
object-fit:cover;
}

.card-content{
padding:30px;
}

.card h2{
color:cyan;
margin-bottom:20px;
font-size:35px;
}

.card p{
line-height:1.9;
color:#ddd;
font-size:16px;
}

.boton{
display:inline-block;
margin-top:25px;
padding:14px 25px;
background:cyan;
color:black;
text-decoration:none;
font-weight:bold;
border-radius:15px;
transition:.3s;
}

.boton:hover{
background:#ff00ff;
color:white;
box-shadow:0 0 20px #ff00ff;
}

/* TABLA */

table{
width:100%;
border-collapse:collapse;
margin-top:20px;
}

table th,
table td{
border:1px solid cyan;
padding:15px;
text-align:center;
}

table th{
background:cyan;
color:black;
}

/* FOOTER */

footer{
text-align:center;
padding:35px;
border-top:3px solid cyan;
color:#aaa;
margin-top:40px;
}

</style>
</head>

<body>

<header>
<h1>🎮 GAMER UNIVERSE 🎮</h1>
<p>Noticias, historia, eSports, consolas y el universo gamer completo 🔥</p>
</header>

<nav>
<a href="#historia">Historia</a>
<a href="#generos">Géneros</a>
<a href="#consolas">Consolas</a>
<a href="#esports">eSports</a>
<a href="#top">Top Juegos</a>
<a href="#futuro">Futuro</a>
</nav>

<!-- HISTORIA -->

<section class="seccion" id="historia">

<div class="card">
<img src="https://images.unsplash.com/photo-1542751371-adc38448a05e">
<div class="card-content">

<h2>🕹️ Historia de los videojuegos</h2>

<p>
Los videojuegos comenzaron en los años 70 con juegos simples como Pong.
Con el paso de los años aparecieron consolas legendarias como Atari,
Nintendo, PlayStation y Xbox.
</p>

<p>
Actualmente el gaming es una de las industrias más grandes del mundo,
superando incluso al cine y la música juntos.
</p>

<a class="boton" href="#generos">Seguir leyendo</a>

</div>
</div>

</section>

<!-- GENEROS -->

<section class="seccion" id="generos">

<div class="card">
<img src="https://images.unsplash.com/photo-1511512578047-dfb367046420">
<div class="card-content">

<h2>⚔️ Géneros más populares</h2>

<p>
Existen muchísimos géneros de videojuegos:
</p>

<table>
<tr>
<th>Género</th>
<th>Ejemplo</th>
</tr>

<tr>
<td>Battle Royale</td>
<td>Fortnite</td>
</tr>

<tr>
<td>Shooter</td>
<td>Call of Duty</td>
</tr>

<tr>
<td>Sandbox</td>
<td>Minecraft</td>
</tr>

<tr>
<td>RPG</td>
<td>Elden Ring</td>
</tr>

<tr>
<td>Deportes</td>
<td>FIFA</td>
</tr>

</table>

</div>
</div>

</section>

<!-- CONSOLAS -->

<section class="seccion" id="consolas">

<div class="card">
<img src="https://images.unsplash.com/photo-1606144042614-b2417e99c4e3">
<div class="card-content">

<h2>🎮 Consolas más famosas</h2>

<p>
Las consolas más conocidas son:
PlayStation, Xbox y Nintendo Switch.
Cada una tiene juegos exclusivos y millones de jugadores alrededor del mundo.
</p>

<p>
También existe el gaming en PC, conocido por tener mejores gráficos,
mods y rendimiento extremo.
</p>

<a class="boton" href="#esports">Ver eSports</a>

</div>
</div>

</section>

<!-- ESPORTS -->

<section class="seccion" id="esports">

<div class="card">
<img src="https://images.unsplash.com/photo-1560253023-3ec5d502959f">
<div class="card-content">

<h2>🏆 Mundo de los eSports</h2>

<p>
Los eSports son competencias profesionales de videojuegos.
Jugadores profesionales participan en torneos mundiales por millones de dólares.
</p>

<p>
Los juegos más importantes en eSports son:
Valorant, League of Legends, Counter Strike y Rocket League.
</p>

</div>
</div>

</section>

<!-- TOP -->

<section class="seccion" id="top">

<div class="card">
<img src="https://images.unsplash.com/photo-1493711662062-fa541adb3fc8">
<div class="card-content">

<h2>🔥 Top videojuegos populares</h2>

<p>
Actualmente algunos de los juegos más jugados son:
</p>

<table>

<tr>
<th>Juego</th>
<th>Jugadores</th>
</tr>

<tr>
<td>Minecraft</td>
<td>300M+</td>
</tr>

<tr>
<td>Fortnite</td>
<td>230M+</td>
</tr>

<tr>
<td>Roblox</td>
<td>200M+</td>
</tr>

<tr>
<td>GTA V</td>
<td>185M+</td>
</tr>

</table>

</div>
</div>

</section>

<!-- FUTURO -->

<section class="seccion" id="futuro">

<div class="card">
<img src="https://images.unsplash.com/photo-1535223289827-42f1e9919769">
<div class="card-content">

<h2>🚀 El futuro del gaming</h2>

<p>
La realidad virtual, inteligencia artificial y el juego en la nube están
cambiando completamente la industria gamer.
</p>

<p>
En el futuro veremos gráficos hiperrealistas, mundos más grandes
y experiencias mucho más inmersivas.
</p>

<a class="boton" href="#historia">Volver arriba</a>

</div>
</div>

</section>

<footer>

<p>
© 2026 Gamer Universe | Página gamer épica creada por un futuro programador 😎🔥
</p>

</footer>

</body>
</html>
