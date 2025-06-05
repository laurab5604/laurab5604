<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <title>Perfil Laura + Juego</title>
  <style>
    body { font-family: Arial, sans-serif; background: #fff0f6; color: #333; max-width: 700px; margin: 20px auto; padding: 20px; }
    h1, h3, h2 { text-align: center; }
    p, ul { font-size: 1.1rem; }
    .center { text-align: center; }
    button { padding: 8px 15px; font-size: 16px; cursor: pointer; background: #ff69b4; color: white; border: none; border-radius: 5px;}
    input { font-size: 16px; padding: 6px; width: 150px; }
  </style>
</head>
<body>

<h1>Hola 👋, soy Laura 💖</h1>
<h3>Apasionada por la tecnología, la robótica y el desarrollo de software</h3>

<div class="center">
  <img src="https://media.giphy.com/media/UqZqFu1qFJgk8/giphy.gif" width="300" alt="Giphy animado" />
</div>

<hr />

<h3>💻 Tecnologías y Lenguajes que uso</h3>
<div class="center">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue" />
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=STMicroelectronics&logoColor=white" />
  <img src="https://img.shields.io/badge/Bash-121011?style=for-the-badge&logo=gnu-bash&logoColor=white" />
</div>

<hr />

<h3>🌸 Un poco sobre mí</h3>
<ul>
  <li>🎓 Estudiante de ingeniería de telecomunicaciones, amante de la programación y la electrónica.</li>
  <li>🤖 Actualmente trabajando con el robot <b>Pepper</b> y proyectos de <b>redes híbridas con QEMU y Docker</b>.</li>
  <li>📚 Aprendiendo más sobre <b>procesamiento digital de señales</b>, <b>sistemas operativos</b> y <b>medios de transmision</b>.</li>
  <li>🌱 Explorando nuevas tecnologías como <b>IoT, Grafana, Zabbix y redes GPON</b>.</li>
  <li>💻 Me encanta usar <b>Linux</b> para mis desarrollos y trabajar en la consola con <b>Nano</b> 💕</li>
</ul>

<hr />

<h3>💌 Conectemos</h3>
<div class="center">
  <a href="mailto:laurab5604@example.com"><img src="https://img.shields.io/badge/email-FF69B4?style=for-the-badge&logo=gmail&logoColor=white" alt="email"/></a>
  <a href="https://www.linkedin.com/in/tu-perfil"><img src="https://img.shields.io/badge/LinkedIn-ffb6c1?style=for-the-badge&logo=linkedin&logoColor=white" alt="linkedin"/></a>
  <a href="https://github.com/laurab5604"><img src="https://img.shields.io/badge/GitHub-daa6d4?style=for-the-badge&logo=github&logoColor=white" alt="github"/></a>
</div>

<hr />

<h3 class="center">🧠 Stats y actividad</h3>
<div class="center">
  <img src="https://github-readme-stats.vercel.app/api?username=laurab5604&show_icons=true&theme=pink" height="165" alt="stats"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=laurab5604&layout=compact&theme=pink" height="165" alt="top langs"/>
</div>
<div class="center" style="margin-top:15px;">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=laurab5604&theme=pink" height="150" alt="streak"/>
</div>

<hr />

<h2 class="center">🎮 Juego: Adivina el Número</h2>
<p class="center">¡Intenta adivinar el número entre 1 y 20! Tienes 5 intentos.</p>

<div class="center" style="margin-bottom: 10px;">
  <input type="number" id="guessInput" placeholder="Escribe un número" />
  <button onclick="checkGuess()">Probar</button>
</div>

<p class="center" id="resultMessage" style="font-weight: bold;"></p>

<script>
  let numeroSecreto = Math.floor(Math.random() * 20) + 1;
  let intentos = 5;

  function checkGuess() {
    let guess = parseInt(document.getElementById('guessInput').value);
    let resultMessage = document.getElementById('resultMessage');

    if (!guess || guess < 1 || guess > 20) {
      resultMessage.textContent = "Por favor, ingresa un número entre 1 y 20.";
      return;
    }

    intentos--;

    if (guess === numeroSecreto) {
      resultMessage.textContent = `🎉 ¡Felicidades! Adivinaste el número secreto (${numeroSecreto}).`;
      resetGame();
    } else if (intentos > 0) {
      resultMessage.textContent = `❌ Incorrecto. Te quedan ${intentos} intento(s). Intenta un número ${guess < numeroSecreto ? "mayor" : "menor"}.`;
    } else {
      resultMessage.textContent = `😢 Se acabaron los intentos. El número era ${numeroSecreto}. ¡Intenta de nuevo!`;
      resetGame();
    }
  }

  function resetGame() {
    numeroSecreto = Math.floor(Math.random() * 20) + 1;
    intentos = 5;
    document.getElementById('guessInput').value = "";
  }
</script>

<footer style="text-align:center; margin-top:30px;">
  🌷 <em>Gracias por visitar mi perfil, ¡sigue tus sueños y nunca dejes de aprender! 💫</em>
</footer>

</body>
</html>
