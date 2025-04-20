<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Pizza Point</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #fff8f0;
      color: #333;
    }
    header {
      background-color: #e63946;
      color: white;
      padding: 1rem;
      text-align: center;
    }
    nav {
      background-color: #f1faee;
      padding: 1rem;
      text-align: center;
    }
    nav a {
      margin: 0 1rem;
      text-decoration: none;
      color: #1d3557;
      font-weight: bold;
    }
    section {
      padding: 2rem;
    }
    .menu {
      display: flex;
      flex-wrap: wrap;
      gap: 1rem;
      justify-content: center;
    }
    .pizza-item {
      border: 1px solid #ccc;
      padding: 1rem;
      width: 200px;
      background-color: #fff;
      border-radius: 8px;
    }
    form {
      max-width: 400px;
      margin: auto;
      display: flex;
      flex-direction: column;
    }
    input, textarea, button {
      margin: 0.5rem 0;
      padding: 0.5rem;
      font-size: 1rem;
    }
    footer {
      background-color: #e63946;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Pizza Point</h1>
    <p>Delicious pizza at your doorstep!</p>
  </header>
  <nav>
    <a href="#home">Home</a>
    <a href="#menu">Menu</a>
    <a href="#order">Order</a>
  </nav>

  <section id="home">
    <h2>Welcome to Pizza Point</h2>
    <p>We serve the best hot & cheesy pizzas in town. Check out our menu below!</p>
  </section>

  <section id="menu">
    <h2>Our Menu</h2>
    <div class="menu">
      <div class="pizza-item">
        <h3>Margherita</h3>
        <p>Classic cheese & tomato</p>
        <p>₹199</p>
      </div>
      <div class="pizza-item">
        <h3>Farmhouse</h3>
        <p>Veggies with cheese</p>
        <p>₹249</p>
      </div>
      <div class="pizza-item">
        <h3>Pepperoni</h3>
        <p>Spicy meat slices</p>
        <p>₹299</p>
      </div>
    </div>
  </section>

  <section id="order">
    <h2>Place Your Order</h2>
    <form>
      <input type="text" placeholder="Your Name" required />
      <input type="tel" placeholder="Phone Number" required />
      <textarea placeholder="Your Order Details" rows="4" required></textarea>
      <button type="submit">Submit</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Pizza Point | All rights reserved.</p>
  </footer>
</body>
</html>

