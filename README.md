

<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Dan's Cafe</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      background-color: #fff;
      color: #4e342e;
    }
    header {
      background-color: #d7ccc8;
      color: #3e2723;
      padding: 1rem 1rem;
      text-align: center;
    }
    header img {
      height: 60px;
      margin-bottom: 0.5rem;
    }
    nav {
      background-color: #a1887f;
      display: flex;
      justify-content: center;
      padding: 0.5rem;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0 1rem;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    section {
      padding: 2rem 1rem;
      text-align: center;
    }
    .menu {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
      padding: 2rem;
    }
    .item {
      background-color: #f5f5f5;
      border-radius: 10px;
      padding: 1rem;
      box-shadow: 0 0 5px rgba(0,0,0,0.05);
    }
    .item img {
      width: 100%;
      height: 180px;
      object-fit: cover;
      border-radius: 8px;
    }
    .item h3 {
      margin: 0.5rem 0;
    }
    footer {
      background-color: #a1887f;
      color: white;
      text-align: center;
      padding: 1rem;
    }
  </style>
</head>
<body>

  <header>
    <img src="20250720_221620_0000.png" alt="Cafe Logo">
    <h1>Dan's Cafe</h1>
    <p>Where Sweet Moments Brew</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#menu">Menu</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="home">
    <h2>Welcome to Dan's Cafe</h2>
    <p>Enjoy handcrafted pastries and aromatic coffee in a cozy minimalist space made just for you.</p>
  </section>

  <section id="menu">
    <h2>Our Menu</h2>
    <div class="menu">
      <div class="item">
        <img src="IMG_20250720_230837_196.jpg" alt="Macaron">
        <h3>Macaron</h3>
        <p>₱85 - Colorful, delicate, and perfectly sweet.</p>
      </div>
      <div class="item">
        <img src="IMG_20250720_230838_794.jpg" alt="Croissant">
        <h3>Croissant</h3>
        <p>₱120 - Flaky, buttery, and freshly baked every morning.</p>
      </div>
      <div class="item">
        <img src="IMG_20250720_230840_954.jpg" alt="Iced Americano">
        <h3>Iced Americano</h3>
        <p>₱100 - Refreshing and bold with a smooth espresso base.</p>
      </div>
      <div class="item">
        <img src="IMG_20250720_230843_019.jpg" alt="Cappuccino">
        <h3>Cappuccino</h3>
        <p>₱110 - A perfect balance of espresso, milk, and foam.</p>
      </div>
    </div>
  </section>

  <section id="about">
    <h2>About Us</h2>
    <p>Founded in 2025, Dan's Cafe is a warm, minimalist space designed for those who love quiet corners, pastries, and exceptional coffee.</p>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Email: hello@dan'scafe.com<br>Instagram: @dan'scafe.ph<br>Visit us in Manila!</p>
  </section>

  <footer>
    &copy; 2025 Dan's Cafe. All rights reserved.
  </footer>

</body>
</html>
