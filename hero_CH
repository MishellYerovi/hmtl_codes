[![hero-ch.png](https://i.postimg.cc/CMtVR8Hv/hero-ch.png)](https://postimg.cc/t7hcfYcP)

<!-- =============== HERO CAROUSEL PREMIUM DE 3 SLIDES =============== -->
<section id="heroShowcase">
  <div class="hero-carousel">

    <!-- ====== SLIDE 1 ====== -->
    <div class="hero-slide active"
      style="background-image: url('https://images.pexels.com/photos/3419706/pexels-photo-3419706.jpeg?auto=compress&cs=tinysrgb&w=1600');">
      <div class="hero-overlay"></div>

      <div class="hero-content">
        <p class="hero-genre">Dramedia</p>
        <h1 class="hero-title">La Agencia</h1>
        <p class="hero-sub">Call My Agent</p>

        <!-- BOTONES -->
        <div class="hero-buttons">
          <a href="#estimate" class="hero-btn hero-btn-primary">Request a Free Estimate</a>
          <a href="tel:+10000000000" class="hero-btn hero-btn-secondary">Call Us</a>
        </div>
      </div>
    </div>

    <!-- ====== SLIDE 2 ====== -->
    <div class="hero-slide"
      style="background-image: url('https://images.pexels.com/photos/845457/pexels-photo-845457.jpeg?auto=compress&cs=tinysrgb&w=1600');">
      <div class="hero-overlay"></div>

      <div class="hero-content">
        <p class="hero-genre">Thriller</p>
        <h1 class="hero-title">Behind The Scenes</h1>
        <p class="hero-sub">Hidden Truths</p>

        <!-- BOTONES -->
        <div class="hero-buttons">
          <a href="#estimate" class="hero-btn hero-btn-primary">Request a Free Estimate</a>
          <a href="tel:+10000000000" class="hero-btn hero-btn-secondary">Call Us</a>
        </div>
      </div>
    </div>

    <!-- ====== SLIDE 3 ====== -->
    <div class="hero-slide"
      style="background-image: url('https://images.pexels.com/photos/7135205/pexels-photo-7135205.jpeg?auto=compress&cs=tinysrgb&w=1600');">
      <div class="hero-overlay"></div>

      <div class="hero-content">
        <p class="hero-genre">Documental</p>
        <h1 class="hero-title">Legacy Portraits</h1>
        <p class="hero-sub">True Stories</p>

        <!-- BOTONES -->
        <div class="hero-buttons">
          <a href="#estimate" class="hero-btn hero-btn-primary">Request a Free Estimate</a>
          <a href="tel:+10000000000" class="hero-btn hero-btn-secondary">Call Us</a>
        </div>
      </div>
    </div>

    <!-- ====== PAGINATION DOTS ====== -->
    <div class="hero-dots">
      <span class="dot active"></span>
      <span class="dot"></span>
      <span class="dot"></span>
    </div>

  </div>

  <!-- MENU INFERIOR -->
  <div class="hero-bottom-menu">
    <a href="#services">Servicios</a>
    <a href="#areas">Areas We Serve</a>
    <a href="#contact">Contact</a>
  </div>
</section>

<style>

  /* ====== GENERAL ====== */
  #heroShowcase {
    position: relative;
    width: 100%;
    height: 100vh;
    overflow: hidden;
    font-family: Arial, sans-serif;
  }

  .hero-carousel {
    width: 100%;
    height: 100%;
    position: relative;
  }

  /* ====== SLIDES ====== */
  .hero-slide {
    position: absolute;
    inset: 0;
    background-size: cover;
    background-position: center;
    opacity: 0;
    transform: scale(1);
    transition: opacity 1s ease, transform 1.2s ease;
  }

  .hero-slide.active {
    opacity: 1;
    transform: scale(1.04);
  }

  .hero-overlay {
    position: absolute;
    inset: 0;
    background: linear-gradient(to top, rgba(0,0,0,0.75) 0%, rgba(0,0,0,0.25) 40%, rgba(0,0,0,0) 100%);
  }

  /* ====== TEXTO ====== */
  .hero-content {
    position: absolute;
    bottom: 160px;
    left: 50%;
    transform: translateX(-50%);
    text-align: center;
    color: #fff;
  }

  .hero-genre {
    letter-spacing: 4px;
    font-size: 0.9rem;
    opacity: 0.8;
    margin-bottom: 8px;
  }

  .hero-title {
    font-size: 3rem;
    font-weight: 700;
    margin-bottom: 8px;
  }

  .hero-sub {
    font-size: 1.4rem;
    opacity: 0.85;
    margin-bottom: 25px;
  }

  /* ===== BOTONES ===== */
  .hero-buttons {
    display: flex;
    justify-content: center;
    gap: 18px;
  }

  .hero-btn {
    padding: 14px 30px;
    font-size: 1.0625rem; /* 17px en rem EXACTO */
    border-radius: 6px;
    text-decoration: none;
    font-weight: 600;
    transition: 0.3s;
  }

  .hero-btn-primary {
    background: #ffffff;
    color: #000;
  }

  .hero-btn-primary:hover {
    background: #e5e5e5;
  }

  .hero-btn-secondary {
    border: 2px solid #fff;
    color: #fff;
  }

  .hero-btn-secondary:hover {
    background: rgba(255,255,255,0.2);
  }

  /* ====== DOTS ====== */
  .hero-dots {
    position: absolute;
    bottom: 105px;
    left: 50%;
    transform: translateX(-50%);
    display: flex;
    gap: 8px;
  }

  .dot {
    width: 9px;
    height: 9px;
    border-radius: 50%;
    background: rgba(255,255,255,0.45);
    cursor: pointer;
  }

  .dot.active {
    background: #fff;
  }

  /* ====== MENÚ FIJO ====== */
  .hero-bottom-menu {
    position: absolute;
    bottom: 0;
    width: 100%;
    background: black;
    padding: 22px 0;
    display: flex;
    justify-content: center;
    gap: 40px;
  }

  .hero-bottom-menu a {
    color: white;
    text-decoration: none;
    font-size: 1rem;
    font-weight: 500;
    opacity: 0.85;
    transition: 0.3s;
  }

  .hero-bottom-menu a:hover {
    opacity: 1;
  }

  /* ===== RESPONSIVE ===== */
  @media (max-width: 768px) {
    .hero-title { font-size: 2rem; }
    .hero-sub { font-size: 1rem; }
    .hero-buttons { flex-direction: column; }
  }

</style>

<script>
  /* ========== HERO LOOP INFINITO ========== */

  let slides = document.querySelectorAll("#heroShowcase .hero-slide");
  let dots = document.querySelectorAll("#heroShowcase .dot");
  let current = 0;
  let slideInterval = 6000; // tiempo entre slides

  function showSlide(index) {
    slides.forEach(s => s.classList.remove("active"));
    dots.forEach(d => d.classList.remove("active"));

    slides[index].classList.add("active");
    dots[index].classList.add("active");
  }

  function nextSlide() {
    current = (current + 1) % slides.length;
    showSlide(current);
  }

  setInterval(nextSlide, slideInterval);

  dots.forEach((dot, i) => {
    dot.addEventListener("click", () => {
      current = i;
      showSlide(i);
    });
  });
</script>
