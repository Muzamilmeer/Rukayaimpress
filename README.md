
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Forever Yours – Rukaya & Muzamil</title>
  <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Poppins&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(to right, #ffdde1, #ee9ca7);
      color: #333;
      scroll-behavior: smooth;
    }

    header {
      text-align: center;
      padding: 3rem;
      background-color: rgba(255, 255, 255, 0.2);
      backdrop-filter: blur(5px);
    }

    h1 {
      font-family: 'Great Vibes', cursive;
      font-size: 3.5rem;
      color: #e60073;
    }

    p.quote {
      font-size: 1.2rem;
      font-style: italic;
    }

    section {
      padding: 3rem;
      max-width: 800px;
      margin: auto;
    }

    .timeline {
      border-left: 3px solid #e60073;
      padding-left: 1rem;
      position: relative;
    }

    .timeline::before {
      content: '';
      position: absolute;
      left: -9px;
      top: 0;
      width: 15px;
      height: 15px;
      background: #e60073;
      border-radius: 50%;
    }

    .timeline p {
      margin: 1rem 0;
    }

    .surprise {
      text-align: center;
      margin-top: 2rem;
    }

    .btn {
      padding: 1rem 2rem;
      background-color: #e60073;
      color: white;
      border: none;
      border-radius: 25px;
      font-size: 1rem;
      cursor: pointer;
      transition: background 0.3s ease;
    }

    .btn:hover {
      background-color: #c4005a;
    }

    footer {
      text-align: center;
      padding: 2rem;
      font-size: 0.9rem;
      color: #666;
    }

    #popup {
      display: none;
      position: fixed;
      top: 30%;
      left: 50%;
      transform: translate(-50%, -50%);
      background: white;
      padding: 2rem;
      border-radius: 10px;
      box-shadow: 0px 0px 20px rgba(0, 0, 0, 0.2);
      z-index: 100;
    }

    #popup p {
      font-size: 1.3rem;
      color: #e60073;
    }

    #overlay {
      display: none;
      position: fixed;
      top: 0; left: 0;
      width: 100%;
      height: 100%;
      background: rgba(0, 0, 0, 0.4);
      z-index: 99;
    }

    audio {
      display: none;
    }
  </style>
</head>
<body>

  <header>
    <h1>Forever Yours</h1>
    <p class="quote">"From a conference call to forever – our journey is written in the stars."</p>
  </header>

  <section>
    <h2>Our Story</h2>
    <div class="timeline">
      <p>📞 First call during Rukaya's breakup</p>
      <p>🤝 Friendship that became special</p>
      <p>💖 Love bloomed – 1 year 3 months strong</p>
      <p>🫶 Still going strong, forever to go...</p>
    </div>

    <div class="surprise">
      <button class="btn" onclick="showPopup()">Click for a Surprise 💌</button>
    </div>
  </section>

  <div id="overlay" onclick="hidePopup()"></div>
  <div id="popup">
    <p>Rukaya, you are the reason behind Muzamil's smile 💫</p>
  </div>

  <footer>
    Made with 💕 by Muzamil | For Rukaya Only
  </footer>

  <!-- Romantic Background Music -->
  <audio autoplay loop>
    <source src="https://res.cloudinary.com/dxjkbpmgm/image/upload/v1744658409/Picsart_25-04-14_00-56-51-907_ztwdk2.jpg" type="https://voca.ro/1gTT0pHu0Nr7">
    Your browser does not support the audio element.
  </audio>

  <script>
    function showPopup() {
      document.getElementById('popup').style.display = 'block';
      document.getElementById('overlay').style.display = 'block';
    }

    function hidePopup() {
      document.getElementById('popup').style.display = 'none';
      document.getElementById('overlay').style.display = 'none';
    }
  </script>
</body>
</html>
