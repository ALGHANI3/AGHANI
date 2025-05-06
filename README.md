<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Alghani Perfumes</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: #f9f5f5;
      color: #333;
    }

    header, footer {
      background-color: #1a1a1a;
      color: white;
      text-align: center;
      padding: 20px;
    }

    header h1 {
      margin: 0;
      font-size: 2.5em;
    }

    .hero {
      padding: 50px 20px;
      text-align: center;
      background: linear-gradient(to bottom, #fff5f5, #f0e5e5);
    }

    .hero img {
      width: 300px;
      border-radius: 15px;
      box-shadow: 0 5px 20px rgba(0,0,0,0.2);
    }

    .hero h2 {
      margin-top: 20px;
      color: #7a3e3e;
    }

    .btn {
      margin-top: 20px;
      padding: 10px 25px;
      background-color: #7a3e3e;
      color: white;
      border: none;
      border-radius: 25px;
      cursor: pointer;
    }

    .section {
      padding: 50px 20px;
      text-align: center;
    }

    .products, .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
      max-width: 1000px;
      margin: auto;
    }

    .product, .gallery img {
      background: white;
      padding: 10px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }

    .product img {
      width: 100%;
      border-radius: 8px;
    }

    .contact-form {
      max-width: 600px;
      margin: auto;
    }

    input, textarea {
      width: 100%;
      padding: 10px;
      margin-top: 10px;
      border: 1px solid #ccc;
      border-radius: 8px;
    }

    .instagram-feed {
      background-color: #f0f0f0;
      padding: 20px;
    }

    .instagram-feed p {
      font-style: italic;
      color: #555;
    }

    /* WhatsApp button */
    .whatsapp-button {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background-color: #25D366;
      color: white;
      padding: 15px;
      border-radius: 50%;
      font-size: 20px;
      text-align: center;
      z-index: 999;
      box-shadow: 0 4px 10px rgba(0,0,0,0.3);
      text-decoration: none;
    }

  </style>
</head>
<body>

<header>
  <h1>Alghani Perfumes</h1>
</header>

<section class="hero">
  <img src="https://images.unsplash.com/photo-1598511723805-d3dc3b0e9d66?auto=format&fit=crop&w=600&q=80" alt="Perfume" />
  <h2>Fragrance That Defines You</h2>
  <p>Elegant. Timeless. Just like you.</p>
  <button class="btn">Explore Collection</button>
</section>

<section class="section">
  <h2>Our Products</h2>
  <div class="products">
    <div class="product">
      <img src="https://images.unsplash.com/photo-1600180758890-d4df7c1dfdf7?auto=format&fit=crop&w=400&q=80" alt="Product 1">
      <p>Rose Oud - 100ml</p>
    </div>
    <div class="product">
      <img src="https://images.unsplash.com/photo-1616627981347-5e098c5ab6e0?auto=format&fit=crop&w=400&q=80" alt="Product 2">
      <p>Musk Alghani - 50ml</p>
    </div>
    <div class="product">
      <img src="https://images.unsplash.com/photo-1606111820642-01c5b87b0b8e?auto=format&fit=crop&w=400&q=80" alt="Product 3">
      <p>Amber Night - 100ml</p>
    </div>
  </div>
</section>

<section class="section gallery">
  <h2>Gallery</h2>
  <div class="gallery">
    <img src="https://images.unsplash.com/photo-1600180758834-9ee94d9116e4?auto=format&fit=crop&w=400&q=80" alt="Gallery 1">
    <img src="https://images.unsplash.com/photo-1588098666910-7fa029ddaeaf?auto=format&fit=crop&w=400&q=80" alt="Gallery 2">
    <img src="https://images.unsplash.com/photo-1556228453-c8469239e6ca?auto=format&fit=crop&w=400&q=80" alt="Gallery 3">
  </div>
</section>

<section class="section contact">
  <h2>Contact Us</h2>
  <div class="contact-form">
    <form action="https://formspree.io/f/your-form-id" method="POST">
      <input type="text" name="name" placeholder="Your Name" required />
      <input type="email" name="email" placeholder="Your Email" required />
      <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
      <button type="submit" class="btn">Send Message</button>
    </form>
  </div>
</section>

<section class="section instagram-feed">
  <h2>Instagram Feed</h2>
  <p>Follow us on Instagram @alghaniperfumes for the latest updates!</p>
  <!-- Placeholder only, you can later embed Instagram posts -->
</section>

<footer>
  &copy; 2025 Alghani Perfumes. All rights reserved.
</footer>

<!-- WhatsApp Chat Button -->
<a class="whatsapp-button" href="https://wa.me/923001234567" target="_blank">💬</a>

</body>
</html>
