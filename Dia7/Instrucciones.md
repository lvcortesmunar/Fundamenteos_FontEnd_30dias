🟢 DÍA 7 — MINI LANDING PAGE
🎯 Objetivo

Integrar todo: HTML + CSS

🧠 Introducción

Aquí haces tu primera web real.

💻 Código completo
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Dia 7</title>

  <style>
    body {
      font-family: Arial;
      margin: 0;
    }

    header {
      background: black;
      color: white;
      padding: 20px;
      display: flex;
      justify-content: space-between;
    }

    .hero {
      text-align: center;
      padding: 50px;
    }

    .cards {
      display: flex;
      gap: 20px;
      padding: 20px;
    }

    .card {
      background: lightgray;
      padding: 20px;
      flex: 1;
    }

    footer {
      text-align: center;
      padding: 20px;
    }
  </style>

</head>
<body>

<header>
  <h1>Logo</h1>
  <nav>
    <a href="#">Inicio</a>
    <a href="#">Contacto</a>
  </nav>
</header>

<section class="hero">
  <h2>Mi primera landing</h2>
  <p>Frontend sin pensar</p>
</section>

<section class="cards">
  <div class="card">Servicio 1</div>
  <div class="card">Servicio 2</div>
  <div class="card">Servicio 3</div>
</section>

<footer>
  <p>Footer</p>
</footer>

</body>
</html>
✅ Checklist
 Tiene header, hero, cards y footer
 Usa flexbox
 Se ve ordenado
 Lo abriste en navegador