<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>NEXPLORE - Your Travel Companion</title>
  <link rel="stylesheet" href="styles.css" />
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; }
    header, footer { background-color: #002B5B; color: white; padding: 1em; text-align: center; }
    nav a { margin: 0 1em; color: white; text-decoration: none; }
    .hero { padding: 4em 2em; background: url('hero.jpg') no-repeat center center/cover; color: white; text-align: center; }
    section { padding: 2em; }
    .features, .steps { display: flex; flex-wrap: wrap; gap: 2em; justify-content: center; }
    .feature, .step { border: 1px solid #ccc; padding: 1em; border-radius: 8px; width: 300px; }
    form { max-width: 400px; margin: auto; display: flex; flex-direction: column; gap: 1em; }
    input, textarea { padding: 0.5em; }
    button { padding: 0.5em; background-color: #002B5B; color: white; border: none; cursor: pointer; }
  </style>
</head>
<body>
  <header>
    <h1>NEXPLORE</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#features">Features</a>
      <a href="#how">How It Works</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero" id="home">
    <h2>Discover the world, safely and authentically</h2>
    <p>NEXPLORE connects you with trusted local guides for a personalized, scam-free experience — anywhere, anytime.</p>
    <button onclick="window.location.href='#contact'">Get Started</button>
  </section>

  <section id="features">
    <h2>App Features</h2>
    <div class="features">
      <div class="feature">
        <h3>Geo-Based Matching</h3>
        <p>Find local guides near your location in real-time.</p>
      </div>
      <div class="feature">
        <h3>In-App Chat</h3>
        <p>Communicate directly with your guide before and during your trip.</p>
      </div>
      <div class="feature">
        <h3>Built-in Translation</h3>
        <p>Break language barriers with live chat translation.</p>
      </div>
      <div class="feature">
        <h3>Secure & Verified</h3>
        <p>Every guide is screened and reviewed for your safety and peace of mind.</p>
      </div>
    </div>
  </section>

  <section id="how">
    <h2>How It Works</h2>
    <div class="steps">
      <div class="step">
        <h4>1. Sign Up</h4>
        <p>Create a free account to get started.</p>
      </div>
      <div class="step">
        <h4>2. Set Your Destination</h4>
        <p>Choose where you're going and what you're interested in.</p>
      </div>
      <div class="step">
        <h4>3. Match with a Guide</h4>
        <p>Get connected with local experts based on your preferences.</p>
      </div>
      <div class="step">
        <h4>4. Chat & Explore</h4>
        <p>Chat, plan, and enjoy an authentic travel experience.</p>
      </div>
    </div>
  </section>

  <section id="about">
    <h2>About NEXPLORE</h2>
    <p>NEXPLORE was created to bridge the gap between travelers and local culture. Our mission is to ensure safe, meaningful, and immersive travel experiences by empowering real connections between visitors and local experts.</p>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <form>
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <textarea placeholder="Your Message" rows="4" required></textarea>
      <button type="submit">Send</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 NEXPLORE. All rights reserved.</p>
  </footer>
</body>
</html>
