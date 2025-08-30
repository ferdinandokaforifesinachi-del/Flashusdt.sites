# Flashusdt.sites
Codes 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>FlashUSDT - Crypto Investments</title>
  <style>
    /* General Styles */
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #0a0a0a;
      color: #e0e0e0;
      scroll-behavior: smooth;
    }
    h1, h2 {
      color: #00ff99;
      text-shadow: 0 0 10px #00ff99;
    }
    a {
      color: #00ff99;
      text-decoration: none;
    }
    section {
      padding: 80px 20px;
      max-width: 1000px;
      margin: auto;
      text-align: center;
    }
    /* Navbar */
    nav {
      position: fixed;
      top: 0;
      width: 100%;
      background: rgba(10,10,10,0.95);
      padding: 15px;
      display: flex;
      justify-content: space-around;
      align-items: center;
      z-index: 1000;
      border-bottom: 1px solid #00ff99;
      box-shadow: 0 0 15px #00ff99;
    }
    nav a {
      margin: 0 10px;
      font-weight: bold;
    }
    nav a:hover {
      color: #fff;
    }
    /* Hero */
    #home {
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
    }
    .btn {
      display: inline-block;
      padding: 12px 25px;
      margin-top: 20px;
      background: #00ff99;
      color: #000;
      border-radius: 8px;
      font-weight: bold;
      box-shadow: 0 0 15px #00ff99;
    }
    .btn:hover {
      background: #fff;
    }
    /* Community Buttons */
    .community-btn {
      display: inline-block;
      padding: 15px 30px;
      margin: 15px;
      border-radius: 10px;
      color: #fff;
      font-weight: bold;
      font-size: 18px;
      text-decoration: none;
      box-shadow: 0 0 20px;
    }
    .telegram { background: #0088cc; box-shadow: 0 0 20px #0088cc; }
    .discord { background: #5865F2; box-shadow: 0 0 20px #5865F2; }
    .twitter { background: #1DA1F2; box-shadow: 0 0 20px #1DA1F2; }
    /* Contact Form */
    form input, form textarea {
      width: 80%;
      padding: 12px;
      margin: 10px 0;
      background: #111;
      border: 1px solid #00ff99;
      border-radius: 6px;
      color: #fff;
    }
    form button {
      padding: 12px 25px;
      background: #00ff99;
      border: none;
      border-radius: 8px;
      font-weight: bold;
      color: #000;
      box-shadow: 0 0 15px #00ff99;
    }
    form button:hover {
      background: #fff;
    }
    /* Footer */
    footer {
      padding: 20px;
      text-align: center;
      border-top: 1px solid #00ff99;
      box-shadow: 0 0 10px #00ff99;
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav>
    <a href="#home">Home</a>
    <a href="#investments">Investments</a>
    <a href="#community">Community</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>

  <!-- Hero Section -->
  <section id="home">
    <h1>Welcome to FlashUSDT</h1>
    <p>Your Gateway to Smart Crypto Investing 🚀</p>
    <a href="#investments" class="btn">Get Started</a>
    <br><br>
    <!-- Example Crypto Ticker -->
    <iframe src="https://widget.coinlib.io/widget?type=horizontal_v2&theme=dark" width="100%" height="36" scrolling="auto" frameborder="0"></iframe>
  </section>

  <!-- Investments -->
  <section id="investments">
    <h2>Investments</h2>
    <p>Track, analyze, and grow your crypto portfolio in real time.</p>
    <br>
    <!-- Placeholder Chart -->
    <iframe src="https://www.tradingview.com/widgetembed/?frameElementId=tradingview_12345&symbol=BINANCE:BTCUSDT&interval=30&hidesidetoolbar=1&theme=dark" 
      width="100%" height="400" frameborder="0"></iframe>
  </section>

  <!-- Community -->
  <section id="community">
    <h2>Join Our Community</h2>
    <p>Connect with other investors and stay updated.</p>
    <a href="https://t.me/FlashUSDT" target="_blank" class="community-btn telegram">Join Telegram</a>
    <a href="https://discord.gg/FlashUSDT" target="_blank" class="community-btn discord">Join Discord</a>
    <a href="https://twitter.com/FlashUSDT" target="_blank" class="community-btn twitter">Follow Twitter</a>
  </section>

  <!-- About -->
  <section id="about">
    <h2>About FlashUSDT</h2>
    <p>FlashUSDT helps you explore crypto markets with ease, offering tools to monitor, invest, and connect with a vibrant community of traders worldwide.</p>
  </section>

  <!-- Contact -->
  <section id="contact">
    <h2>Contact Us</h2>
    <form>
      <input type="text" placeholder="Your Name" required><br>
      <input type="email" placeholder="Your Email" required><br>
      <textarea rows="5" placeholder="Your Message"></textarea><br>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2025 FlashUSDT. All Rights Reserved.</p>
  </footer>

</body>
</html>
