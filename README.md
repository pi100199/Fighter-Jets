<!DOCTYPE html>
<html>
<head>
  <title>Fighter Jet Command</title>

  <style>
    body {
      background: radial-gradient(circle at top, #0a0f1c, #05070d);
      color: #00ffcc;
      font-family: Arial, sans-serif;
      margin: 0;
    }

    h1 {
      text-align: center;
      font-size: 50px;
      text-shadow: 0 0 20px #00ffcc;
      padding: 20px;
      letter-spacing: 2px;
    }

    .container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
    }

    .jet {
      background: rgba(0,0,0,0.8);
      border: 1px solid #00ffcc;
      margin: 20px;
      padding: 20px;
      border-radius: 15px;
      width: 320px;
      box-shadow: 0 0 15px #00ffcc;
      transition: 0.3s;
      position: relative;
      overflow: hidden;
    }

    .jet::before {
      content: "";
      position: absolute;
      width: 100%;
      height: 2px;
      background: #00ffcc;
      top: 0;
      left: -100%;
      animation: scan 3s infinite;
    }

    @keyframes scan {
      0% { left: -100%; }
      50% { left: 100%; }
      100% { left: 100%; }
    }

    .jet:hover {
      transform: scale(1.05);
      box-shadow: 0 0 30px #00ffcc;
    }

    h2 {
      margin-top: 0;
      text-shadow: 0 0 10px #00ffcc;
    }

    .role {
      font-size: 13px;
      opacity: 0.7;
      margin-bottom: 10px;
    }

    .stats {
      text-align: left;
      margin-top: 10px;
      font-size: 14px;
    }

    .stats p {
      margin: 5px 0;
    }

    .highlight {
      color: #ffffff;
    }

    button {
      width: 100%;
      margin-top: 15px;
      padding: 10px;
      background: transparent;
      color: #00ffcc;
      border: 1px solid #00ffcc;
      cursor: pointer;
      transition: 0.3s;
    }

    button:hover {
      background: #00ffcc;
      color: black;
    }
  </style>
</head>

<body>

<h1>✈️ Fighter Jet Command System</h1>

<div class="container">

  <div class="jet">
    <h2>F-22 Raptor</h2>
    <div class="role">Stealth Air Superiority Fighter</div>
    <p>Advanced 5th-gen jet with unmatched stealth and agility.</p>
    <div class="stats">
      <p><span class="highlight">Speed:</span> Mach 2.25</p>
      <p><span class="highlight">Range:</span> 2,960 km</p>
      <p><span class="highlight">Weapons:</span> Missiles + Cannon</p>
    </div>
    <button onclick="alert('Stealth Engaged 🚀')">Activate</button>
  </div>

  <div class="jet">
    <h2>F-35 Lightning II</h2>
    <div class="role">Stealth Multirole Fighter</div>
    <p>Highly advanced jet with sensor fusion and stealth tech.</p>
    <div class="stats">
      <p><span class="highlight">Speed:</span> Mach 1.6</p>
      <p><span class="highlight">Range:</span> 2,200 km</p>
      <p><span class="highlight">Systems:</span> AI Assisted</p>
    </div>
    <button onclick="alert('Stealth Mode ⚡')">Activate</button>
  </div>

  <div class="jet">
    <h2>F-16 Fighting Falcon</h2>
    <div class="role">Multirole Fighter</div>
    <p>Lightweight jet known for extreme maneuverability.</p>
    <div class="stats">
      <p><span class="highlight">Speed:</span> Mach 2.0</p>
      <p><span class="highlight">Range:</span> 4,200 km</p>
      <p><span class="highlight">Strength:</span> Agility</p>
    </div>
    <button onclick="alert('Agility Boost 💨')">Activate</button>
  </div>

  <div class="jet">
    <h2>F-15 Eagle</h2>
    <div class="role">Air Superiority Fighter</div>
    <p>One of the most successful fighters ever built.</p>
    <div class="stats">
      <p><span class="highlight">Speed:</span> Mach 2.5</p>
      <p><span class="highlight">Range:</span> 5,500 km</p>
      <p><span class="highlight">Record:</span> 100+ Wins</p>
    </div>
    <button onclick="alert('Combat Mode 🏆')">Activate</button>
  </div>

  <div class="jet">
    <h2>F/A-18 Hornet</h2>
    <div class="role">Carrier Multirole Fighter</div>
    <p>Operates from aircraft carriers with versatility.</p>
    <div class="stats">
      <p><span class="highlight">Speed:</span> Mach 1.8</p>
      <p><span class="highlight">Range:</span> 3,300 km</p>
      <p><span class="highlight">Feature:</span> Naval Ops</p>
    </div>
    <button onclick="alert('Carrier Launch ⚓')">Activate</button>
  </div>

  <div class="jet">
    <h2>F-14 Tomcat</h2>
    <div class="role">Interceptor</div>
    <p>Famous swing-wing jet featured in Top Gun.</p>
    <div class="stats">
      <p><span class="highlight">Speed:</span> Mach 2.34</p>
      <p><span class="highlight">Range:</span> 3,200 km</p>
      <p><span class="highlight">Feature:</span> Variable Wings</p>
    </div>
    <button onclick="alert('Top Gun Mode 🎬')">Activate</button>
  </div>

  <div class="jet">
    <h2>Dassault Rafale</h2>
    <div class="role">Omnirole Fighter</div>
    <p>French jet capable of air, ground, and naval missions.</p>
    <div class="stats">
      <p><span class="highlight">Speed:</span> Mach 1.8</p>
      <p><span class="highlight">Range:</span> 3,700 km</p>
      <p><span class="highlight">Strength:</span> Versatility</p>
    </div>
    <button onclick="alert('System Check 🎯')">Activate</button>
  </div>

  <!-- ✅ MIRAGE ADDED HERE -->
  <div class="jet">
    <h2>Mirage 2000</h2>
    <div class="role">Interceptor / Multirole Fighter</div>
    <p>French delta-wing fighter known for speed, precision, and simplicity in design.</p>
    <div class="stats">
      <p><span class="highlight">Speed:</span> Mach 2.2</p>
      <p><span class="highlight">Range:</span> 3,335 km</p>
      <p><span class="highlight">Feature:</span> Delta Wing Design</p>
    </div>
    <button onclick="alert('Delta Mode 🔺')">Activate</button>
  </div>

  <div class="jet">
    <h2>Eurofighter Typhoon</h2>
    <div class="role">Air Superiority Fighter</div>
    <p>European jet with supercruise and agility.</p>
    <div class="stats">
      <p><span class="highlight">Speed:</span> Mach 2.0</p>
      <p><span class="highlight">Range:</span> 2,900 km</p>
      <p><span class="highlight">Feature:</span> Supercruise</p>
    </div>
    <button onclick="alert('Boost ⚡')">Activate</button>
  </div>

  <div class="jet">
    <h2>Su-57 Felon</h2>
    <div class="role">Stealth Multirole Fighter</div>
    <p>Russia’s advanced stealth jet with high maneuverability.</p>
    <div class="stats">
      <p><span class="highlight">Speed:</span> Mach 2.0</p>
      <p><span class="highlight">Range:</span> 3,500 km</p>
      <p><span class="highlight">Feature:</span> 3D Thrust Vectoring</p>
    </div>
    <button onclick="alert('Weapons Online 💥')">Activate</button>
  </div>

</div>

</body>
</html>
