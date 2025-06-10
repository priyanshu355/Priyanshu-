<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Priyanshu Chauragade</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      color: #fff;
      text-align: center;
      background-image: url('https://images.unsplash.com/photo-1503264116251-35a269479413?auto=format&fit=crop&w=1600&q=80');
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
      min-height: 100vh;
      padding: 20px;
      animation: fadeInBody 2s ease-in;
    }

    @keyframes fadeInBody {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    h1 {
      font-size: 40px;
      margin-top: 40px;
      text-shadow: 2px 2px 5px #000;
      animation: slideDown 1s ease;
    }

    h2 {
      font-size: 28px;
      margin-bottom: 20px;
      text-shadow: 1px 1px 4px #000;
      animation: slideUp 1s ease;
    }

    @keyframes slideDown {
      from { transform: translateY(-50px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }

    @keyframes slideUp {
      from { transform: translateY(50px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }

    p {
      font-size: 18px;
      padding: 0 10%;
      text-shadow: 1px 1px 3px #000;
      animation: fadeInText 2s ease;
    }

    @keyframes fadeInText {
      0% { opacity: 0; }
      100% { opacity: 1; }
    }

    img {
      width: 200px;
      height: 200px;
      object-fit: cover;
      border-radius: 50%;
      border: 5px solid #fff;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.5);
      margin: 20px 0;
      animation: zoomIn 1.5s ease;
    }

    @keyframes zoomIn {
      from { transform: scale(0.5); opacity: 0; }
      to { transform: scale(1); opacity: 1; }
    }

    .button {
      margin: 10px;
      background-color: #3498db;
      border: none;
      color: white;
      padding: 12px 25px;
      font-size: 16px;
      border-radius: 30px;
      cursor: pointer;
      transition: background-color 0.3s ease, transform 0.2s;
      box-shadow: 0 3px 8px rgba(0,0,0,0.3);
      text-decoration: none;
      display: inline-block;
      animation: fadeInText 2s ease;
    }

    .button:hover {
      background-color: #2980b9;
      transform: scale(1.05);
    }

    footer {
      margin-top: 40px;
      font-size: 14px;
      color: #eee;
      text-shadow: 1px 1px 3px #000;
      animation: fadeInText 2s ease;
    }
  </style>
</head>
<body>

  <h1>👋 Welcome to My Stylish Page</h1>
  <h2>✨ Priyanshu Chauragade ✨</h2>

  <p>
    Hello! I am <strong>Priyanshu Chauragade</strong>.<br>
    I'm passionate about <em>coding, creativity, and technology</em>.<br>
    This is my stylish HTML web page made with ❤️.
  </p>

  <!-- Web Page Button -->
  <a href="https://priyanshudesigning.blogspot.com" target="_blank" class="button">
    🌐 Visit My Web Page
  </a>

  <!-- Instagram Button -->
  <a href="https://www.instagram.com/priyanshu_i2010" target="_blank" class="button">
    📸 Follow on Instagram
  </a>

  <p>📧 Email: priyanshu@example.com</p>

  <h2>----ABOUT ME-----</h2>

  <p>
    MY NAME IS PRIYANSHU CHAURAGADE.<br>
    I AM NCC X CADET, A 11TH CLASS STUDENT AT GOVT HIGHER SECONDARY SCHOOL RAMAKONA ❤️‍🩹.<br>
    I LOVE INDIAN ARMY 🪖🪖
  </p>
<body>

<body>

  <!-- Music Control Button -->
<audio id="bgMusic" autoplay loop>
  <source src="https://www.bensound.com/bensound-music/bensound-sunny.mp3" type="audio/mpeg">
</audio>

<button onclick="toggleMusic()" id="musicButton" class="music-btn">🔊 Pause Music</button>

<script>
  const music = document.getElementById("bgMusic");
  const btn = document.getElementById("musicButton");

  function toggleMusic() {
    if (music.paused) {
      music.play();
      btn.textContent = "🔊 Pause Music";
    } else {
      music.pause();
      btn.textContent = "🔈 Play Music";
    }
  }
</script>

<style>
  .music-btn {
    background: linear-gradient(45deg, #ff416c, #ff4b2b);
    border: none;
    padding: 14px 30px;
    color: white;
    font-size: 18px;
    font-weight: bold;
    border-radius: 50px;
    cursor: pointer;
    box-shadow: 0 0 15px rgba(255, 65, 108, 0.6);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    animation: pulse 2s infinite;
    margin-top: 20px;
  }

  .music-btn:hover {
    transform: scale(1.08);
    box-shadow: 0 0 25px rgba(255, 75, 43, 0.9);
  }

  @keyframes pulse {
    0% {
      box-shadow: 0 0 15px rgba(255, 65, 108, 0.6);
    }
    50% {
      box-shadow: 0 0 30px rgba(255, 75, 43, 0.9);
    }
    100% {
      box-shadow: 0 0 15px rgba(255, 65, 108, 0.6);
    }
  }
 
</style> 
<h3>Tap Music Button</h3>
  <!-- Rest of your content below... -->

  <h1>👋 Welcome to My Stylish Page</h1>
  <h2>✨ Priyanshu Chauragade ✨</h2>

  <!-- (Baaki code same rahega) -->

</body>
  <footer>
    © 2025 Priyanshu Chauragade 💖🧿💖
  </footer>

</body>
</html>
