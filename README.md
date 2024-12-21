<!DOCTYPE html>
<html lang="id">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta
      name="description"
      content="Jelajahi kemegahan Garuda Wisnu Kencana (GWK) Cultural Park di Bali. Temukan sejarah, atraksi, dan keindahan budaya yang ditawarkannya."
    />
    <title>Garuda Wisnu Kencana Bali</title>
    <style>
      body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
        background-color: #f0f8ff;
        color: #333;
      }

      header {
        background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)),
          url("gwk_header.jpg") no-repeat center center/cover;
        height: 80vh;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        text-align: center;
        color: white;
        background-attachment: fixed; /* Parallax effect */
      }

      header h1 {
        font-size: 3.5rem;
        text-shadow: 3px 3px 7px rgba(0, 0, 0, 0.8);
      }

      header p {
        font-size: 1.2rem;
        margin-top: 10px;
        text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.7);
      }

      nav {
        background: #008080;
        color: white;
        padding: 1rem 0;
        text-align: center;
        position: sticky;
        top: 0;
        z-index: 1000;
      }

      nav a {
        color: white;
        margin: 0 20px;
        text-decoration: none;
        font-weight: bold;
      }

      nav a:hover {
        text-decoration: underline;
      }

      .hamburger {
        display: none;
        font-size: 30px;
        cursor: pointer;
        color: white;
      }

      .menu {
        display: flex;
        justify-content: center;
      }

      .menu a {
        padding: 10px 20px;
      }

      /* Mobile responsive menu */
      @media (max-width: 800px) {
        nav .menu {
          display: none;
          flex-direction: column;
          align-items: center;
        }

        nav .menu.active {
          display: flex;
        }

        nav .hamburger {
          display: block;
          position: absolute;
          top: -5px;
          right: 20px;
        }

        nav a {
          padding: 10px;
        }
      }

      .container {
        max-width: 1100px;
        margin: 20px auto;
        padding: 20px;
        background: #e6ffff;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        border-radius: 10px;
      }

      .section img {
        max-width: 50%;
        height: auto;
        display: block;
        margin: 20px 0;
        border: 3px solid #008080;
        border-radius: 10px;
      }

      footer {
        background-color: #222;
        color: white;
        padding: 40px 20px;
        text-align: center;
      }

      footer .footer-content {
        display: flex;
        justify-content: space-around;
        gap: 30px;
        flex-wrap: wrap;
        margin-bottom: 20px;
        text-align: left;
      }

      footer .footer-content div {
        max-width: 250px;
      }

      footer .footer-content h4 {
        font-size: 1.3rem;
        margin-bottom: 15px;
        color: #ffdd00;
        text-transform: uppercase;
      }

      footer .footer-content ul {
        list-style: none;
        padding: 0;
        margin: 0;
      }

      footer .footer-content ul li {
        margin: 10px 0;
      }

      footer .footer-content ul li a {
        color: #bbb;
        text-decoration: none;
      }

      footer .footer-content ul li a:hover {
        color: #ffdd00;
        text-decoration: underline;
      }

      footer .social-icons {
        margin-top: 20px;
      }

      footer .social-icons a {
        color: white;
        font-size: 1.5rem;
        margin: 0 15px;
        text-decoration: none;
        transition: color 0.3s;
      }

      footer .social-icons a:hover {
        color: #ffdd00;
      }

      footer p {
        margin-top: 20px;
        font-size: 0.9rem;
        color: #bbb;
      }

      footer p a {
        color: #ffdd00;
        text-decoration: none;
      }

      footer p a:hover {
        text-decoration: underline;
      }

      /* Responsiveness */
      @media (max-width: 100px) {
        footer .footer-content {
          flex-direction: column;
          text-align: center;
        }

        footer .footer-content div {
          margin-bottom: 20px;
        }

        footer .social-icons a {
          font-size: 1.2rem;
        }

        footer p {
          font-size: 1rem;
        }
      }
    </style>
  </head>
  <body>
    <header>
      <h1>Garuda Wisnu Kencana (GWK) Bali</h1>
      <p>Presented By Pixel</p>
    </header>

    <nav>
      <div class="hamburger" onclick="toggleMenu()">&#9776;</div>
      <div class="menu">
        <a href="#tentang">Tentang GWK</a>
        <a href="#sejarah">Sejarah</a>
        <a href="#atraksi">Atraksi</a>
        <a href="#galeri">Galeri</a>
      </div>
    </nav>

    <div class="container">
      <section id="tentang" class="section">
        <h2>Tentang GWK</h2>
        <p>
          Garuda Wisnu Kencana (GWK) Cultural Park adalah salah satu ikon paling
          terkenal di Bali, menampilkan patung besar Dewa Wisnu yang menunggangi
          burung Garuda. Dengan tinggi 121 meter, patung ini termasuk salah satu
          yang tertinggi di dunia.
        </p>
      </section>

      <section id="sejarah" class="section">
        <h2>Sejarah GWK</h2>
        <p>
          Pembangunan patung GWK dimulai pada tahun 1997, dirancang oleh
          pematung terkenal Bali, Nyoman Nuarta. Proyek ini bertujuan untuk
          menciptakan taman budaya yang mencerminkan hubungan harmonis antara
          manusia dan alam. Setelah melalui berbagai tantangan, patung ini
          selesai pada tahun 2018.
        </p>
      </section>

      <section id="atraksi" class="section">
        <h2>Atraksi di GWK</h2>
        <ul>
          <li>
            <strong>Patung GWK:</strong> Sebuah mahakarya seni dan teknik yang
            luar biasa.
          </li>
          <li>
            <strong>Lotus Pond:</strong> Area terbuka luas untuk acara budaya
            dan pertunjukan.
          </li>
          <li>
            <strong>Taman Indraloka:</strong> Menawarkan pemandangan indah
            lanskap Bali.
          </li>
          <li>
            <strong>Teater Jalanan:</strong> Nikmati pertunjukan tari
            tradisional Bali.
          </li>
        </ul>
        <img src="gwk_attractions.jpg" alt="Atraksi di GWK" />
      </section>

      <section id="galeri" class="section">
        <h2>Galeri</h2>
        <img src="gwk_gallery1.jpg" alt="Patung GWK" />
        <img src="gwk_gallery2.jpg" alt="Lotus Pond di GWK" />
        <img src="gwk_gallery3.jpg" alt="Taman Indraloka" />
      </section>
    </div>

    <footer>
      <div class="footer-content">
        <div>
          <h4>About Us</h4>
          <ul>
            <li><a href="#">Our Mission</a></li>
            <li><a href="#">Our History</a></li>
            <li><a href="#">Our Vision</a></li>
          </ul>
        </div>
        <div>
          <h4>Quick Links</h4>
          <ul>
            <li><a href="#tentang">Tentang GWK</a></li>
            <li><a href="#sejarah">Sejarah</a></li>
            <li><a href="#atraksi">Atraksi</a></li>
            <li><a href="#galeri">Galeri</a></li>
          </ul>
        </div>
        <div>
          <h4>Contact Us</h4>
          <ul>
            <li><a href="#">Email</a></li>
            <li><a href="#">Phone</a></li>
            <li><a href="#">Location</a></li>
          </ul>
        </div>
      </div>

      <div class="social-icons">
        <a href="#">🔵</a>
        <!-- Facebook Icon -->
        <a href="#">📸</a>
        <!-- Instagram Icon -->
        <a href="#">🐦</a>
        <!-- Twitter Icon -->
      </div>

      <p>
        &copy; 2024 GWK Bali. All Rights Reserved. |
        <a href="#">Privacy Policy</a>
      </p>
    </footer>

    <script>
      function toggleMenu() {
        const menu = document.querySelector(".menu");
        menu.classList.toggle("active");
      }
    </script>
  </body>
</html>
