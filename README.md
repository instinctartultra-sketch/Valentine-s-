# Valentine-s- <!DOCTYPE html>
<html>
<head>
<title>Just For You ❤️</title>
<style>
body {
  margin: 0;
  padding: 0;
  overflow: hidden;
  font-family: Arial, sans-serif;
  background: radial-gradient(circle at top, #1a001f, #000000);
  color: white;
  text-align: center;
}

.container {
  position: relative;
  top: 50%;
  transform: translateY(-50%);
}

h1 {
  font-size: 28px;
  text-shadow: 0 0 15px #ff4da6;
}

p {
  font-size: 18px;
  margin: 20px;
}

button {
  padding: 12px 25px;
  margin: 10px;
  border: none;
  border-radius: 30px;
  font-size: 16px;
  cursor: pointer;
  transition: 0.3s;
}

.yes {
  background: #ff0066;
  color: white;
  box-shadow: 0 0 15px #ff0066;
}

.no {
  background: #444;
  color: white;
  position: absolute;
}

button:hover {
  transform: scale(1.1);
}

#loveMessage {
  display: none;
  font-size: 22px;
  margin-top: 20px;
  text-shadow: 0 0 10px #ff66cc;
}

/* Floating Hearts */
.heart {
  position: absolute;
  color: #ff4da6;
  animation: float 6s linear infinite;
  font-size: 20px;
}

@keyframes float {
  from { transform: translateY(100vh); opacity: 1; }
  to { transform: translateY(-10vh); opacity: 0; }
}
</style>
</head>

<body>

<audio autoplay loop>
  <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg">
</audio>

<div class="container">
  <h1>🌹 Hey... This Is For You 🌹</h1>
  <p>
    In this big world...  
    You somehow became my favorite person.  
    Every smile of yours feels special to me.  
  </p>

  <h2>Will you be my Valentine? ❤️</h2>

  <button class="yes" onclick="showLove()">💖 YES</button>
  <button class="no" onmouseover="moveButton(this)">🙈 No</button>

  <div id="loveMessage">
    💕 You just made me the happiest person alive! 💕  
  </div>
</div>

<script>
function showLove() {
  document.getElementById("loveMessage").style.display = "block";
  for (let i = 0; i < 30; i++) {
    let heart = document.createElement("div");
    heart.className = "heart";
    heart.innerHTML = "❤️";
    heart.style.left = Math.random() * 100 + "vw";
    heart.style.animationDuration = (Math.random() * 3 + 3) + "s";
    document.body.appendChild(heart);
  }
}

function moveButton(button) {
  button.style.top = Math.random() * window.innerHeight + "px";
  button.style.left = Math.random() * window.innerWidth + "px";
}
</script>

</body>
</html><!DOCTYPE html>
<html>
<head>
<title>Just For You ❤️</title>
<style>
body {
  margin: 0;
  padding: 0;
  overflow: hidden;
  font-family: Arial, sans-serif;
  background: radial-gradient(circle at top, #1a001f, #000000);
  color: white;
  text-align: center;
}

.container {
  position: relative;
  top: 50%;
  transform: translateY(-50%);
}

h1 {
  font-size: 28px;
  text-shadow: 0 0 15px #ff4da6;
}

p {
  font-size: 18px;
  margin: 20px;
}

button {
  padding: 12px 25px;
  margin: 10px;
  border: none;
  border-radius: 30px;
  font-size: 16px;
  cursor: pointer;
  transition: 0.3s;
}

.yes {
  background: #ff0066;
  color: white;
  box-shadow: 0 0 15px #ff0066;
}

.no {
  background: #444;
  color: white;
  position: absolute;
}

button:hover {
  transform: scale(1.1);
}

#loveMessage {
  display: none;
  font-size: 22px;
  margin-top: 20px;
  text-shadow: 0 0 10px #ff66cc;
}

/* Floating Hearts */
.heart {
  position: absolute;
  color: #ff4da6;
  animation: float 6s linear infinite;
  font-size: 20px;
}

@keyframes float {
  from { transform: translateY(100vh); opacity: 1; }
  to { transform: translateY(-10vh); opacity: 0; }
}
</style>
</head>

<body>

<audio autoplay loop>
  <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg">
</audio>

<div class="container">
  <h1>🌹 Hey... This Is For You 🌹</h1>
  <p>
    In this big world...  
    You somehow became my favorite person.  
    Every smile of yours feels special to me.  
  </p>

  <h2>Will you be my Valentine? ❤️</h2>

  <button class="yes" onclick="showLove()">💖 YES</button>
  <button class="no" onmouseover="moveButton(this)">🙈 No</button>

  <div id="loveMessage">
    💕 You just made me the happiest person alive! 💕  
  </div>
</div>

<script>
function showLove() {
  document.getElementById("loveMessage").style.display = "block";
  for (let i = 0; i < 30; i++) {
    let heart = document.createElement("div");
    heart.className = "heart";
    heart.innerHTML = "❤️";
    heart.style.left = Math.random() * 100 + "vw";
    heart.style.animationDuration = (Math.random() * 3 + 3) + "s";
    document.body.appendChild(heart);
  }
}

function moveButton(button) {
  button.style.top = Math.random() * window.innerHeight + "px";
  button.style.left = Math.random() * window.innerWidth + "px";
}
</script>

</body>
</html>
