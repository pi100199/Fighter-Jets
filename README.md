<!DOCTYPE html>
<html>
<head>
  <title>Fighter Jet Command</title>

  <style>
    body {
      background: linear-gradient(#0a0f1c, #1c2e4a);
      color: #00ffcc;
      font-family: Arial, sans-serif;
      margin: 0;
    }

    h1 {
      text-align: center;
      font-size: 50px;
      text-shadow: 0 0 15px #00ffcc;
      padding: 20px;
    }

    .container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
    }

    .jet {
      background: rgba(0,0,0,0.7);
      border: 1px solid #00ffcc;
      margin: 20px;
      padding: 15px;
      border-radius: 15px;
      width: 350px;
      box-shadow: 0 0 20px #00ffcc;
      transition: transform 0.3s;
    }

    .jet:hover {
      transform: scale(1.05);
    }

    img {
      width: 100%;
      border-radius: 10px;
    }

    h2 {
      margin-top: 10px;
      text-shadow: 0 0 8px #00ffcc;
    }

    p {
      font-size: 14px;
      line-height: 1.5;
    }

    .stats {
      text-align: left;
      margin-top: 10px;
    }

    .stats p {
      margin: 5px 0;
    }

    button {
      width: 100%;
      margin-top: 10px;
      padding: 10px;
      background: black;
      color: #00ffcc;
      border: 1px solid #00ffcc;
      cursor: pointer;
    }

    button:hover {
      background: #00ffcc;
      color: black;
    }
  </style>
</head>

<body>

<h1>✈️ Fighter Jet Command Center</h1>

<div class="container">

  <!-- F-22 -->
  <div class="jet">
    <img src="https://upload.wikimedia.org/wikipedia/commons/3/3e/F-22_Raptor_edit1_%28cropped%29.jpg">
    <h2>F-22 Raptor</h2>
    <p>5th-generation stealth air superiority fighter used by the United States Air Force.</p>
    
    <div class="stats">
      <p><b>Speed:</b> Mach 2.25</p>
      <p><b>Range:</b> 2,960 km</p>
      <p><b>Role:</b> Air Superiority</p>
    </div>

    <button onclick="alert('Stealth Engaged 🚀')">Activate</button>
  </div>

  <!-- F-35 -->
  <div class="jet">
    <img src="https://upload.wikimedia.org/wikipedia/commons/2/2e/F-35A_flight_%28cropped%29.jpg">
    <h2>F-35 Lightning II</h2>
    <p>Advanced stealth multi-role fighter with cutting-edge avionics.</p>

    <div class="stats">
      <p><b>Speed:</b> Mach 1.6</p>
      <p><b>Range:</b> 2,200 km</p>
      <p><b>Role:</b> Multirole</p>
    </div>

    <button onclick="alert('Stealth Mode ⚡')">Activate</button>
  </div>

  <!-- F-16 -->
  <div class="jet">
    <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/F-16_June_2008.jpg">
    <h2>F-16 Fighting Falcon</h2>
    <p>Lightweight, highly maneuverable fighter used by many countries worldwide.</p>

    <div class="stats">
      <p><b>Speed:</b> Mach 2.0</p>
      <p><b>Range:</b> 4,200 km</p>
      <p><b>Role:</b> Multirole</p>
    </div>

    <button onclick="alert('Agility Boost 💨')">Activate</button>
  </div>

  <!-- F-15 -->
  <div class="jet">
    <img src="https://upload.wikimedia.org/wikipedia/commons/0/0f/F-15C_Eagle.jpg">
    <h2>F-15 Eagle</h2>
    <p>Legendary air superiority fighter with over 100 aerial victories.</p>

    <div class="stats">
      <p><b>Speed:</b> Mach 2.5</p>
      <p><b>Range:</b> 5,500 km</p>
      <p><b>Role:</b> Air Superiority</p>
    </div>

    <button onclick="alert('Combat Mode 🏆')">Activate</button>
  </div>

  <!-- F-18 -->
  <div class="jet">
    <img src="https://upload.wikimedia.org/wikipedia/commons/2/2a/FA-18_Hornet.jpg">
    <h2>F/A-18 Hornet</h2>
    <p>Carrier-capable multirole fighter used by the Navy.</p>

    <div class="stats">
      <p><b>Speed:</b> Mach 1.8</p>
      <p><b>Range:</b> 3,300 km</p>
      <p><b>Role:</b> Multirole</p>
    </div>

    <button onclick="alert('Carrier Launch ⚓')">Activate</button>
  </div>

  <!-- F-14 -->
  <div class="jet">
    <img src="https://upload.wikimedia.org/wikipedia/commons/2/2e/F-14A_Tomcat.jpg">
    <h2>F-14 Tomcat</h2>
    <p>Iconic swing-wing fighter made famous by Top Gun.</p>

    <div class="stats">
      <p><b>Speed:</b> Mach 2.34</p>
      <p><b>Range:</b> 3,200 km</p>
      <p><b>Role:</b> Interceptor</p>
    </div>

    <button onclick="alert('Top Gun Mode 🎬')">Activate</button>
  </div>

  <!-- Rafale -->
  <div class="jet">
    <img src="https://upload.wikimedia.org/wikipedia/commons/0/0c/Rafale_Marine.jpg">
    <h2>Dassault Rafale</h2>
    <p>French omnirole fighter with advanced systems.</p>

    <div class="stats">
      <p><b>Speed:</b> Mach 1.8</p>
      <p><b>Range:</b> 3,700 km</p>
      <p><b>Role:</b> Multirole</p>
    </div>

    <button onclick="alert('System Check 🎯')">Activate</button>
  </div>

  <!-- Mirage -->
  <div class="jet">
    <img src="https://upload.wikimedia.org/wikipedia/commons/4/4e/Mirage_2000.jpg">
    <h2>Mirage 2000</h2>
    <p>Delta-wing fighter known for speed and simplicity.</p>

    <div class="stats">
      <p><b>Speed:</b> Mach 2.2</p>
      <p><b>Range:</b> 3,335 km</p>
      <p><b>Role:</b> Interceptor</p>
    </div>

    <button onclick="alert('Delta Mode 🔺')">Activate</button>
  </div>

</div>

</body>
</html>
