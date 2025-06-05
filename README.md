<h1 align="center">Hola 👋, soy Laura 💖</h1>
<h3 align="center">Apasionada por la tecnología, la robótica y el desarrollo de software</h3>

<div align="center">
  <img src="https://media.giphy.com/media/UqZqFu1qFJgk8/giphy.gif" width="300px" />
</div>

---

### 💻 Tecnologías y Lenguajes que uso

<p align="center">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue" />
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=STMicroelectronics&logoColor=white" />
  <img src="https://img.shields.io/badge/Bash-121011?style=for-the-badge&logo=gnu-bash&logoColor=white" />
</p>

---

### 🌸 Un poco sobre mí

- 🎓 Estudiante de ingeniería de telecomunicaciones, amante de la programación y la electrónica.
- 🤖 Actualmente trabajando con el robot **Pepper** y proyectos de **redes híbridas con QEMU y Docker**.
- 📚 Aprendiendo más sobre **procesamiento digital de señales**, **sistemas operativos**, y **medios de transmision**.
- 🌱 Explorando nuevas tecnologías como **IoT, Grafana, Zabbix y redes GPON**.
- 💻 Me encanta usar **Linux** para mis desarrollos y trabajar en la consola con **Nano** 💕

---

### 💌 Conectemos

<p align="center">
  <a href="mailto:laurab5604@example.com"><img src="https://img.shields.io/badge/email-FF69B4?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/tu-perfil"><img src="https://img.shields.io/badge/LinkedIn-ffb6c1?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://github.com/laurab5604"><img src="https://img.shields.io/badge/GitHub-daa6d4?style=for-the-badge&logo=github&logoColor=white" /></a>
</p>

---

### 🧠 Stats y actividad

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=laurab5604&show_icons=true&theme=pink" height="165px"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=laurab5604&layout=compact&theme=pink" height="165px"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=laurab5604&theme=pink" height="150px"/>
</p>

---

🌷 *Gracias por visitar mi perfil, ¡sigue tus sueños y nunca dejes de aprender!* 💫

---

<h2 align="center">🎮 Juego: Adivina el Número</h2>

<p align="center">¡Intenta adivinar el número entre 1 y 20! Tienes 5 intentos.</p>

<div align="center">
  <input type="number" id="guessInput" placeholder="Escribe un número" style="padding:5px; font-size:16px;" />
  <button onclick="checkGuess()" style="padding:5px 10px; font-size:16px; cursor:pointer;">Probar</button>
</div>

<p align="center" id="resultMessage" style="font-weight:bold; margin-top:10px;"></p>

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

  <a href="mailto:laurab5604@example.com"><img src="https://img.shields.io/badge/email-FF69B4?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/tu-perfil"><img src="https://img.shields.io/badge/LinkedIn-ffb6c1?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://github.com/laurab5604"><img src="https://img.shields.io/badge/GitHub-daa6d4?style=for-the-badge&logo=github&logoColor=white" /></a>
</p>

---

### 🧠 Stats y actividad

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=laurab5604&show_icons=true&theme=pink" height="165px"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=laurab5604&layout=compact&theme=pink" height="165px"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=laurab5604&theme=pink" height="150px"/>
</p>

---

🌷 *Gracias por visitar mi perfil, ¡sigue tus sueños y nunca dejes de aprender!* 💫

