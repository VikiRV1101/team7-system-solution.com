<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Team7 System Solution</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0; padding: 0;
      background: #f4f4f4;
    }
    header {
      background: #222;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    nav {
      background: #333;
      display: flex;
      justify-content: center;
    }
    nav a {
      color: white;
      text-decoration: none;
      padding: 14px 20px;
      display: block;
    }
    nav a:hover {
      background: #555;
    }
    .hero {
      text-align: center;
      padding: 60px 20px;
      background: linear-gradient(120deg, #007bff, #00c6ff);
      color: white;
    }
    .hero h1 { font-size: 40px; margin: 10px 0; }
    .hero p { font-size: 18px; }
    .btn {
      display: inline-block;
      margin-top: 15px;
      padding: 10px 20px;
      background: #fff;
      color: #007bff;
      border-radius: 5px;
      font-weight: bold;
      text-decoration: none;
    }
    .section {
      padding: 40px 20px;
      text-align: center;
    }
    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
    }
    .card {
      background: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    }
    footer {
      background: #222;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Team7 System Solution</h1>
    <p>Laptop • PC • Printer • CCTV • Design & Printing • Billing Software</p>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
  </nav>

  <section class="hero">
    <h1>Your Trusted Tech & Design Partner</h1>
    <p>One-stop solution for Computers, CCTV, Printing, and Business Needs</p>
    <a href="tel:+919360039283" class="btn">📞 Call Us Now</a>
  </section>

  <section class="section" id="services">
    <h2>Our Services</h2>
    <div class="services">
      <div class="card">💻 Laptop & PC Sales/Service</div>
      <div class="card">🖨️ Printer Sales/Repair</div>
      <div class="card">📹 CCTV Installation</div>
      <div class="card">🧾 Billing Software</div>
      <div class="card">🎨 Print & Design (Cards, Flyers, Posters)</div>
      <div class="card">🌐 Website & Portfolio Design</div>
    </div>
  </section>

  <section class="section" id="contact">
    <h2>Contact Us</h2>
    <p>📍 Angalakurichi, Pollachi<br>
    📞 93600 39283 / 93630 06495<br>
    ✉️ teamsevensystemsolution@gmail.com</p>
  </section>

  <footer>
    <p>© 2025 Team7 System Solution | Created by Vignesh</p>
  </footer>
</body>
</html>
