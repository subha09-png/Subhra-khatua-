<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>QuickFix Repair</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }
    body {
      background: #f5f5f5;
      color: #333;
    }
    header {
      background-color: #003366;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      background-color: #004080;
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 10px 0;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    section {
      padding: 40px 20px;
      max-width: 1200px;
      margin: auto;
    }
    .services, .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .card {
      background: white;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      text-align: center;
    }
    .card img {
      width: 100%;
      height: 160px;
      object-fit: cover;
      border-radius: 6px;
    }
    .contact-form {
      background: white;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      max-width: 600px;
      margin: auto;
    }
    .contact-form input, .contact-form textarea {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border: 1px solid #ccc;
      border-radius: 6px;
    }
    .contact-form button {
      background: #003366;
      color: white;
      padding: 10px 20px;
      border: none;
      border-radius: 6px;
      cursor: pointer;
    }
    footer {
      text-align: center;
      padding: 20px;
      background-color: #003366;
      color: white;
    }
  </style>
</head>
<body>
  <header>
    <h1>QuickFix Repair Center</h1>
    <p>Fast & Reliable Laptop and Mobile Repair Services</p>
  </header>

  <nav>
    <a href="#services">Services</a>
    <a href="#about">About</a>
    <a href="#gallery">Gallery</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="services">
    <h2>Our Services</h2>
    <div class="services">
      <div class="card">
        <img src="https://via.placeholder.com/300x160?text=Screen+Replacement" alt="Screen Replacement" />
        <h3>Screen Replacement</h3>
        <p>Broken or cracked screen? We'll fix it like new!</p>
      </div>
      <div class="card">
        <img src="https://via.placeholder.com/300x160?text=Battery+Issue" alt="Battery Issue" />
        <h3>Battery Replacement</h3>
        <p>Battery draining fast? Get it replaced quickly.</p>
      </div>
      <div class="card">
        <img src="https://via.placeholder.com/300x160?text=Software+Repair" alt="Software Repair" />
        <h3>Software Repair</h3>
        <p>OS issues, slow device or virus removal—we fix all.</p>
      </div>
    </div>
  </section>

  <section id="about">
    <h2>About Us</h2>
    <p>We are a trusted laptop and mobile repairing center with over 5 years of experience. Our skilled technicians provide fast and guaranteed service. Customer satisfaction is our top priority!</p>
  </section>

  <section id="gallery">
    <h2>Our Work</h2>
    <div class="gallery">
      <img src="https://via.placeholder.com/300x200?text=Repair+1" alt="Repair work 1" />
      <img src="https://via.placeholder.com/300x200?text=Repair+2" alt="Repair work 2" />
      <img src="https://via.placeholder.com/300x200?text=Repair+3" alt="Repair work 3" />
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <div class="contact-form">
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <textarea placeholder="Your Message" rows="5" required></textarea>
      <button type="submit">Send Message</button>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 QuickFix Repair Center | All Rights Reserved</p>
  </footer>
</body>
</html>
