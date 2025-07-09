<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Exceed Adventures</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header class="hero">
    <div class="overlay">
      <h1>Exceed Adventures</h1>
      <p>Explore, Embrace & Experience</p>
      <a href="#about" class="btn">Discover More</a>
    </div>
  </header>

  <nav>
    <ul>
      <li><a href="#about">About</a></li>
      <li><a href="#destinations">Destinations</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <section id="about" class="section">
    <h2>About Us</h2>
    <p>At Exceed Adventures, we curate unforgettable travel experiences that blend adventure, culture, and comfort. From the mysteries of India to the wonders of the world, your journey begins here.</p>
  </section>

  <section id="destinations" class="section">
    <h2>Top Destinations</h2>
    <div class="cards">
      <div class="card">
        <img src="https://source.unsplash.com/400x300/?india,travel" alt="India" />
        <h3>Incredible India</h3>
      </div>
      <div class="card">
        <img src="https://source.unsplash.com/400x300/?mountains,trekking" alt="Trekking" />
        <h3>Adventure Treks</h3>
      </div>
      <div class="card">
        <img src="https://source.unsplash.com/400x300/?beach,sunset" alt="Beaches" />
        <h3>Tropical Escapes</h3>
      </div>
    </div>
  </section>

  <section id="contact" class="section">
    <h2>Contact Us</h2>
    <form>
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Email" required />
      <textarea placeholder="Message"></textarea>
      <button type="submit">Send</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Exceed Adventures. All rights reserved.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>

