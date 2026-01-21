# valentines
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Will You Be My Valentine?</title>
  <style>
    body {
      margin: 0;
      font-family: 'Arial', sans-serif;
      background: linear-gradient(135deg, #ffd6e8, #ffc0cb);
      text-align: center;
      color: #8b004f;
    }

    .container {
      padding: 40px 20px;
    }

    h1 {
      font-size: 3em;
      margin-bottom: 10px;
    }

    h2 {
      font-weight: normal;
    }

    .tulips {
      font-size: 3rem;
      margin: 20px 0;
    }

    .box {
      background: #fff0f6;
      border-radius: 20px;
      padding: 20px;
      max-width: 520px;
      margin: 30px auto;
      box-shadow: 0 8px 20px rgba(0,0,0,0.1);
    }

    p {
      font-size: 1.2em;
      margin: 10px 0;
    }

    button {
      background-color: #ff69b4;
      color: white;
      border: none;
      padding: 15px 30px;
      font-size: 1.2em;
      border-radius: 30px;
      cursor: pointer;
      margin: 15px;
      transition: transform 0.2s;
    }

    button:hover {
      transform: scale(1.1);
    }

    #response {
      font-size: 1.5em;
      margin-top: 20px;
      display: none;
    }

    iframe {
      border-radius: 12px;
      margin-top: 15px;
    }

    footer {
      margin-top: 40px;
      font-size: 0.9em;
      opacity: 0.8;
    }
  </style>
</head>
<body>

  <div class="container">
    <h1>Hey Love 💕</h1>
    <h2>I made this just for you</h2>

    <div class="tulips">🌷🌷🌷</div>

    <div class="box">
      <p>💖 Your favorite color: <strong>Pink</strong></p>
      <p>🌴 Watching <strong>Outer Banks</strong> together</p>
      <p>🎬 Loving <strong>On My Block</strong></p>
      <p>🌷 Tulips, because they remind me of you</p>
    </div>

    <div class="box">
      <h2>🎶 Songs That Make Me Think of You</h2>

      <p><strong>It Will Rain – Bruno Mars</strong></p>
      <iframe style="border:none;" 
        src="https://open.spotify.com/embed/track/6QpkI1hXHcib6TzN3aY6Z5"
        width="100%" height="80" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture">
      </iframe>

      <p><strong>Talking to the Moon – Bruno Mars</strong></p>
      <iframe style="border:none;" 
        src="https://open.spotify.com/embed/track/161DnLWsx1i3u1JT05lzqU"
        width="100%" height="80" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture">
      </iframe>
    </div>

    <h2>So I have one important question…</h2>

    <button onclick="sayYes()">Yes 💘</button>
    <button onclick="sayYes()">Obviously Yes 💞</button>

    <div id="response">
      💗 I’m so happy. You make me feel so lucky every day 💗
    </div>

    <footer>
      Made with all my love 💕
    </footer>
  </div>

  <script>
    function sayYes() {
      document.getElementById("response").style.display = "block";
    }
  </script>

</body>
</html>
