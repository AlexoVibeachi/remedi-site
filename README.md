index.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>ReMedi – Your Health, Our Priority</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Inter', sans-serif;
      background-color: #f9f9f9;
      color: #333;
    }
    header {
      background-color: #00796b;
      color: white;
      padding: 2em 1em;
      text-align: center;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    }
    nav {
      text-align: center;
      margin-top: 1em;
    }
    nav a {
      margin: 0 1em;
      color: white;
      text-decoration: none;
      font-weight: 600;
    }
    nav a:hover {
      text-decoration: underline;
    }
    section {
      max-width: 960px;
      margin: auto;
      padding: 2em;
      background-color: white;
      margin-top: 2em;
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.05);
    }
    h2 {
      color: #00796b;
    }
    ul {
      padding-left: 1.2em;
    }
    .services li::marker {
      color: #00796b;
    }
    footer {
      background-color: #004d40;
      color: white;
      text-align: center;
      padding: 1.5em 1em;
      margin-top: 3em;
    }
    .contact-info {
      font-size: 0.95em;
      margin-top: 1em;
      background: #e0f2f1;
      padding: 1em;
      border-radius: 8px;
    }
    .cta {
      text-align: center;
      margin-top: 2em;
    }
    .cta a {
      background-color: #00796b;
      color: white;
      padding: 0.75em 1.5em;
      border-radius: 8px;
      text-decoration: none;
      font-weight: 600;
      transition: background 0.3s;
    }
    .cta a:hover {
      background-color: #005a4f;
    }
  </style>
</head>
<body>
  <header>
    <h1>ReMedi</h1>
    <p>Your Health, Our Priority</p>
    <nav>
      <a href="#about">About</a>
      <a href="#services">Services</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="about">
    <h2>About Us</h2>
    <p>ReMedi is a trusted provider of pharmaceutical products and services in the UK. Our mission is to ensure access to quality medicines and expert advice. We prioritize patient care, trust, and quality in everything we do.</p>
  </section>

  <section id="services">
    <h2>Our Services</h2>
    <ul class="services">
      <li>Prescription and over-the-counter medications</li>
      <li>Pharmacist consultations</li>
      <li>Online orders and home delivery</li>
      <li>Blood pressure and glucose checks</li>
    </ul>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <div class="contact-info">
      📍 6 Bank Street, High Street, TW1 1RR<br>
      📞 074 654 65 543<br>
      🕒 Mon–Fri: 9:00–17:00 | Weekends: 10:00–15:00
    </div>
    <div class="cta">
      <a href="mailto:info@remedi-health.co.uk">Get in Touch</a>
    </div>
  </section>

  <footer>
    &copy; 2025 ReMedi. All rights reserved.
  </footer>
</body>
</html>
