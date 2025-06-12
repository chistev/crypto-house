<script>
  import NavBar from '$lib/components/NavBar.svelte';
</script>

<NavBar />

<section class="hero-text">
  <h1>Stay Ahead with</h1>
  <h2>Personalized CryptoNews</h2>
</section>

<style>
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

  .hero-text h1 {
    font-size: 4.5rem;
    line-height: 1.1;
  }

  .hero-text h2 {
    font-size: 4.5rem;
    line-height: 1.1;
  }

  @media (max-width: 1024px) {
    .hero-text h1,
    .hero-text h2 {
      font-size: 3.5rem;
    }
  }

  @media (max-width: 768px) {
    .hero-text h1,
    .hero-text h2 {
      font-size: 2.5rem;
    }
  }

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
