<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Welcome to the Hair Queendom</title>
  <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Montserrat', sans-serif;
      background: linear-gradient(to bottom, #000000, #4b0082);
      color: #fff;
      background-attachment: fixed;
      overflow-x: hidden;
    }
    header {
      text-align: center;
      padding: 50px 20px;
      background: url('https://images.unsplash.com/photo-1517957754647-65d6d1f24688?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=MnwxMTc3M3wwfDF8c2VhYmFja3x8c3Rvcm0lMjBsaWdodG5pbmd8ZW58MHx8fHwxNjk5ODU3NzYy&ixlib=rb-4.0.3&q=80&w=1080') no-repeat center center/cover;
      position: relative;
      overflow: hidden;
    }
    header::after {
      content: '';
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: rgba(0,0,0,0.4);
    }
    header h1 {
      position: relative;
      font-family: 'Great Vibes', cursive;
      font-size: 60px;
      text-shadow: 2px 2px 15px #8a2be2;
    }
    nav {
      text-align: center;
      margin: 20px 0;
    }
    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #ffccff;
      font-weight: bold;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #dda0dd;
    }
    section {
      padding: 50px 20px;
      max-width: 1000px;
      margin: auto;
    }
    .services, .contact {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
    }
    .service-card, .contact-card {
      background: rgba(75,0,130,0.3);
      border-radius: 10px;
      padding: 20px;
      margin: 15px;
      flex: 1 1 250px;
      text-align: center;
      transition: transform 0.3s, background 0.3s;
    }
    .service-card:hover, .contact-card:hover {
      transform: scale(1.05);
      background: rgba(138,43,226,0.4);
    }
    .service-card img {
      max-width: 100%;
      border-radius: 10px;
      filter: brightness(0.8);
      cursor: pointer;
    }
    .service-gallery {
      display: flex;
      overflow-x: auto;
      gap: 10px;
      margin-top: 10px;
    }
    .service-gallery img {
      height: 120px;
      border-radius: 10px;
      cursor: pointer;
      transition: transform 0.3s;
    }
    .service-gallery img:hover {
      transform: scale(1.1);
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #000;
      border-top: 2px solid #4b0082;
    }
    .ig-link {
      color: #ff99ff;
      text-decoration: none;
      font-weight: bold;
    }
    button {
      background: #8a2be2;
      border: none;
      padding: 10px 20px;
      border-radius: 5px;
      font-weight: bold;
      color: #fff;
      cursor: pointer;
      margin-top: 10px;
      transition: background 0.3s;
    }
    button:hover {
      background: #dda0dd;
    }
    .terms {
      background: rgba(0,0,0,0.6);
      border-radius: 10px;
      padding: 20px;
      margin: 20px auto;
      max-width: 800px;
      text-align: center;
      color: #eee;
    }
  </style>
</head>
<body>
  <header>
    <h1>Welcome to the Hair Queendom</h1>
  </header>
  <nav>
    <a href="#services">Services</a>
    <a href="#booking">Booking</a>
    <a href="#contact">Contact</a>
  </nav>
  <section id="services">
    <h2>Our Services</h2>
    <div class="services">
      <div class="service-card">
        <h3>Braids</h3>
        <p>Box braids and creative styles done with care and love.</p>
        <p>Price: $70–$150</p>
      </div>
      <div class="service-card">
        <h3>Dreads</h3>
        <p>Full or partial dread styles with gentle care for your hair health.</p>
        <p>Price: $50–$75</p>
      </div>
      <div class="service-card">
        <h3>Starter Locs</h3>
        <p>Perfect for beginners to start their loc journey with guidance.</p>
        <p>Price: $35–$60</p>
      </div>
      <div class="service-card">
        <h3>Wig Install</h3>
        <p>Clients' hair must already be braided down. Professional wig installation for flawless results.</p>
        <p>Price: $40</p>
      </div>
      <div class="service-card">
        <h3>Waxing</h3>
        <p>Eyebrow, lip, full face, and body waxing done gently.</p>
        <p>Price: $15–$80</p>
      </div>
      <div class="service-card">
        <h3>Piercing</h3>
        <p>Ear, nose, belly button, and custom jewelry piercings in a safe, friendly environment.</p>
        <p>Price: $10–$25</p>
      </div>
      <div class="service-card">
        <h3>Wash & Dry</h3>
        <p>Professional wash and dry service to keep hair healthy.</p>
        <p>Price: $10–$15</p>
      </div>
      <div class="service-card">
        <h3>Detangling</h3>
        <p>Gentle detangling service for healthy hair maintenance.</p>
        <p>Price: $10/hour</p>
      </div>
      <div class="service-card">
        <h3>Kids Hair</h3>
        <p>Wash & Dry, Detangling, or basic styles for kids.</p>
        <p>Price: $35</p>
      </div>
    </div>
  </section>
  <section id="booking">
    <h2>Booking</h2>
    <p>Abby is available Wednesday – Saturday, 12PM – 12AM.</p>
    <p>A $25 deposit is required before your session. You can pay online via Cash App ($keyshonna17) or in person. Friendly, flexible booking options are available!</p>
    <button onclick="window.open('https://cash.app/$keyshonna17', '_blank')">Pay Deposit via Cash App</button>
  </section>
  <section id="contact">
    <h2>Contact</h2>
    <p>Follow us on Instagram: <a href="https://instagram.com/abbytosweet" class="ig-link" target="_blank">@abbytosweet</a></p>
    <p>Email or call for more info! We’re happy to answer any questions and help you choose your perfect style.</p>
    <p>Phone: <a href="tel:3183618020" class="ig-link">318-361-8020</a></p>
  </section>
  <section class="terms">
    <h3>Friendly Terms & Services</h3>
    <p>Please arrive 5–10 minutes early for your appointment. Deposits secure your spot and are non-refundable if you cancel less than 24 hours in advance. Clients’ hair must be properly prepared for certain services (like Wig Install). Kids services are separate. We love making your hair and beauty experience fun, safe, and relaxing!</p>
  </section>
  <footer>
    <p>&copy; 2025 Welcome to the Hair Queendom</p>
  </footer>
</body>
</html>

 Welcome to the Hair Queendom
