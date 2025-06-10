<script>
  // Any additional logic can go here
</script>

<!-- Add Bootstrap CSS for icons -->
<link
  href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.css"
  rel="stylesheet"
/>

<style>
  nav {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: space-between;
    padding: 1rem 2rem;
    background-color: #0b0f1a;
    color: #fff;
    font-family: 'Segoe UI', sans-serif;
  }

  .logo {
    display: flex;
    align-items: center;
    font-weight: bold;
    color: #00ffa3;
    margin: 2.5rem 0 0 10vw; /* Relative margin */
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
  }
</style>

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
