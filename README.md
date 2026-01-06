<!-- ================= index.html ================= --><!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Personal Website</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, sans-serif;
      background: radial-gradient(circle at top, #0f2027, #000000 70%);
      color: #e5e5e5;
      overflow-x: hidden;
    }
    /* Animated stars background */
    .stars, .stars::after {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: transparent;
      box-shadow: 2px 3px #00ffcc, 100px 200px #00ffcc, 300px 150px #00ffcc,
                  500px 400px #00ffcc, 700px 100px #00ffcc, 900px 300px #00ffcc;
      animation: moveStars 60s linear infinite;
      z-index: -1;
      opacity: 0.4;
    }
    .stars::after {
      content: "";
      box-shadow: 50px 80px #00ffcc, 250px 350px #00ffcc, 450px 50px #00ffcc,
                  650px 250px #00ffcc, 850px 150px #00ffcc;
      animation-duration: 120s;
    }
    @keyframes moveStars {
      from { transform: translateY(0); }
      to { transform: translateY(-1000px); }
    }
    header {
      padding: 20px;
      text-align: center;
      background: linear-gradient(90deg, #000000, #1a1a1a);
      border-bottom: 2px solid #00ffcc;
    }
    header h2 {
      letter-spacing: 2px;
      color: #00ffcc;
    }
    nav a {
      color: #e5e5e5;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      color: #00ffcc;
    }
    .container {
      padding: 70px 20px;
      text-align: center;
    }
    h1 {
      font-size: 50px;
      color: #00ffcc;
      text-shadow: 0 0 15px rgba(0, 255, 204, 0.6);
    }
    h2 {
      color: #00ffcc;
      margin-top: 40px;
    }
    p {
      font-size: 18px;
      max-width: 700px;
      margin: 0 auto 30px;
      line-height: 1.7;
    }
    ul {
      list-style: none;
      padding: 0;
    }
    ul li::before {
      content: "▶ ";
      color: #00ffcc;
    }
    .button {
      display: inline-block;
      padding: 14px 30px;
      background: #00ffcc;
      color: #000;
      border-radius: 30px;
      text-decoration: none;
      font-weight: bold;
      box-shadow: 0 0 20px rgba(0, 255, 204, 0.6);
    }
    .button:hover {
      background: #00cca3;
      box-shadow: 0 0 30px rgba(0, 255, 204, 0.9);
    }
    footer {
      text-align: center;
      padding: 15px;
      background: #000000;
      border-top: 2px solid #00ffcc;
      color: #888;
    }
  </style>
</head>
<body>
  <div class="stars"></div>
  <header>
    <h2>My Website</h2>
    <nav>
      <a href="index.html">Home</a>
      <a href="about.html">About Me</a>
    </nav>
  </header>  <div class="container">
    <h1>Who Am I?</h1>
    <p>
      My name is Yousef. I am passionate about technology, games, and creating
      things on the internet. I like learning by doing.
    </p><h2>My Skills</h2>
<div style="max-width:600px;margin:30px auto;text-align:left;">
  <p>Gaming</p>
  <div style="background:#222;border-radius:20px;overflow:hidden;">
    <div style="width:85%;background:#00ffcc;padding:8px 0;"></div>
  </div>

  <p style="margin-top:15px;">Web Design</p>
  <div style="background:#222;border-radius:20px;overflow:hidden;">
    <div style="width:70%;background:#00ffcc;padding:8px 0;"></div>
  </div>

  <p style="margin-top:15px;">Creativity</p>
  <div style="background:#222;border-radius:20px;overflow:hidden;">
    <div style="width:75%;background:#00ffcc;padding:8px 0;"></div>
  </div>
</div>

<h2>Gaming Profile</h2>
<div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:20px;margin-top:30px;">
  <div style="background:#111;border:1px solid #00ffcc;border-radius:15px;padding:20px;box-shadow:0 0 20px rgba(0,255,204,0.3);">
    <h3 style="color:#00ffcc;">Favorite Games</h3>
    <p>Fortnite<br>Call of Duty<br>Roblox<br>FIFA</p>
  </div>
  <div style="background:#111;border:1px solid #00ffcc;border-radius:15px;padding:20px;box-shadow:0 0 20px rgba(0,255,204,0.3);">
    <h3 style="color:#00ffcc;">Play Style</h3>
    <p>Competitive<br>Team Player<br>Strategic</p>
  </div>
  <div style="background:#111;border:1px solid #00ffcc;border-radius:15px;padding:20px;box-shadow:0 0 20px rgba(0,255,204,0.3);">
    <h3 style="color:#00ffcc;">Gaming Goals</h3>
    <p>Improve skills<br>Rank up<br>Join tournaments</p>
  </div>
</div>

  </div>
  </div>  <footer>
    © 2026 Yousef
  </footer>
</body>
</html><!-- ================= about.html ================= --><!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>About Me</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, sans-serif;
      background: radial-gradient(circle at top, #0f2027, #000000 70%);
      color: #e5e5e5;
      overflow-x: hidden;
    }
    /* Animated stars background */
    .stars, .stars::after {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: transparent;
      box-shadow: 2px 3px #00ffcc, 100px 200px #00ffcc, 300px 150px #00ffcc,
                  500px 400px #00ffcc, 700px 100px #00ffcc, 900px 300px #00ffcc;
      animation: moveStars 60s linear infinite;
      z-index: -1;
      opacity: 0.4;
    }
    .stars::after {
      content: "";
      box-shadow: 50px 80px #00ffcc, 250px 350px #00ffcc, 450px 50px #00ffcc,
                  650px 250px #00ffcc, 850px 150px #00ffcc;
      animation-duration: 120s;
    }
    @keyframes moveStars {
      from { transform: translateY(0); }
      to { transform: translateY(-1000px); }
    }
    header {
      padding: 20px;
      text-align: center;
      background: linear-gradient(90deg, #000000, #1a1a1a);
      border-bottom: 2px solid #00ffcc;
    }
    header h2 {
      letter-spacing: 2px;
      color: #00ffcc;
    }
    nav a {
      color: #e5e5e5;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      color: #00ffcc;
    }
    .container {
      padding: 70px 20px;
      text-align: center;
    }
    h1 {
      font-size: 50px;
      color: #00ffcc;
      text-shadow: 0 0 15px rgba(0, 255, 204, 0.6);
    }
    h2 {
      color: #00ffcc;
      margin-top: 40px;
    }
    p {
      font-size: 18px;
      max-width: 700px;
      margin: 0 auto 30px;
      line-height: 1.7;
    }
    ul {
      list-style: none;
      padding: 0;
    }
    ul li::before {
      content: "▶ ";
      color: #00ffcc;
    }
    .button {
      display: inline-block;
      padding: 14px 30px;
      background: #00ffcc;
      color: #000;
      border-radius: 30px;
      text-decoration: none;
      font-weight: bold;
      box-shadow: 0 0 20px rgba(0, 255, 204, 0.6);
    }
    .button:hover {
      background: #00cca3;
      box-shadow: 0 0 30px rgba(0, 255, 204, 0.9);
    }
    footer {
      text-align: center;
      padding: 15px;
      background: #000000;
      border-top: 2px solid #00ffcc;
      color: #888;
    }
  </style>
</head>
<body>
  <div class="stars"></div>
  <header>
    <h2>About Me</h2>
    <nav>
      <a href="index.html">Home</a>
      <a href="about.html">About Me</a>
    </nav>
  </header>  <div class="container">
    <h1>Who Am I?</h1>
    <p>
      My name is Yousef. I am passionate about technology, games, and
      learning new things.
    </p><h2>My Interests</h2>
<ul>
  <li>Gaming</li>
  <li>Web Design</li>
  <li>Music</li>
  <li>Learning new skills</li>
</ul>

  </div>  <footer>
    © 2026 Yousef
  </footer>
</body>
</html>
