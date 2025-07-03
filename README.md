<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>LUNORÉ – Timeless Elegance</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;700&family=Inter:wght@300;400;600&display=swap" rel="stylesheet" />
  <style>
    body {
      margin: 0;
      font-family: 'Inter', sans-serif;
      background-color: #f4f2ec;
      color: #0d0d0d;
    }
    header {
      padding: 2rem 5%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      border-bottom: 1px solid #dcd6cc;
      font-family: 'Playfair Display', serif;
    }
    nav a {
      margin: 0 1rem;
      text-decoration: none;
      color: #0d0d0d;
      font-weight: 500;
    }
    .hero {
      background: #e7e2d5;
      text-align: center;
      padding: 4rem 2rem;
    }
    .hero h1 {
      font-size: 3rem;
      margin-bottom: 1rem;
      font-family: 'Playfair Display', serif;
    }
    .hero button {
      background-color: #0d0d0d;
      color: #fff;
      border: none;
      padding: 0.75rem 2rem;
      font-size: 1rem;
      cursor: pointer;
      border-radius: 2px;
    }
    .section {
      padding: 3rem 5%;
    }
    .section h2 {
      font-family: 'Playfair Display', serif;
      font-size: 2rem;
      margin-bottom: 2rem;
    }
    .products {
      display: flex;
      gap: 2rem;
      flex-wrap: wrap;
      justify-content: center;
    }
    .product {
      width: 220px;
      text-align: center;
    }
    .product img {
      width: 100%;
      border-radius: 4px;
    }
    .product h3 {
      font-size: 1.1rem;
      margin: 0.5rem 0 0.25rem;
    }
    .product p {
      font-size: 0.95rem;
      color: #555;
    }
    .newsletter {
      background: #0d0d0d;
      color: #f4f2ec;
      padding: 2rem 5%;
      text-align: center;
    }
    .newsletter input[type="email"] {
      padding: 0.5rem;
      margin-top: 1rem;
      border: none;
      width: 250px;
    }
    .newsletter button {
      padding: 0.5rem 1rem;
      background-color: #c5a75f;
      color: #0d0d0d;
      border: none;
      margin-left: 1rem;
      cursor: pointer;
    }
    footer {
      background: #0d0d0d;
      color: #f4f2ec;
      padding: 2rem 5%;
      text-align: center;
      font-size: 0.875rem;
    }
  </style>
</head>
<body>
  <header>
    <div><strong>LUNORÉ</strong></div>
    <nav>
      <a href="#collection">Collection</a>
      <a href="#about">About</a>
      <a href="#journal">Journal</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h1>Timeless Elegance</h1>
    <p>Style written in moonlight. Explore our signature old money pieces.</p>
    <button>Shop Now</button>
  </section>

  <section class="section" id="collection">
    <h2>New Arrivals</h2>
    <div class="products">
      <div class="product">
        <img src="https://via.placeholder.com/220x300" alt="Ivory Polo" />
        <h3>Ivory Polo</h3>
        <p>₹4,800</p>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/220x300" alt="Heritage Trousers" />
        <h3>Heritage Trousers</h3>
        <p>₹7,200</p>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/220x300" alt="Midnight Knit" />
        <h3>Midnight Knit</h3>
        <p>₹8,500</p>
      </div>
    </div>
  </section>

  <section class="section" id="about">
    <h2>About Lunoré</h2>
    <p>Lunoré is a luxury fashion house founded on the principle of quiet power and timeless elegance. Each piece is crafted with the heritage of old money style, redefined for modern legacy builders. We believe real luxury whispers.</p>
  </section>

  <section class="section" id="journal">
    <h2>From The Journal</h2>
    <p>Read insights on understated fashion, legacy, and the philosophy behind Lunoré's design language.</p>
  </section>

  <section class="section" id="contact">
    <h2>Contact & Concierge</h2>
    <p>Email: concierge@lunore.com</p>
    <p>Instagram: @lunore.official</p>
  </section>

  <section class="newsletter">
    <h2>Join The Lunoré Club</h2>
    <p>Get exclusive access to private drops, stories, and timeless elegance.</p>
    <input type="email" placeholder="Your email address" />
    <button>Join Now</button>
  </section>

  <footer>
    © 2025 LUNORÉ. All rights reserved. | Style written in moonlight.
  </footer>
</body>
</html>
