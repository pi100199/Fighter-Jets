<!DOCTYPE html>
<html>
<head>
  <title>Fighter Jet Command System</title>

  <style>
    body {
      background: radial-gradient(circle at top, #0a0f1c, #05070d);
      color: #00ffcc;
      font-family: Arial, sans-serif;
      margin: 0;
    }

    h1 {
      text-align: center;
      font-size: 45px;
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
      background: rgba(0,0,0,0.85);
      border: 1px solid #00ffcc;
      margin: 15px;
      padding: 20px;
      border-radius: 12px;
      width: 300px;
      box-shadow: 0 0 10px #00ffcc;
      transition: 0.3s;
    }

    .jet:hover {
      transform: scale(1.05);
      box-shadow: 0 0 25px #00ffcc;
    }

    h2 {
      margin: 0;
      text-shadow: 0 0 10px #00ffcc;
    }

    .role {
      font-size: 12px;
      opacity: 0.7;
      margin-bottom: 10px;
    }

    .description {
      font-size: 13px;
      margin-bottom: 10px;
    }

    .stats {
      font-size: 13px;
      text-align: left;
      border-top: 1px solid #00ffcc;
      padding-top: 10px;
    }

    .stats p {
      margin: 4px 0;
    }

    .label {
      color: #ffffff;
    }

    .status {
      margin-top: 10px;
      font-size: 12px;
    }

    .online {
      color: lime;
    }

    .ready {
      color: orange;
    }
  </style>
</head>

<body>

<h1>✈️ Fighter Jet Command System</h1>

<div class="container">

  <div class="jet">
    <h2>F-22 Raptor</h2>
    <div class="role">Stealth Air Superiority</div>
    <div class="description">5th-gen stealth fighter with extreme agility.</div>
    <div class="stats">
      <p><span class="label">Speed:</span> Mach 2.25</p>
      <p><span class="label">Range:</span> 2,960 km</p>
      <p><span class="label">Ceiling:</span> 65,000 ft</p>
    </div>
    <div class="status">Status: <span class="online">Operational</span></div>
  </div>

  <div class="jet">
    <h2>F-35 Lightning II</h2>
    <div class="role">Stealth Multirole</div>
    <div class="description">Sensor-fusion stealth fighter.</div>
    <div class="stats">
      <p><span class="label">Speed:</span> Mach 1.6</p>
      <p><span class="label">Range:</span> 2,200 km</p>
    </div>
    <div class="status">Status: <span class="online">Operational</span></div>
  </div>

  <div class="jet">
    <h2>F-16 Fighting Falcon</h2>
    <div class="role">Multirole</div>
    <div class="description">Highly agile lightweight fighter.</div>
    <div class="stats">
      <p><span class="label">Speed:</span> Mach 2.0</p>
      <p><span class="label">Range:</span> 4,200 km</p>
    </div>
    <div class="status">Status: <span class="online">Active</span></div>
  </div>

  <div class="jet">
    <h2>F-15 Eagle</h2>
    <div class="role">Air Superiority</div>
    <div class="description">Unmatched combat record.</div>
    <div class="stats">
      <p><span class="label">Speed:</span> Mach 2.5</p>
      <p><span class="label">Range:</span> 5,500 km</p>
    </div>
    <div class="status">Status: <span class="online">Combat Ready</span></div>
  </div>

  <!-- ✅ F-18 BACK -->
  <div class="jet">
    <h2>F/A-18 Hornet</h2>
    <div class="role">Carrier Multirole</div>
    <div class="description">Naval fighter designed for aircraft carriers.</div>
    <div class="stats">
      <p><span class="label">Speed:</span> Mach 1.8</p>
      <p><span class="label">Range:</span> 3,300 km</p>
    </div>
    <div class="status">Status: <span class="online">Carrier Ready</span></div>
  </div>

  <!-- ✅ F-14 BACK -->
  <div class="jet">
    <h2>F-14 Tomcat</h2>
    <div class="role">Interceptor</div>
    <div class="description">Swing-wing naval interceptor made famous by Top Gun.</div>
    <div class="stats">
      <p><span class="label">Speed:</span> Mach 2.34</p>
      <p><span class="label">Range:</span> 3,200 km</p>
    </div>
    <div class="status">Status: <span class="ready">Retired</span></div>
  </div>

  <div class="jet">
    <h2>Dassault Rafale</h2>
    <div class="role">Omnirole</div>
    <div class="description">French multi-mission fighter.</div>
    <div class="stats">
      <p><span class="label">Speed:</span> Mach 1.8</p>
      <p><span class="label">Range:</span> 3,700 km</p>
    </div>
    <div class="status">Status: <span class="online">Operational</span></div>
  </div>

  <div class="jet">
    <h2>Mirage 2000</h2>
    <div class="role">Interceptor</div>
    <div class="description">Delta-wing fighter focused on speed.</div>
    <div class="stats">
      <p><span class="label">Speed:</span> Mach 2.2</p>
      <p><span class="label">Range:</span> 3,335 km</p>
    </div>
    <div class="status">Status: <span class="ready">Standby</span></div>
  </div>

  <div class="jet">
    <h2>Eurofighter Typhoon</h2>
    <div class="role">Air Superiority</div>
    <div class="description">High agility European fighter.</div>
    <div class="stats">
      <p><span class="label">Speed:</span> Mach 2.0</p>
      <p><span class="label">Range:</span> 2,900 km</p>
    </div>
    <div class="status">Status: <span class="online">Active</span></div>
  </div>

  <div class="jet">
    <h2>Su-57 Felon</h2>
    <div class="role">Stealth Multirole</div>
    <div class="description">Advanced Russian stealth jet.</div>
    <div class="stats">
      <p><span class="label">Speed:</span> Mach 2.0</p>
      <p><span class="label">Range:</span> 3,500 km</p>
    </div>
    <div class="status">Status: <span class="ready">Testing</span></div>
  </div>

</div>

</body>
</html>
