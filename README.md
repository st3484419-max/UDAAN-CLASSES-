# UDAAN-CLASSES-

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Udaan Classes | Quality Tuition in Manoharpur</title>

  <meta name="description" content="Udaan Classes offers tuition for Classes 6 to 10 in Manoharpur, Jharkhand. Contact us for subject availability and fee details.">

  <meta name="theme-color" content="#102544">

  <style>
    :root {
      --navy: #102544;
      --blue: #1d4e89;
      --gold: #f3bd4b;
      --light: #f4f7fb;
      --white: #ffffff;
      --text: #263449;
      --muted: #65748b;
      --border: #e1e7f0;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth;
      scroll-padding-top: 85px;
    }

    body {
      font-family: Arial, Helvetica, sans-serif;
      background: var(--white);
      color: var(--text);
      line-height: 1.7;
    }

    a {
      text-decoration: none;
      color: inherit;
    }

    .container {
      width: min(1120px, 90%);
      margin: auto;
    }

    .topbar {
      background: #0a1930;
      color: #eaf0f8;
      padding: 9px 0;
      font-size: 13px;
    }

    .topbar-inner {
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 12px;
      flex-wrap: wrap;
    }

    header {
      background: var(--white);
      position: sticky;
      top: 0;
      z-index: 100;
      box-shadow: 0 3px 18px rgba(16, 37, 68, 0.08);
    }

    .navbar {
      min-height: 76px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 20px;
    }

    .brand {
      display: flex;
      align-items: center;
      gap: 12px;
    }

    .brand-icon {
      width: 47px;
      height: 47px;
      border-radius: 13px;
      display: grid;
      place-items: center;
      background: var(--navy);
      color: var(--gold);
      font-size: 25px;
      font-weight: 800;
    }

    .brand-name {
      color: var(--navy);
      font-size: 23px;
      font-weight: 800;
      line-height: 1.2;
    }

    .brand-tagline {
      color: var(--muted);
      font-size: 11px;
      letter-spacing: 1px;
      text-transform: uppercase;
    }

    .nav-links {
      display: flex;
      align-items: center;
      gap: 25px;
      font-size: 14px;
      font-weight: 700;
    }

    .nav-links a:hover {
      color: var(--blue);
    }

    .button {
      display: inline-flex;
      justify-content: center;
      align-items: center;
      gap: 8px;
      border: 0;
      border-radius: 8px;
      padding: 13px 21px;
      font-weight: 700;
      font-size: 14px;
      cursor: pointer;
      transition: transform 0.2s, background 0.2s;
    }

    .button:hover {
      transform: translateY(-2px);
    }

    .button-gold {
      background: var(--gold);
      color: #17253a;
    }

    .button-gold:hover {
      background: #ffd16b;
    }

    .button-blue {
      background: var(--blue);
      color: var(--white);
    }

    .button-outline {
      border: 1px solid rgba(255,255,255,0.55);
      color: var(--white);
      background: transparent;
    }

    .hero {
      color: var(--white);
      background:
        radial-gradient(circle at 85% 20%, rgba(61, 116, 184, 0.35), transparent 30%),
        linear-gradient(125deg, #0c1c34, #163b69 70%, #20558b);
      padding: 90px 0 85px;
      overflow: hidden;
    }

    .hero-grid {
      display: grid;
      grid-template-columns: 1.2fr 0.8fr;
      align-items: center;
      gap: 55px;
    }

    .eyebrow {
      display: inline-block;
      color: var(--gold);
      font-weight: 800;
      text-transform: uppercase;
      letter-spacing: 2px;
      font-size: 12px;
      margin-bottom: 18px;
    }

    .hero h1 {
      font-size: clamp(38px, 5vw, 61px);
      line-height: 1.12;
      letter-spacing: -1.5px;
      margin-bottom: 23px;
    }

    .hero h1 span {
      color: var(--gold);
    }

    .hero p {
      color: #e0e9f6;
      font-size: 17px;
      max-width: 580px;
      margin-bottom: 29px;
    }

    .hero-buttons {
      display: flex;
      gap: 13px;
      flex-wrap: wrap;
    }

    .hero-note {
      font-size: 12px;
      color: #c7d7eb;
      margin-top: 20px;
    }

    .hero-card {
      background: rgba(255,255,255,0.08);
      border: 1px solid rgba(255,255,255,0.19);
      border-radius: 22px;
      padding: 32px;
      backdrop-filter: blur(8px);
    }

    .hero-card h2 {
      font-size: 22px;
      margin-bottom: 8px;
    }

    .hero-card > p {
      font-size: 14px;
      margin-bottom: 23px;
    }

    .hero-feature {
      display: flex;
      gap: 13px;
      align-items: flex-start;
      padding: 15px 0;
      border-top: 1px solid rgba(255,255,255,0.15);
    }

    .feature-icon {
      background: rgba(243,189,75,0.15);
      color: var(--gold);
      width: 38px;
      height: 38px;
      flex-shrink: 0;
      display: grid;
      place-items: center;
      border-radius: 10px;
      font-size: 19px;
    }

    .hero-feature strong {
      display: block;
      font-size: 15px;
    }

    .hero-feature small {
      color: #cfdbec;
      font-size: 12px;
    }

    .trust-strip {
      background: var(--white);
      border-bottom: 1px solid var(--border);
      padding: 22px 0;
    }

    .trust-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 20px;
      text-align: center;
    }

    .trust-item strong {
      display: block;
      color: var(--navy);
      font-size: 16px;
    }

    .trust-item span {
      color: var(--muted);
      font-size: 13px;
    }

    section {
      padding: 78px 0;
    }

    .section-heading {
      text-align: center;
      max-width: 700px;
      margin: 0 auto 42px;
    }

    .section-heading .eyebrow {
      color: var(--blue);
      margin-bottom: 9px;
    }

    .section-heading h2 {
      color: var(--navy);
      font-size: clamp(28px, 3.5vw, 39px);
      line-height: 1.2;
      margin-bottom: 14px;
    }

    .section-heading p {
      color: var(--muted);
      font-size: 15px;
    }

    .classes-section {
      background: var(--light);
    }

    .class-grid {
      display: grid;
      grid-template-columns: repeat(5, 1fr);
      gap: 17px;
    }

    .class-card {
      background: var(--white);
      border: 1px solid var(--border);
      border-radius: 15px;
      padding: 25px 16px;
      text-align: center;
      transition: transform 0.2s, box-shadow 0.2s;
    }

    .class-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 12px 30px rgba(16,37,68,0.09);
    }

    .class-number {
      background: #e9f0fb;
      color: var(--blue);
      width: 55px;
      height: 55px;
      border-radius: 15px;
      display: grid;
      place-items: center;
      margin: 0 auto 15px;
      font-size: 24px;
      font-weight: 800;
    }

    .class-card h3 {
      color: var(--navy);
      font-size: 18px;
      margin-bottom: 6px;
    }

    .class-card p {
      font-size: 12px;
      color: var(--muted);
    }

    .about-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 55px;
      align-items: center;
    }

    .about-panel {
      background: var(--navy);
      color: var(--white);
      padding: 35px;
      border-radius: 20px;
      position: relative;
      overflow: hidden;
    }

    .about-panel::after {
      content: "";
      position: absolute;
      width: 180px;
      height: 180px;
      border: 30px solid rgba(243,189,75,0.12);
      border-radius: 50%;
      right: -65px;
      bottom: -75px;
    }

    .about-panel .eyebrow {
      margin-bottom: 10px;
    }

    .about-panel h3 {
      font-size: 28px;
      line-height: 1.3;
      margin-bottom: 16px;
    }

    .about-panel p {
      color: #d8e3f2;
      font-size: 14px;
    }

    .about-content h2 {
      color: var(--navy);
      font-size: 34px;
      line-height: 1.2;
      margin-bottom: 17px;
    }

    .about-content > p {
      color: var(--muted);
      margin-bottom: 23px;
      font-size: 15px;
    }

    .check-list {
      list-style: none;
      display: grid;
      gap: 13px;
    }

    .check-list li {
      display: flex;
      gap: 11px;
      align-items: flex-start;
      font-weight: 600;
      font-size: 14px;
    }

    .check {
      color: #178253;
      font-weight: 900;
    }

    .approach-section {
      background: var(--light);
    }

    .approach-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 22px;
    }

    .approach-card {
      background: var(--white);
      border: 1px solid var(--border);
      border-radius: 15px;
      padding: 27px;
    }

    .approach-icon {
      width: 49px;
      height: 49px;
      border-radius: 13px;
      display: grid;
      place-items: center;
      background: #e9f0fb;
      font-size: 23px;
      margin-bottom: 18px;
    }

    .approach-card h3 {
      color: var(--navy);
      margin-bottom: 9px;
      font-size: 18px;
    }

    .approach-card p {
      color: var(--muted);
      font-size: 14px;
    }

    .contact-section {
      background: var(--white);
    }

    .contact-grid {
      display: grid;
      grid-template-columns: 0.9fr 1.1fr;
      gap: 35px;
      align-items: start;
    }

    .contact-info {
      background: var(--navy);
      color: var(--white);
      padding: 34px;
      border-radius: 18px;
    }

    .contact-info h3 {
      font-size: 25px;
      margin-bottom: 10px;
    }

    .contact-info > p {
      color: #d6e2f2;
      font-size: 14px;
      margin-bottom: 25px;
    }

    .contact-item {
      display: flex;
      gap: 14px;
      padding: 18px 0;
      border-top: 1px solid rgba(255,255,255,0.16);
    }

    .contact-item-icon {
      color: var(--gold);
      font-size: 21px;
      width: 28px;
      flex-shrink: 0;
    }

    .contact-item strong {
      display: block;
      font-size: 14px;
      margin-bottom: 4px;
    }

    .contact-item a,
    .contact-item span {
      color: #d6e2f2;
      font-size: 14px;
      overflow-wrap: anywhere;
    }

    .contact-item a:hover {
      color: var(--gold);
    }

    .enquiry-form {
      padding: 32px;
      border: 1px solid var(--border);
      border-radius: 18px;
      box-shadow: 0 8px 30px rgba(16,37,68,0.05);
    }

    .enquiry-form h3 {
      color: var(--navy);
      font-size: 24px;
      margin-bottom: 6px;
    }

    .enquiry-form > p {
      color: var(--muted);
      font-size: 13px;
      margin-bottom: 22px;
    }

    .form-group {
      margin-bottom: 17px;
    }

    .form-group label {
      display: block;
      font-size: 13px;
      font-weight: 700;
      margin-bottom: 7px;
      color: var(--navy);
    }

    .form-group input,
    .form-group select,
    .form-group textarea {
      width: 100%;
      padding: 12px 13px;
      border: 1px solid #d6deea;
      border-radius: 8px;
      font: inherit;
      font-size: 14px;
      color: var(--text);
      background: var(--white);
      outline: none;
    }

    .form-group input:focus,
    .form-group select:focus,
    .form-group textarea:focus {
      border-color: var(--blue);
      box-shadow: 0 0 0 3px rgba(29,78,137,0.1);
    }

    .form-group textarea {
      resize: vertical;
      min-height: 95px;
    }

    .enquiry-form .button {
      width: 100%;
    }

    .form-note {
      font-size: 11px;
      color: var(--muted);
      margin-top: 12px;
    }

    .cta {
      background: #edf3fb;
      padding: 48px 0;
      text-align: center;
    }

    .cta h2 {
      color: var(--navy);
      font-size: clamp(26px, 3vw, 35px);
      margin-bottom: 10px;
    }

    .cta p {
      color: var(--muted);
      margin-bottom: 23px;
    }

    footer {
      background: #09172b;
      color: #d8e1ee;
      padding: 28px 0;
    }

    .footer-inner {
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 20px;
      flex-wrap: wrap;
    }

    .footer-brand {
      color: var(--white);
      font-size: 19px;
      font-weight: 800;
    }

    footer p {
      font-size: 12px;
      color: #b5c3d7;
    }

    .footer-links {
      display: flex;
      gap: 17px;
      flex-wrap: wrap;
      font-size: 12px;
    }

    .footer-links a:hover {
      color: var(--gold);
    }

    @media (max-width: 900px) {
      .hero-grid,
      .about-grid,
      .contact-grid {
        grid-template-columns: 1fr;
      }

      .hero-grid {
        gap: 35px;
      }

      .class-grid {
        grid-template-columns: repeat(3, 1fr);
      }

      .about-grid {
        gap: 30px;
      }

      .nav-links {
        gap: 14px;
      }
    }

    @media (max-width: 650px) {
      .topbar-inner {
        justify-content: center;
        text-align: center;
      }

      .navbar {
        min-height: auto;
        padding: 15px 0;
        align-items: flex-start;
        flex-direction: column;
        gap: 13px;
      }

      .nav-links {
        width: 100%;
        overflow-x: auto;
        padding-bottom: 5px;
        font-size: 13px;
      }

      .nav-links .button {
        padding: 9px 13px;
        white-space: nowrap;
      }

      .hero {
        padding: 60px 0;
      }

      .hero h1 {
        letter-spacing: -0.8px;
      }

      .hero-card {
        padding: 23px;
      }

      .trust-grid {
        grid-template-columns: 1fr;
        gap: 15px;
      }

      section {
        padding: 58px 0;
      }

      .class-grid {
        grid-template-columns: repeat(2, 1fr);
        gap: 12px;
      }

      .approach-grid {
        grid-template-columns: 1fr;
      }

      .about-panel,
      .contact-info,
      .enquiry-form {
        padding: 24px;
      }

      .about-content h2 {
        font-size: 29px;
      }

      .footer-inner {
        flex-direction: column;
        align-items: flex-start;
      }
    }
  </style>
</head>

<body>

  <div class="topbar">
    <div class="container topbar-inner">
      <span>📍 Manoharpur, Jharkhand</span>
      <span>Admissions & Enquiries: 92629 36926 | 92043 22772</span>
    </div>
  </div>

  <header>
    <div class="container navbar">
      <a class="brand" href="#home" aria-label="Udaan Classes home">
        <div class="brand-icon">U</div>
        <div>
          <div class="brand-name">Udaan Classes</div>
          <div class="brand-tagline">Learn Today. Lead Tomorrow.</div>
        </div>
      </a>

      <nav class="nav-links" aria-label="Main navigation">
        <a href="#home">Home</a>
        <a href="#classes">Classes</a>
        <a href="#about">About</a>
        <a href="#approach">Our Approach</a>
        <a href="#contact" class="button button-blue">Enquire Now</a>
      </nav>
    </div>
  </header>

  <main>
    <section class="hero" id="home">
      <div class="container hero-grid">
        <div>
          <span class="eyebrow">Welcome to Udaan Classes</span>

          <h1>Build Strong Foundations. <span>Achieve More.</span></h1>

          <p>
            Helping students from Classes 6 to 10 learn with confidence,
            strengthen their understanding, and work towards their academic goals.
          </p>

          <div class="hero
