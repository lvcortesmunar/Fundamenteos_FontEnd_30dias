🟢 DÍA 6 — FLEXBOX
🎯 Objetivo

Alinear elementos correctamente.

🧠 Introducción

Flexbox sirve para:

ordenar elementos en línea

💻 Código completo
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Dia 6</title>

  <style>
    .container {
      display: flex;
      justify-content: space-around;
    }

    .box {
      background: lightblue;
      padding: 20px;
    }
  </style>

</head>
<body>

<div class="container">
  <div class="box">1</div>
  <div class="box">2</div>
  <div class="box">3</div>
</div>

</body>
</html>
✅ Checklist
 Los elementos están en fila
 Hay espacio entre ellos
 Probaste cambiar justify-content