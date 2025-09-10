<!doctype html>
<html lang="es">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>Landing Shara</title>
<style>
body {
margin: 0;
background: #add8e6; /* azul claro */
color: #111;
font-family: Roboto, sans-serif; /* nueva fuente */
line-height: 1.6;
}
header {
padding: 20px;
border-bottom: 2px solid #333;
background: #87cefa;
}
h1, h2, h3 {
color: red; /* títulos en rojo */
margin-top: 0;
}
.wrap {
max-width: 900px;
margin: 0 auto;
padding: 20px;
}
.hero {
padding: 40px 0;
}
.hero h2 {
font-size: 36px;
}
.card {
background: #f0f8ff;
border: 1px solid #333;
border-radius: 12px;
padding: 16px;
margin-bottom: 16px;
}
a {
color: red;
font-weight: bold;
text-decoration: none;
}
a:hover {
text-decoration: underline;
}
footer {
padding: 24px;
text-align: center;
border-top: 2px solid #333;
margin-top: 30px;
background: #87cefa;
}
</style>
</head>
<body>
<header>
<div class="wrap">
<h1>Shara · UX/UI + Front-End</h1>
</div>
</header>


<main class="wrap">
<section class="hero">
<h2>Hola! Soy Shara 🚀</h2>
<p>Soy <strong>diseñadora UX/UI</strong> y <strong>desarrolladora front-end</strong>. 
  Diseño interfaces bonitas y las convierto en producto con código.
  Actualmente estudio el <em>Web Developer Bootcamp 2025</em> y estoy construyendo mi portfolio híbrido 
  mientras me preparo para trabajar afincada en Madrid.</p>
</section>


<section id="proyectos">
<div class="card">
<h3>Landing personal</h3>
<p>Mi primera web estática con HTML y CSS. <a href="#">Ver demo</a></p>
</div>
<div class="card">
<h3>App del Tiempo</h3>
<p>Aplicación con JavaScript y Fetch API para consultar clima. <a href="#">Ver demo</a></p>
</div>
</section>


<section id="contacto">
<div class="card">
<h3>Contacto</h3>
<p>Escríbeme a <a href="mailto:sharasanzaznar@gmail.com">sharasanzaznar@gmail.com</a></p>
</div>
</section>
</main>


<footer>
© <span id="y"></span> Shara — Hecho con cariño.
</footer>


<script>
document.getElementById('y').textContent = new Date().getFullYear();
</script>
</body>
</html>
