<!DOCTYPE html>
<html>
<head>
  <title>Fighter Jet Command</title>

  <style>
    body {
      text-align: center;
      background: linear-gradient(#0a0f1c, #1c2e4a);
      color: #00ffcc;
      font-family: Arial, sans-serif;
      margin: 0;
    }

    h1 {
      font-size: 50px;
      text-shadow: 0 0 10px #00ffcc;
      margin-top: 20px;
    }

    .jet {
      background: rgba(0,0,0,0.6);
      border: 1px solid #00ffcc;
      margin: 20px;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 0 15px #00ffcc;
    }

    img {
      width: 300px;
      border-radius: 10px;
      margin-top: 10px;
    }

    button {
      background: black;
      color: #00ffcc;
      border: 1px solid #00ffcc;
      padding: 10px 20px;
      margin-top: 10px;
      cursor: pointer;
    }

    button:hover {
      background: #00ffcc;
      color: black;
    }

    .hud-line {
      width: 100%;
      height: 2px;
      background: #00ffcc;
      margin: 10px 0;
      animation: scan 2s infinite;
    }

    @keyframes scan {
      0% {opacity: 0;}
      50% {opacity: 1;}
      100% {opacity: 0;}
    }
  </style>
</head>

<body>

<h1>✈️ Fighter Jet Command</h1>
<div class="hud-line"></div>

<div class="jet">
  <h2>F-22 Raptor</h2>
  <p>Stealth air superiority fighter.</p>
  <img src="https://upload.wikimedia.org/wikipedia/commons/3/3e/F-22_Raptor_edit1_%28cropped%29.jpg">
  <br>
  <button onclick="alert('Speed: Mach 2.25 🚀')">View Stats</button>
</div>

<div class="jet">
  <h2>F-35 Lightning II</h2>
  <p>Advanced stealth multi-role fighter.</p>
  <img src="https://upload.wikimedia.org/wikipedia/commons/2/2e/F-35A_flight_%28cropped%29.jpg">
  <br>
  <button onclick="alert('Stealth Mode Activated ⚡')">Activate Mode</button>
</div>

<div class="jet">
  <h2>F-16 Fighting Falcon</h2>
  <p>Highly agile multi-role jet.</p>
  <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/F-16_June_2008.jpg">
  <br>
  <button onclick="alert('Agility: Extreme 💨')">Check Agility</button>
</div>

<div class="jet">
  <h2>F-15 Eagle</h2>
  <p>Air superiority fighter with unmatched combat record.</p>
  <img src="https://upload.wikimedia.org/wikipedia/commons/0/0f/F-15C_Eagle.jpg">
  <br>
  <button onclick="alert('Kills: 100+ 🏆')">Combat Record</button>
</div>

<div class="jet">
  <h2>F/A-18 Hornet</h2>
  <p>Carrier-based multi-role fighter.</p>
  <img src="https://upload.wikimedia.org/wikipedia/commons/2/2a/FA-18_Hornet.jpg">
  <br>
  <button onclick="alert('Carrier Ready ⚓')">Launch Mode</button>
</div>

<div class="jet">
  <h2>F-14 Tomcat</h2>
  <p>Famous naval interceptor with swing wings.</p>
  <img src="https://upload.wikimedia.org/wikipedia/commons/2/2e/F-14A_Tomcat.jpg">
  <br>
  <button onclick="alert('Top Gun Mode 🎬')">Engage</button>
</div>

<div class="jet">
  <h2>Dassault Rafale</h2>
  <p>French omnirole fighter.</p>
  <img src="https://upload.wikimedia.org/wikipedia/commons/0/0c/Rafale_Marine.jpg">
  <br>
  <button onclick="alert('Systems: Fully Operational 🎯')">System Check</button>
</div>

<div class="jet">
  <h2>Mirage 2000</h2>
  <p>Lightweight French delta-wing fighter.</p>
  <img src="https://upload.wikimedia.org/wikipedia/commons/4/4e/Mirage_2000.jpg">
  <br>
  <button onclick="alert('Delta Wing Engaged 🔺')">Flight Mode</button>
</div>

<div class="jet">
  <h2>Eurofighter Typhoon</h2>
  <p>Advanced European air superiority fighter.</p>
  <img src="https://upload.wikimedia.org/wikipedia/commons/0/0e/Eurofighter_Typhoon.jpg">
  <br>
  <button onclick="alert('Supercruise Enabled ⚡')">Boost</button>
</div>

<div class="jet">
  <h2>Su-57 Felon</h2>
  <p>Russia's stealth fighter.</p>
  <img src="https://upload.wikimedia.org/wikipedia/commons/5/5d/Sukhoi_Su-57_in_flight.jpg">
  <br>
  <button onclick="alert('Weapons System Online 💥')">Arm Weapons</button>
</div>

</body>
</html>
