<html>
<head>
  <style>
    body {
      background: radial-gradient(circle at top, #0a0f1c, #05070d);
      color: #00ffcc;
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 20px;
    }

    .container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
    }

    .jet {
      background: rgba(0,0,0,0.9);
      border: 1px solid #00ffcc;
      margin: 12px;
      padding: 15px;
      border-radius: 10px;
      width: 260px;
      box-shadow: 0 0 8px #00ffcc;
      transition: 0.25s;
    }

    .jet:hover {
      transform: scale(1.06);
      box-shadow: 0 0 20px #00ffcc;
    }

    h2 {
      margin: 0;
      font-size: 18px;
      text-shadow: 0 0 8px #00ffcc;
    }

    .role {
      font-size: 11px;
      opacity: 0.7;
      margin-bottom: 8px;
    }

    .description {
      font-size: 12px;
      margin-bottom: 8px;
    }

    .stats {
      font-size: 12px;
      border-top: 1px solid #00ffcc;
      padding-top: 8px;
    }

    .stats p {
      margin: 3px 0;
    }

    .label {
      color: white;
    }

    .status {
      margin-top: 6px;
      font-size: 11px;
    }

    .online { color: lime; }
    .ready { color: orange; }
  </style>
</head>

<body>

<div class="container">

  <div class="jet"><h2>F-22 Raptor</h2><div class="role">Stealth Air Superiority</div><div class="description">5th-gen stealth fighter.</div><div class="stats"><p><span class="label">Speed:</span> Mach 2.25</p><p><span class="label">Range:</span> 2,960 km</p></div><div class="status">Operational</div></div>

  <div class="jet"><h2>F-35 Lightning II</h2><div class="role">Stealth Multirole</div><div class="description">Advanced sensor fusion fighter.</div><div class="stats"><p><span class="label">Speed:</span> Mach 1.6</p><p><span class="label">Range:</span> 2,200 km</p></div><div class="status online">Active</div></div>

  <div class="jet"><h2>F-16 Fighting Falcon</h2><div class="role">Multirole</div><div class="description">Highly maneuverable.</div><div class="stats"><p><span class="label">Speed:</span> Mach 2.0</p><p><span class="label">Range:</span> 4,200 km</p></div><div class="status online">Active</div></div>

  <div class="jet"><h2>F-15 Eagle</h2><div class="role">Air Superiority</div><div class="description">Legendary combat jet.</div><div class="stats"><p><span class="label">Speed:</span> Mach 2.5</p><p><span class="label">Range:</span> 5,500 km</p></div><div class="status online">Combat Ready</div></div>

  <div class="jet"><h2>F/A-18 Hornet</h2><div class="role">Carrier Multirole</div><div class="description">Naval fighter.</div><div class="stats"><p><span class="label">Speed:</span> Mach 1.8</p><p><span class="label">Range:</span> 3,300 km</p></div><div class="status online">Carrier Ready</div></div>

  <div class="jet"><h2>F-14 Tomcat</h2><div class="role">Interceptor</div><div class="description">Swing-wing legend.</div><div class="stats"><p><span class="label">Speed:</span> Mach 2.34</p><p><span class="label">Range:</span> 3,200 km</p></div><div class="status ready">Retired</div></div>

  <div class="jet"><h2>Dassault Rafale</h2><div class="role">Omnirole</div><div class="description">French multi-mission jet.</div><div class="stats"><p><span class="label">Speed:</span> Mach 1.8</p><p><span class="label">Range:</span> 3,700 km</p></div><div class="status online">Operational</div></div>

  <div class="jet"><h2>Mirage 2000</h2><div class="role">Interceptor</div><div class="description">Delta-wing speed fighter.</div><div class="stats"><p><span class="label">Speed:</span> Mach 2.2</p><p><span class="label">Range:</span> 3,335 km</p></div><div class="status ready">Standby</div></div>

  <div class="jet"><h2>Eurofighter Typhoon</h2><div class="role">Air Superiority</div><div class="description">High agility European jet.</div><div class="stats"><p><span class="label">Speed:</span> Mach 2.0</p><p><span class="label">Range:</span> 2,900 km</p></div><div class="status online">Active</div></div>

  <div class="jet"><h2>Su-57 Felon</h2><div class="role">Stealth Multirole</div><div class="description">Russian stealth fighter.</div><div class="stats"><p><span class="label">Speed:</span> Mach 2.0</p><p><span class="label">Range:</span> 3,500 km</p></div><div class="status ready">Testing</div></div>

</div>

</body>
</html>
