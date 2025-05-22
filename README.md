index.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>ReMedi – Your Health, Our Priority</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600&display=swap" rel="stylesheet">
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body {
      font-family: 'Inter', sans-serif;
      background: linear-gradient(to bottom right, #e0f7fa, #ffffff);
      color: #333; line-height: 1.6;
    }
    header {
      background: #004d40; color: #fff; padding: 2rem;
      text-align: center; box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }
    nav {
      background: #00695c; padding: 1rem; text-align: center;
    }
    nav a {
      color: #fff; text-decoration: none; margin: 0 1rem;
      font-weight: 600; transition: color 0.3s;
    }
    nav a:hover { color: #b2dfdb; }
    section {
      max-width: 1000px; margin: 2rem auto; background: #fff;
      border-radius: 12px; padding: 2rem;
      box-shadow: 0 4px 12px rgba(0,0,0,0.05);
    }
    h2 { color: #00796b; margin-bottom: 1rem; }
    ul li { margin-bottom: 0.5rem; }
    .highlight-box {
      background: #e0f2f1; padding: 1.5rem;
      border-left: 6px solid #00796b;
      border-radius: 8px; margin-top: 1rem;
    }
    footer {
      background: #004d40; color: white; text-align: center;
      padding: 2rem 1rem; margin-top: 3rem;
    }
    .button {
      display: inline-block; margin-top: 1.5rem; background: #00796b;
      color: white; padding: 0.75rem 1.5rem; text-decoration: none;
      border-radius: 8px; font-weight: bold; transition: background 0.3s ease;
    }
    .button:hover { background: #004d40; }
  </style>
</head>
<body>
  <header>
    <h1>ReMedi</h1>
    <p>Your Health, Our Priority</p>
  </header>
  <nav>
    <a href="#about">About</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
  </nav>
  <section id="about">
    <h2>About Us</h2>
    <p>ReMedi is your trusted provider of pharmaceutical products and expert health advice in the UK. We are committed to making high-quality medications accessible, with care and precision.</p>
    <div class="highlight-box">
      <strong>Mission:</strong> Deliver quality, affordability, and trust in every product and service we offer.
    </div>
  </section>
  <section id="services">
    <h2>Our Services</h2>
    <ul>
      <li>✓ Prescription & over-the-counter medications</li>
      <li>✓ Online orders & home delivery</li>
      <li>✓ Blood pressure & glucose testing</li>
      <li>✓ Private consultations with pharmacists</li>
    </ul>
    <a class="button" href="#contact">Contact Us</a>
  </section>
  <section id="contact">
    <h2>Contact Information</h2>
    <p class="highlight-box">
      📍 6 Bank Street, High Street, TW1 1RR<br>
      📞 Phone: 074 654 65 543<br>
      🕒 Hours: Mon–Fri: 9:00–17:00 | Weekends: 10:00–15:00<br>
      ✉️ Email: info@remedi-health.co.uk
    </p>
  </section>
  <footer>
    &copy; 2025 ReMedi – All rights reserved.
  </footer>
</body>
</html>
