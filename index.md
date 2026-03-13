---
layout: page
permalink: /
---

<style>
  /* ── Fonts ── */
  @import url('https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@400;600&family=DM+Sans:wght@300;400;500&display=swap');

  body {
    font-family: 'DM Sans', sans-serif;
    color: #1a1a2e;
    background: #fafaf8;
  }

  /* ── Hero Section ── */
  .hero {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    padding: 0 1rem 2rem;
  }

  .hero-photo {
    width: 320px;
    height: 320px;
    border-radius: 50%;
    object-fit: cover;
    border: 4px solid #c9a96e;
    box-shadow: 0 8px 30px rgba(0,0,0,0.12);
    margin-bottom: 1.5rem;
  }

  .hero h1 {
    font-family: 'Cormorant Garamond', serif;
    font-size: 2.8rem;
    font-weight: 600;
    margin: 0 0 0.4rem;
    letter-spacing: -0.5px;
    color: #1a1a2e;
  }

  .hero .tagline {
    font-size: 1.05rem;
    font-weight: 300;
    color: #555;
    margin: 0;
    max-width: 480px;
  }

  /* ── Section Titles ── */
  .section-title {
    font-family: 'Cormorant Garamond', serif;
    font-size: 1.8rem;
    font-weight: 600;
    color: #1a1a2e;
    border-bottom: 2px solid #c9a96e;
    display: inline-block;
    padding-bottom: 4px;
    margin-bottom: 1rem;
  }

  /* ── About Section ── */
  .about-section {
    max-width: 680px;
    margin: 2.5rem auto;
    padding: 0 1rem;
  }

  .about-section p {
    font-size: 1rem;
    line-height: 1.8;
    color: #333;
  }

  /* ── Schools Section ── */
  .schools-section {
    max-width: 680px;
    margin: 2.5rem auto;
    padding: 0 1rem;
  }

  .schools-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 1.5rem;
    align-items: center;
    margin-top: 1rem;
  }

  .school-logo {
    height: 60px;
    width: auto;
    max-width: 130px;
    object-fit: contain;
    filter: grayscale(20%);
    transition: filter 0.2s ease, transform 0.2s ease;
  }

  .school-logo:hover {
    filter: grayscale(0%);
    transform: scale(1.05);
  }

  /* ── Contact Section ── */
  .contact-section {
    max-width: 680px;
    margin: 2.5rem auto;
    padding: 0 1rem;
  }

  .contact-section p {
    font-size: 1rem;
    line-height: 1.8;
    color: #333;
  }

  .contact-section a {
    color: #c9a96e;
    text-decoration: none;
    font-weight: 500;
  }

  .contact-section a:hover {
    text-decoration: underline;
  }

  /* ── Resume Button ── */
  .resume-btn {
    display: inline-flex;
    align-items: center;
    gap: 0.5rem;
    margin-top: 1rem;
    padding: 0.65rem 1.4rem;
    background: #1a1a2e;
    color: #fff !important;
    border-radius: 6px;
    font-size: 0.95rem;
    font-weight: 500;
    text-decoration: none !important;
    transition: background 0.2s ease;
  }

  .resume-btn:hover {
    background: #c9a96e;
  }

  /* ── PDF Embed ── */
  .resume-embed {
    margin-top: 1.5rem;
    border: 1px solid #ddd;
    border-radius: 8px;
    overflow: hidden;
  }

  .resume-embed iframe {
    width: 100%;
    height: 520px;
    border: none;
    display: block;
  }

  /* ── Divider ── */
  .divider {
    max-width: 680px;
    margin: 0 auto;
    border: none;
    border-top: 1px solid #e5e5e5;
  }
</style>

<!-- ══════════════════ HERO ══════════════════ -->
<div class="hero">
  <!-- Replace the src below with your actual photo path, e.g. /files/profile.jpg -->
  <img class="hero-photo" src="/files/profile.jpg" alt="Photo of Isabella" />
  <h1>Hi, I'm Isabella McLaughlin</h1>
  <p class="tagline">Structural Design Engineer <br> M.S. Computer Science (in progress) <br> B.S. Mechanical Engineering</p>
</div>

<hr class="divider">

<!-- ══════════════════ ABOUT ME ══════════════════ -->
<div class="about-section">
  <h2 class="section-title">About Me</h2>
  <p>
    [Write your about me paragraph here.]
  </p>
</div>

<hr class="divider">

<!-- ══════════════════ EDUCATION  ══════════════════ -->
<div class="schools-section">
  <h2 class="section-title">Education</h2>
  <div class="schools-grid">

    <a href="/education">
      <img class="school-logo"
           src="/files/CU.jpg"
           alt="Columbia University" />
    </a>

    <a href="/education">
      <img class="school-logo"
           src="/files/UW.png"
           alt="University of Washington" />
    </a>

    <a href="/education">
      <img class="school-logo"
           src="/assets/images/school3-logo.png"
           alt="[School Name 3]" />
    </a>

  </div>
</div>

<hr class="divider">

<!-- ══════════════════ CONTACT ══════════════════ -->
<div class="contact-section">
  <h2 class="section-title">Contact</h2>
  <p>
    Feel free to reach out — I'd love to connect!<br>
    📧 <a href="mailto:your.email@example.com">your.email@example.com</a><br>
    💼 <a href="https://linkedin.com/in/yourprofile" target="_blank">LinkedIn</a>
  </p>

  <!-- Download button — update the href to your actual resume file path -->
  <a class="resume-btn" href="/files/IsabellaMcLaughlinResume.pdf" target="_blank">
    📄 View My Resume
  </a>

  <!-- Inline PDF preview — same file path as above -->
  <div class="resume-embed">
    <iframe src="/files/IsabellaMcLaughlinResume.pdf" title="Isabella's Resume"></iframe>
  </div>
</div>
