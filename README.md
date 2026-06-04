<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Car Showroom</title>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial, sans-serif;
}

body {
  background: #0f0f0f;
  color: white;
}

/* HEADER */
header {
  background: #111;
  padding: 15px 20px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap;
}

.logo {
  font-size: 24px;
  font-weight: bold;
  color: #ffcc00;
}

nav a {
  color: white;
  margin: 10px;
  text-decoration: none;
  font-size: 16px;
}

nav a:hover {
  color: #ffcc00;
}

/* HERO */
.hero {
  text-align: center;
  padding: 40px 20px;
}

.hero h1 {
  font-size: 40px;
  color: #ffcc00;
  letter-spacing: 2px;
}

.hero p {
  margin-top: 10px;
  color: #ccc;
}

/* IMAGE */
.car-img {
  width: 100%;
  max-width: 900px;
  display: block;
  margin: 30px auto;
  border-radius: 10px;
}

/* ABOUT */
.about {
  padding: 40px 20px;
  background: #1a1a1a;
}

.about h2 {
  color: #ffcc00;
  margin-bottom: 10px;
}

.about p {
  color: #ccc;
  line-height: 1.6;
}

/* FOOTER */
footer {
  text-align: center;
  padding: 15px;
  background: #111;
  color: #777;
}

/* MOBILE */
@media (max-width: 768px) {
  .hero h1 {
    font-size: 28px;
  }

  nav {
    width: 100%;
    text-align: center;
    margin-top: 10px;
  }
}
</style>

</head>

<body>

<header>
  <div class="logo">CAR WORLD</div>
  <nav>
    <a href="#">Home</a>
    <a href="#about">About</a>
    <a href="#">Menu</a>
    <a href="#">Contact</a>
  </nav>
</header>

<section class="hero">
  <h1>THE FUTURE OF DRIVING</h1>
  <p>Experience speed, luxury and performance</p>
</section>

<!-- Replace "car.jpg" with your image file -->
<img src="car.jpg" alt="Car Image" class="car-img">

<section id="about" class="about">
  <h2>About Us</h2>
  <p>
    Welcome to Car World. We bring you the latest and most powerful cars with advanced technology,
    stylish design and top performance. Our mission is to deliver quality vehicles that match your lifestyle.
    Explore our collection and find your dream car today.
  </p>
</section>

<footer>
  © 2026 Car World. All Rights Reserved.
</footer>

</body>
</html>
