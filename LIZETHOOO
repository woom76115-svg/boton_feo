<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Modo Claro / Oscuro</title>

<style>
  body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 20px;
    transition: background 0.3s, color 0.3s;
    background: #aeebb3;
    color: #578a5b;
  }

  body.dark {
    background: #263625;
    color: #76ab6a;
  }

  .toggle-btn {
    background: none;
    border: none;
    cursor: pointer;
    font-size: 34px;
    transition: transform 0.3s ease;
  }

  .toggle-btn:hover {
    transform: scale(1.15);
  }

  /* Posición opcional si lo quieres en una esquina */
  .toggle-container {
    position: fixed;
    top: 20px;
    right: 20px;
  }
</style>

</head>
<body>

<div class="toggle-container">
  <button class="toggle-btn" id="themeToggle">☀︎</button>
</div>

<script>
  const btn = document.getElementById("themeToggle");

  btn.addEventListener("click", () => {
    document.body.classList.toggle("dark");

    if (document.body.classList.contains("dark")) {
      btn.textContent = "⏾"; // luna en modo oscuro
    } else {
      btn.textContent = "☀︎"; // sol en modo claro
    }
  });
</script>

</body>
</html>
