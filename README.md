<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>NEXPLORE - Your Travel Companion</title>
  <link rel="icon" href="https://cdn-icons-png.flaticon.com/512/854/854866.png" type="image/png">
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f9f9f9;
      color: #023047;
    }
    header, footer {
      background-color: #0077B6;
      color: white;
      padding: 1em;
      text-align: center;
    }
    nav a {
      margin: 0 1em;
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .hero {
      padding: 6em 2em;
      background: url('https://images.unsplash.com/photo-1507525428034-b723cf961d3e') no-repeat center center/cover;
      color: white;
      text-align: center;
    }
    .hero h2 {
      font-size: 2.5em;
      margin-bottom: 0.5em;
    }
    section {
      padding: 3em 2em;
      max-width: 1100px;
      margin: auto;
    }
    h2 {
      text-align: center;
      margin-bottom: 1em;
      color: #0077B6;
    }
    .features, .steps {
      display: flex;
      flex-wrap: wrap;
      gap: 2em;
      justify-content: center;
    }
    .feature, .step {
      background: white;
      border: 1px solid #ddd;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
      padding: 1.5em;
      border-radius: 12px;
      width: 300px;
      transition: transform 0.3s ease;
    }
    .feature:hover, .step:hover {
      transform: scale(1.03);
    }
    form {
      max-width: 500px;
      margin: auto;
      display: flex;
      flex-direction: column;
      gap: 1em;
      background: white;
      padding: 2em;
      border-radius: 12px;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    }
    input, textarea {
      padding: 0.75em;
      border: 1px solid #ccc;
      border-radius: 8px;
      font-size: 1em;
    }
    button {
      padding: 0.75em;
      background-color: #0077B6;
      color: white;
      border: none;
      border-radius: 8px;
      font-size: 1em;
      cursor: pointer;
    }
    button:hover {
      background-color: #023E8A;
    }
    @media (max-width: 768px) {
      .features, .steps {
        flex-direction: column;
        align-items: center;
      }
    }
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
    <p style="font-size: 1.2em;">Connect with local guides for personalized, scam-free travel — anytime, anywhere.</p>
    <button onclick="window.location.href='#contact'">Get Started</button>
  </section>

  <section id="features">
    <h2>App Features</h2>
    <div class="features">
      <div class="feature">
        <h3>🌍 Geo-Based Matching</h3>
        <p>Find local guides near your location in real-time.</p>
      </div>
      <div class="feature">
        <h3>💬 In-App Chat</h3>
        <p>Communicate directly with your guide before and during your trip.</p>
      </div>
      <div class="feature">
        <h3>🌐 Built-in Translation</h3>
        <p>Break language barriers with live chat translation.</p>
      </div>
      <div class="feature">
        <h3>🔒 Secure & Verified</h3>
        <p>Every guide is screened and reviewed for your peace of mind.</p>
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
        <p>Choose your location and interests.</p>
      </div>
      <div class="step">
        <h4>3. Match with a Guide</h4>
        <p>Get connected with verified locals based on your preferences.</p>
      </div>
      <div class="step">
        <h4>4. Chat & Explore</h4>
        <p>Message, plan, and enjoy a local adventure.</p>
      </div>
    </div>
  </section>

  <section id="about">
    <h2>About NEXPLORE</h2>
    <p style="max-width: 800px; margin: auto; text-align: center; font-size: 1.1em;">
      NEXPLORE was built with the mission to create meaningful connections through travel. We believe in empowering people to discover places not just as tourists, but as locals — with safety, trust, and authenticity leading the way.
    </p>
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
