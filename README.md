<!DOCTYPE
 html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>SkyAlliance Airlines Group</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Inter', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f2f6fc;
      color: #333;
    }
    header {
      background-color: #003366;
      color: white;
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    header h1 {
      margin: 0;
      font-size: 1.8rem;
    }
    nav a {
      color: white;
      margin-left: 20px;
      text-decoration: none;
      font-weight: 500;
    }
    .hero {
      padding: 80px 40px;
      background: url('https://images.unsplash.com/photo-1524492449090-1e45b6c45f98?auto=format&fit=crop&w=1400&q=80') no-repeat center center/cover;
      color: gold;
      text-align: center;
    }
    .hero h2 {
      font-size: 2.5rem;
      margin-bottom: 20px;
    }
    .hero p {
      font-size: 1.2rem;
    }
    .section {
      padding: 60px 40px;
      background-color: white;
    }
    .section h3 {
      font-size: 2rem;
      margin-bottom: 20px;
      color: #0055aa;
    }
    h1, h2, h3, h4 {
      color: #0055aa;
    }
    .airlines {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
    }
    .airline-card {
      flex: 1 1 300px;
      background-color: #eaf0fa;
      border-radius: 12px;
      padding: 20px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }
    .footer {
      background-color: #003366;
      color: white;
      text-align: center;
      padding: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>SkyAlliance</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#airlines">Airlines</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <div class="hero">
    <h2>Connecting the World, Together</h2>
    <p>SkyAlliance is a global group of leading airlines committed to seamless travel and exceptional service.</p>
  </div>

  <div class="section" id="about">
    <h3>About SkyAlliance</h3>
    <p>Founded in 2025 by Niccolo Camporeale, SkyAlliance brings together top-tier international airlines to provide travelers with more destinations, coordinated schedules, and a superior flying experience. Our mission is to make global travel more connected and accessible. The group includes 8 major airlines: ITA Airways, United Airlines, Southwest Airlines, American Airlines, KLM Royal Dutch Airlines, Lufthansa, British Airways, and Air France. SkyAlliance also owns and operates many subsidiaries worldwide, serving both domestic and international markets.</p>
  </div>

  <div class="section" id="airlines">
    <h3>Our Member Airlines</h3>
    <div class="airlines">
      <div class="airline-card">
        <h4>ITA Airways</h4>
        <p>The Italian flag carrier, providing high-quality service across Europe and beyond.</p>
      </div>
      <div class="airline-card">
        <h4>United Airlines</h4>
        <p>A major U.S. airline connecting North America to the world.</p>
      </div>
      <div class="airline-card">
        <h4>Southwest Airlines</h4>
        <p>Known for low fares and reliable service across the United States.</p>
      </div>
      <div class="airline-card">
        <h4>American Airlines</h4>
        <p>One of the largest airlines in the world with extensive global routes.</p>
      </div>
      <div class="airline-card">
        <h4>KLM Royal Dutch Airlines</h4>
        <p>The oldest operating airline, connecting Europe with the world.</p>
      </div>
      <div class="airline-card">
        <h4>Lufthansa</h4>
        <p>Germany's flagship carrier offering premium service and a wide network.</p>
      </div>
      <div class="airline-card">
        <h4>British Airways</h4>
        <p>Connecting the UK globally with trusted and professional service.</p>
      </div>
      <div class="airline-card">
        <h4>Air France</h4>
        <p>France's national carrier with routes spanning the globe.</p>
      </div>
    </div>
  </div>

  <div class="section" id="contact">
    <h3>Contact Us</h3>
    <p>Email: info@skyalliance.com<br />Phone: +1 (800) 555-8899</p>
  </div>

  <div class="footer">
    &copy; 2025 SkyAlliance. All rights reserved.
  </div>
</body>
</html>
