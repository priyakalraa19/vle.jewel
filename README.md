# vle.jewel
<!-- index.html -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>VLE — Coming Soon</title>
  <link rel="stylesheet" href="style.css">
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@600&family=Roboto&display=swap" rel="stylesheet">
</head>
<body>
  <div class="container">
    <h1 class="logo">VLE</h1>
    <p class="tagline">Your Style, Your Story</p>
    <p class="coming-soon">COMING SOON</p>
    <div class="glow"></div>
  </div>
</body>
</html>
/* style.css */
body {
  margin: 0;
  padding: 0;
  font-family: 'Orbitron', sans-serif;
  background: linear-gradient(135deg, #000000, #1a1a1a);
  color: gold;
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  overflow: hidden;
}

.container {
  text-align: center;
  position: relative;
  z-index: 2;
}

.logo {
  font-size: 60px;
  letter-spacing: 10px;
  color: gold;
  animation: pulse 3s infinite;
}

.tagline {
  font-family: 'Roboto', sans-serif;
  font-size: 18px;
  margin-top: -10px;
  color: #ddd;
}

.coming-soon {
  margin-top: 30px;
  font-size: 32px;
  letter-spacing: 4px;
  color: white;
  animation: flicker 2s infinite;
}

@keyframes flicker {
  0%, 100% { opacity: 1; }
  50% { opacity: 0.4; }
}

@keyframes pulse {
  0%, 100% { transform: scale(1); }
  50% { transform: scale(1.1); }
}

.glow {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: radial-gradient(circle at center, rgba(255,215,0,0.1), transparent);
  z-index: 1;
}
// script.js
// (Optional) You can add interactivity or animation here later