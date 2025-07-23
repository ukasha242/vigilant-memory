<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Chaye Muhalla</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display&family=Open+Sans&display=swap" rel="stylesheet">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
      font-family: 'Open Sans', sans-serif;
      background-color: #fdf6f0;
      color: #333;
      line-height: 1.6;
    }
    header {
      background: #8B4513;
      color: white;
      padding: 20px 0;
      text-align: center;
    }
    header h1 {
      font-family: 'Playfair Display', serif;
      font-size: 3em;
    }
    nav {
      display: flex;
      justify-content: center;
      background: #5a2d0c;
    }
    nav a {
      color: white;
      padding: 15px 20px;
      text-decoration: none;
      transition: background 0.3s;
    }
    nav a:hover {
      background: #774726;
    }
    .hero {
      background: url('https://images.unsplash.com/photo-1584270354949-1f9e2d22963d') no-repeat center center/cover;
      height: 400px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      text-shadow: 2px 2px 4px #000;
      font-size: 2em;
    }
    section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }
    .menu-item {
      display: flex;
      justify-content: space-between;
      border-bottom: 1px dashed #ccc;
      padding: 10px 0;
    }
    .gallery img {
      width: 100%;
      max-width: 300px;
      margin: 10px;
      border-radius: 10px;
    }
    .contact-form input, .contact-form textarea {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    .contact-form button {
      background: #8B4513;
      color: white;
      padding: 10px 20px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    .contact-form button:hover {
      background: #5a2d0c;
    }
    footer {
      background: #8B4513;
      color: white;
      text-align: center;
      padding: 20px 0;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Chaye Muhalla</h1>
    <p>Your cozy neighborhood tea spot</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#menu">Menu</a>
    <a href="#gallery">Gallery</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="hero">
    Welcome to Chaye Muhalla
  </div>

  <section id="about">
    <h2>About Us</h2>
    <p>At Chaye Muhalla, we celebrate the joy of chai and community. Whether you're here to relax, work, or catch up with friends, our cafe offers a warm ambiance, rich flavors, and that perfect cup of chai every time.</p>
  </section>

  <section id="menu">
    <h2>Our Menu</h2>
    <div class="menu-item">
      <span>Masala Chai</span>
      <span>Rs. 150</span>
    </div>
    <div class="menu-item">
      <span>Kashmiri Chai</span>
      <span>Rs. 200</span>
    </div>
    <div class="menu-item">
      <span>Doodh Patti</span>
      <span>Rs. 120</span>
    </div>
    <div class="menu-item">
      <span>Paratha Roll</span>
      <span>Rs. 250</span>
    </div>
    <div class="menu-item">
      <span>French Fries</span>
      <span>Rs. 180</span>
    </div>
  </section>

  <section id="gallery">
    <h2>Gallery</h2>
    <div class="gallery" style="display: flex; flex-wrap: wrap; justify-content: center;">
      <img src="https://images.unsplash.com/photo-1509042239860-f550ce710b93" alt="Tea">
      <img src="https://images.unsplash.com/photo-1510626176961-4b67cf52b6f4" alt="Snacks">
      <img src="https://images.unsplash.com/photo-1550583724-b269f1f2c1db" alt="Cafe interior">
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>📍 Street 7, Lahore, Pakistan<br>📞 +92 300 1234567</p>
    <form class="contact-form">
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <textarea rows="5" placeholder="Your Message"></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Chaye Muhalla. All rights reserved.</p>
  </footer>
</body>
</html>
