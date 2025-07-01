# funeral-website
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Tranquil Rest Funeral Services</title>
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; line-height: 1.6; color: #333; background: #f9f9f9; }
    header { background: #2c3e50; color: #fff; padding: 20px 0; text-align: center; }
    nav { background: #34495e; padding: 10px 0; text-align: center; }
    nav a { color: white; margin: 0 15px; text-decoration: none; font-weight: bold; }
    nav a:hover { text-decoration: underline; }
    section { padding: 40px 20px; max-width: 1000px; margin: auto; }
    h1, h2 { color: #2c3e50; margin-bottom: 20px; }
    .services, .portfolio { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 20px; }
    .service, .portfolio-item { background: #fff; border-radius: 8px; padding: 20px; box-shadow: 0 2px 6px rgba(0,0,0,0.1); }
    .portfolio-item img { width: 100%; border-radius: 6px; height: 200px; object-fit: cover; }
    footer { background: #2c3e50; color: #fff; text-align: center; padding: 20px 10px; }
    .contact-info p { margin-bottom: 10px; }
  </style>
</head>
<body>
  <header>
    <h1>Tranquil Rest Funeral Services</h1>
    <p>Dignified and Compassionate Farewells</p>
  </header>

  <nav>
    <a href="#services">Services</a>
    <a href="#portfolio">Portfolio</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="services">
    <h2>Our Services</h2>
    <div class="services">
      <div class="service">
        <h3>Traditional Funerals</h3>
        <p>Respectful, personalized ceremonies to honor your loved ones in a traditional setting.</p>
      </div>
      <div class="service">
        <h3>Cremation Services</h3>
        <p>Affordable and dignified cremation arrangements with options for memorial services.</p>
      </div>
      <div class="service">
        <h3>Pre-Planning</h3>
        <p>Plan ahead to ease the burden on your family and ensure your wishes are honored.</p>
      </div>
    </div>
  </section>

  <section id="portfolio">
    <h2>Portfolio</h2>
    <div class="portfolio">
      <div class="portfolio-item">
        <img src="https://images.unsplash.com/photo-1583132334659-47b72f06ab0b" alt="Chapel Setup">
        <p>Elegant chapel setup for a memorial service</p>
      </div>
      <div class="portfolio-item">
        <img src="https://images.unsplash.com/photo-1594225064026-d06f31b25694" alt="Casket & Flowers">
        <p>Beautiful floral arrangements and casket presentation</p>
      </div>
      <div class="portfolio-item">
        <img src="https://images.unsplash.com/photo-1604061983020-cd52f46c2533" alt="Outdoor Tribute">
        <p>Outdoor remembrance service with personalized decorations</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <div class="contact-info">
      <p><strong>Phone:</strong> +65 9123 4567</p>
      <p><strong>Email:</strong> info@tranquilrest.sg</p>
      <p><strong>Address:</strong> 123 Peace Lane, Singapore 567890</p>
      <p><strong>Hours:</strong> 24/7 Availability</p>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Tranquil Rest Funeral Services. All Rights Reserved.</p>
  </footer>
</body>
</html>
