<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Woodcraft Studio</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      line-height: 1.6;
      color: #333;
      background: #f5f2ed;
    }

    header {
      background: url('https://images.unsplash.com/photo-1600585154340-be6161a56a0c') center/cover no-repeat;
      color: white;
      height: 70vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
    }

    header h1 {
      font-size: 3rem;
      margin: 0;
      background: rgba(0,0,0,0.5);
      padding: 1rem 2rem;
    }

    nav {
      display: flex;
      justify-content: center;
      gap: 2rem;
      background: #3e2c1c;
      padding: 1rem;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    section {
      padding: 3rem 2rem;
      max-width: 1100px;
      margin: auto;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
    }

    .card {
      background: white;
      padding: 1rem;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }

    .card img {
      width: 100%;
      border-radius: 5px;
    }

    footer {
      text-align: center;
      padding: 1.5rem;
      background: #3e2c1c;
      color: white;
    }
  </style>
</head>
<body>

<header>
  <h1>Woodcraft Studio</h1>
</header>

<nav>
  <a href="#about">About</a>
  <a href="#projects">Projects</a>
  <a href="#contact">Contact</a>
</nav>

<section id="about">
  <h2>About</h2>
  <p>
    Custom woodworking focused on clean craftsmanship, durable materials, and timeless design.
    From furniture to small decor, everything is built by hand with attention to detail.
  </p>
</section>

<section id="projects">
  <h2>Projects</h2>
  <div class="grid">
    <div class="card">
      <img src="https://images.unsplash.com/photo-1582582429416-ec9fa3f9d7df" alt="">
      <h3>Dining Table</h3>
    </div>
    <div class="card">
      <img src="https://images.unsplash.com/photo-1556909212-d5b604d0c90d" alt="">
      <h3>Wood Shelves</h3>
    </div>
    <div class="card">
      <img src="https://images.unsplash.com/photo-1588854337221-4cf9fa96059c" alt="">
      <h3>Cutting Boards</h3>
    </div>
  </div>
</section>

<section id="contact">
  <h2>Contact</h2>
  <p>Email: hello@woodcraftstudio.com</p>
</section>

<footer>
  <p>© 2026 Woodcraft Studio</p>
</footer>

</body>
</html>
