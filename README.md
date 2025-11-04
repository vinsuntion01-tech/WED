<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <link
      href="https://fonts.googleapis.com/css2?family=Raleway:wght@700&f…o+Script:wght@700&family=Quicksand:wght@300;500&display=swap"
      rel="stylesheet"
    />
    <title>Travel Goals</title>
    <style>
      body {
        background: #fff;
        color: #333;
        margin: 0;
        padding: 0;
      }

      /* ---------------- HEADER ---------------- */
      header {
        position: absolute;
        top: 0;
        width: 100%;
        display: flex;
        justify-content: space-between;
        align-items: flex-start;
        padding: 20px 60px; 
        z-index: 10;
      }

      .logo h1 {
        font-family: "Brush Script MT", cursive;
        font-size: 35px;
        color: #ffd700;
        letter-spacing: 2px;
      }

      .logo .tagline {
        font-size: 17px;
        color: #ffd700;
        margin-top: -4px;
        margin-left: 3px;
      }

      nav {
        margin-right: 150px; 
      }

      nav a {
        color: #ffd700;
        margin-left: 25px;
        font-size: 25px;
        font-weight: 500;
        text-decoration: none;
      }

      /* ---------------- HERO ---------------- */
      .hero {
        width: 100%;
        height: 600px;
        overflow: hidden;
        margin: 0;
        border-radius: 0;
        position: relative;
      }

      .hero img {
        width: 100%;
        height: 100%;
        object-fit: cover;
      }

      .hero-text {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        background: rgba(0, 0, 0, 0.55);
        color: #fff;
        padding: 70px 90px;
        text-align: center;
        border-radius: 10px;
      }

      .hero-text h2 {
        font-size: 50px;
        letter-spacing: 1px;
      }

      .hero-text p {
        font-size: 15px; 
        color: #fff;
        font-weight: 500;
        letter-spacing: 3px; 
        margin-top: 3px;
        
      }
      .hero-text button {
        background: yellow;
        border: none;
        padding: 10px 20px;
        margin-top: 20px;
        font-weight: bold;
        cursor: pointer;
        border-radius: 10px;
        font-size: 20px;
      }

      /* ---------------- HIGHLIGHTS ---------------- */
      .highlights {
        background: #d2f8f8;
        padding: 10px 20px;
        text-align: center;
        border-top: 5px solid #f7aaff;
        border-bottom: 5px solid #f7aaff;
      }

      .highlights h3 {
        font-size: 35px;
        margin-bottom: 20px;
      }

      .cards {
        display: flex;
        justify-content: center;
        gap: 25px;
        flex-wrap: wrap;
      }

      .card:hover {
        transform: scale(1.05);
      }

      .card img {
        width: 100%;
        height: 160px;
        object-fit: cover;
      }

      .card p {
        margin: 10px 0;
        color: #333;
        font-size: 14px;
      }
/* ---------------- DESTINATIONS ---------------- */
      .destinations {
        display: flex;
        justify-content: center;
        gap: 40px;
        flex-wrap: wrap;
      }

      .destination {
        text-align: center;
        width: 500px;
      }

      .destination img {
        width: 100%;
        height: 200px;
        object-fit: cover;
        border-radius: 15px;
        display: block;
        margin: 0 auto;
        transition: transform 0.3s ease;
      }

      .destination img:hover {
        transform: scale(1.05);
      }

      .destination p {
        margin-top: 10px;
        font-size: 25px;
        font-weight: bold;
        color: #fff;
        letter-spacing: 1px;
      }

      .miami-text {
        background: linear-gradient(to right, rgb(115, 112, 112) 51%, #0bb52a 30%);
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
      }

      .MUNICH-text {
        background: linear-gradient(to right, rgb(115, 112, 112) 46%, #0bb52a 50%);
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
      }

      .BARCELONA-text {
        background: linear-gradient(to right, rgb(115, 112, 112) 58%, #0bb52a 50%);
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
      }

      /* ---------------- FOOTER ---------------- */
      footer {
        background: #111;
        color: #fff;
        text-align: center;
        padding: 20px 0;
      }

      footer .social {
        margin-bottom: 30px;
      }

      footer .social img {
        width: 50px;
        margin: 0 10px;
        filter: invert(1);
      }
    </style>
  </head>

  <body>
    <header>
      <div class="logo">
        <h1>TRAVEL GOALS</h1>
        <p class="tagline">Let's explore the world together</p>
      </div>
      <nav>
        <a href="#">Destinations</a>
        <a href="#">About</a>
      </nav>
    </header>

    <main>
      <section class="hero">
        <img
          src="https://m.media-amazon.com/images/S/abs-image-upload-na/2/A…1526f16a06660190.w2000.h1402._CR203,430,1624,635_SX1500_.jpg"
          alt="Surfboard on water"
        />
        <div class="hero-text">
          <h2>JOE'S TRAVEL PAGE</h2>
          <p>LET'S EXPLORE THE WORLD TOGETHER</p>
          <button>Discover places</button>
        </div>
      </section>

      <section class="highlights">
        <h3>HIGHLIGHTS</h3>
        <div class="cards">
          <div class="destination">
            <img
              src="https://static.wixstatic.com/media/nsplsh_734f5671555a736d5…1,enc_avif,quality_auto/Image%20by%20Marc%20Fanelli-Isla.jpg"
              alt="Miami"
            />
            <p class="city-name miami-text">MIAMI USA</p>
          </div>

          <div class="destination">
            <img
src="https://image.stern.de/8203228/t/ic/v4/w1440/r1.7778/-/muenchen-airbnb.jpg"
              alt="MUNICH GERMANY"
            />
            <p class="city-name MUNICH-text">MUNICH GERMANY</p>
          </div>

          <div class="destination">
            <img
              src="https://www.sncf-connect.com/assets/styles/ratio_4_1_max_wi…a-carnelos-bg8tvw6nyyw-unsplash.jpg?h=12dc3527&itok=rcEepbBp"
              alt="BARCELONA SPAIN"
            />
            <p class="city-name BARCELONA-text">BARCELONA SPAIN</p>
          </div>
        </div>
      </section>
    </main>

    <footer>
      <div class="social">
        <a href="#"><img src="https://cdn-icons-png.flaticon.com/512/733/733558.png" alt="Instagram" /></a>
        <a href="#"><img src="https://cdn-icons-png.flaticon.com/512/733/733547.png" alt="Facebook" /></a>
      </div>
    </footer>
  </body>
</html>
