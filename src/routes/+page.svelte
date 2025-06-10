  <link
    href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.css"
    rel="stylesheet"
  />

  <style>
     :global(html, body) {
    margin: 0;
    padding: 0;
    background-color: #0b0f1a;
    height: 100%;
    width: 100%;
    box-sizing: border-box;
  }

  :global(*) {
    box-sizing: inherit;
  }
    /* Navigation Bar Styles */
    nav {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      justify-content: space-between;
      padding: 1rem 2rem;
      background-color: #0b0f1a;
      color: #fff;
      font-family: 'Segoe UI', sans-serif;
      border-bottom: 1px solid #009962;
    }

    .logo {
      display: flex;
      align-items: center;
      font-weight: bold;
      color: #00ffa3;
      margin: 2.5rem 0 0 10vw;
      height: 2.25rem;
      font-size: 1.1rem;
    }

    .logo img {
      height: 1.5rem;
      margin-right: 0.5rem;
    }

    .search-box {
      flex-grow: 1;
      margin: 2.5rem auto 0;
      display: flex;
      align-items: center;
      background: transparent;
      border: 1px solid #009962;
      border-radius: 0.625rem;
      padding: 0.5rem 1rem;
      max-width: 20rem;
      min-width: 14rem;
      height: 2.5rem;
    }

    .search-box input {
      flex: 1;
      background: transparent;
      border: none;
      outline: none;
      color: #fff;
      font-size: 1rem;
    }

    .search-box .bi {
      color: #00ffa3;
      margin-right: 0.5rem;
      font-size: 1.1rem;
    }

    .nav-links {
      display: flex;
      align-items: center;
      gap: 3rem;
      flex-wrap: wrap;
      justify-content: center;
      margin: 2.5rem 10vw 0 0;
    }

    .nav-links a {
      color: #ccc;
      text-decoration: none;
      font-size: 0.95rem;
      transition: color 0.3s ease;
      display: flex;
      align-items: center;
      gap: 0.4rem;
    }

    .nav-links a:hover,
    .nav-links a.active {
      color: #fff;
    }

    .nav-links .icon-right {
      order: 1;
    }

    /* Hero Section Styles */
    .hero-text {
      text-align: center;
      padding: 4rem 1rem 2rem;
      background: #0b0f1a;
      width: 100%;
      box-sizing: border-box;
    }

    .hero-text h1,
    .hero-text h2 {
      font-family: 'Readex Pro', sans-serif;
      font-weight: 400;
      margin: 0.25rem 0;
      color: #ECECEC;
      letter-spacing: 0;
    }

    /* Desktop Defaults */
    .hero-text h1 {
      font-size: 4.5rem; /* ~72px */
      line-height: 1.1;
    }

    .hero-text h2 {
      font-size: 4.5rem;
      line-height: 1.1;
    }

    /* Medium screens */
    @media (max-width: 1024px) {
      .hero-text h1,
      .hero-text h2 {
        font-size: 3.5rem;
      }
    }

    /* Tablet and smaller */
    @media (max-width: 768px) {
      nav {
        flex-direction: column;
        align-items: flex-start;
      }

      .logo,
      .search-box,
      .nav-links {
        margin: 1.5rem 0;
        align-self: center;
      }

      .nav-links {
        gap: 1.5rem;
      }

      .hero-text h1,
      .hero-text h2 {
        font-size: 2.5rem;
      }
    }

    /* Mobile screens */
    @media (max-width: 480px) {
      .hero-text {
        padding: 3rem 1rem 1.5rem;
      }

      .hero-text h1,
      .hero-text h2 {
        font-size: 1.8rem;
        line-height: 1.2;
      }
    }
  </style>
  <!-- Navigation Bar -->
  <nav>
    <div class="logo">
      <img src="/ri_coin-line.png" alt="CryptoHouse Logo" />
      <span>CRYPTOHOUSE</span>
    </div>

    <div class="search-box">
      <i class="bi bi-search"></i>
      <input type="text" placeholder="Explore" />
    </div>

    <div class="nav-links">
      <a href="#" class="active">Home</a>
      <a href="#">
        Profile
        <i class="bi bi-person icon-right"></i>
      </a>
      <a href="#">About Us</a>
      <a href="#">FAQ</a>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="hero-text">
    <h1>Stay Ahead with</h1>
    <h2>Personalized CryptoNews</h2>
  </section>