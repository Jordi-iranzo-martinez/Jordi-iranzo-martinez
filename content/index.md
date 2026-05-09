---
title: "Técnico medioambiental, escritura, oposiciones"
---

<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Jordi Iranzo Martínez — Técnico Medioambiental</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600;700&family=DM+Sans:wght@300;400;500&display=swap" rel="stylesheet" />
  <style>
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    :root {
      --verde: #2d6a4f;
      --verde-claro: #52b788;
      --crema: #f8f5f0;
      --texto: #1a1a1a;
      --gris: #6b6b6b;
      --borde: #e0dbd2;
    }

    html { scroll-behavior: smooth; }

    body {
      font-family: 'DM Sans', sans-serif;
      background: var(--crema);
      color: var(--texto);
      line-height: 1.7;
    }

    /* NAV */
    nav {
      position: fixed;
      top: 0; left: 0; right: 0;
      z-index: 100;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 1.2rem 2.5rem;
      background: rgba(248, 245, 240, 0.92);
      backdrop-filter: blur(10px);
      border-bottom: 1px solid var(--borde);
    }

    .nav-logo {
      font-family: 'Playfair Display', serif;
      font-size: 1.1rem;
      font-weight: 700;
      color: var(--verde);
      text-decoration: none;
      letter-spacing: 0.01em;
    }

    .nav-links {
      display: flex;
      gap: 2rem;
      list-style: none;
    }

    .nav-links a {
      font-size: 0.9rem;
      font-weight: 500;
      color: var(--gris);
      text-decoration: none;
      letter-spacing: 0.03em;
      transition: color 0.2s;
    }

    .nav-links a:hover { color: var(--verde); }

    /* HERO */
    .hero {
      min-height: 100vh;
      display: grid;
      grid-template-columns: 1fr 1fr;
      align-items: center;
      max-width: 1100px;
      margin: 0 auto;
      padding: 8rem 2.5rem 4rem;
      gap: 4rem;
    }

    .hero-text { animation: fadeUp 0.8s ease both; }

    .hero-tag {
      display: inline-block;
      font-size: 0.78rem;
      font-weight: 500;
      letter-spacing: 0.12em;
      text-transform: uppercase;
      color: var(--verde-claro);
      margin-bottom: 1.2rem;
      background: rgba(82, 183, 136, 0.1);
      padding: 0.3rem 0.8rem;
      border-radius: 2rem;
    }

    h1 {
      font-family: 'Playfair Display', serif;
      font-size: clamp(2.4rem, 5vw, 3.6rem);
      font-weight: 700;
      line-height: 1.15;
      color: var(--texto);
      margin-bottom: 1.4rem;
    }

    h1 span { color: var(--verde); }

    .hero-desc {
      font-size: 1.05rem;
      color: var(--gris);
      max-width: 480px;
      margin-bottom: 2rem;
      font-weight: 300;
    }

    .hero-cta {
      display: inline-flex;
      align-items: center;
      gap: 0.5rem;
      background: var(--verde);
      color: white;
      padding: 0.9rem 1.8rem;
      border-radius: 0.5rem;
      text-decoration: none;
      font-weight: 500;
      font-size: 0.95rem;
      transition: background 0.2s, transform 0.2s;
    }

    .hero-cta:hover { background: #1f4d39; transform: translateY(-2px); }

    .hero-cta-sec {
      display: inline-flex;
      align-items: center;
      gap: 0.5rem;
      color: var(--verde);
      padding: 0.9rem 1.4rem;
      border-radius: 0.5rem;
      text-decoration: none;
      font-weight: 500;
      font-size: 0.95rem;
      border: 1.5px solid var(--verde);
      margin-left: 0.8rem;
      transition: background 0.2s, transform 0.2s;
    }

    .hero-cta-sec:hover { background: rgba(45,106,79,0.08); transform: translateY(-2px); }

    .hero-photo {
      animation: fadeUp 0.8s 0.2s ease both;
      display: flex;
      justify-content: center;
    }

    .photo-frame {
      width: 340px;
      height: 400px;
      border-radius: 1.5rem;
      overflow: hidden;
      box-shadow: 0 20px 60px rgba(45,106,79,0.15), 0 4px 16px rgba(0,0,0,0.08);
      background: #c8dfd3;
      position: relative;
    }

    .photo-frame img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      object-position: top;
    }

    .photo-placeholder {
      width: 100%;
      height: 100%;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      color: var(--verde);
      font-size: 0.85rem;
      gap: 0.5rem;
      opacity: 0.6;
    }

    .photo-placeholder svg { width: 48px; height: 48px; }

    /* SOBRE MÍ */
    .section {
      max-width: 1100px;
      margin: 0 auto;
      padding: 5rem 2.5rem;
    }

    .section-label {
      font-size: 0.78rem;
      font-weight: 500;
      letter-spacing: 0.12em;
      text-transform: uppercase;
      color: var(--verde-claro);
      margin-bottom: 0.8rem;
    }

    .section-title {
      font-family: 'Playfair Display', serif;
      font-size: clamp(1.8rem, 3vw, 2.4rem);
      font-weight: 700;
      margin-bottom: 2.5rem;
      color: var(--texto);
    }

    /* ÁREAS */
    .areas-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 1.5rem;
    }

    .area-card {
      background: white;
      border: 1px solid var(--borde);
      border-radius: 1rem;
      padding: 1.8rem;
      transition: box-shadow 0.2s, transform 0.2s;
    }

    .area-card:hover {
      box-shadow: 0 8px 32px rgba(45,106,79,0.1);
      transform: translateY(-3px);
    }

    .area-icon {
      font-size: 1.8rem;
      margin-bottom: 1rem;
    }

    .area-card h3 {
      font-family: 'Playfair Display', serif;
      font-size: 1.1rem;
      font-weight: 600;
      margin-bottom: 0.6rem;
      color: var(--texto);
    }

    .area-card p {
      font-size: 0.9rem;
      color: var(--gris);
      line-height: 1.6;
    }

    /* FORMACIÓN */
    .formacion-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 2rem;
      align-items: start;
    }

    .stat-box {
      background: var(--verde);
      color: white;
      border-radius: 1rem;
      padding: 2rem;
    }

    .stat-num {
      font-family: 'Playfair Display', serif;
      font-size: 3.5rem;
      font-weight: 700;
      line-height: 1;
      margin-bottom: 0.3rem;
    }

    .stat-label { font-size: 0.95rem; opacity: 0.85; }

    .formacion-list {
      list-style: none;
      display: flex;
      flex-direction: column;
      gap: 1rem;
    }

    .formacion-list li {
      display: flex;
      align-items: flex-start;
      gap: 0.8rem;
      font-size: 0.95rem;
      color: var(--gris);
    }

    .formacion-list li::before {
      content: "✦";
      color: var(--verde-claro);
      font-size: 0.7rem;
      margin-top: 0.35rem;
      flex-shrink: 0;
    }

    .formacion-list strong { color: var(--texto); }

    /* IDIOMAS */
    .idiomas-row {
      display: flex;
      flex-wrap: wrap;
      gap: 1rem;
      margin-top: 1.5rem;
    }

    .idioma-tag {
      background: white;
      border: 1px solid var(--borde);
      border-radius: 2rem;
      padding: 0.5rem 1.2rem;
      font-size: 0.88rem;
      display: flex;
      align-items: center;
      gap: 0.5rem;
    }

    .idioma-tag .nivel {
      font-size: 0.75rem;
      color: var(--verde-claro);
      font-weight: 500;
    }

    /* DIVIDER */
    .divider {
      border: none;
      border-top: 1px solid var(--borde);
      max-width: 1100px;
      margin: 0 auto;
    }

    /* CONTACTO */
    .contacto-box {
      background: white;
      border: 1px solid var(--borde);
      border-radius: 1.5rem;
      padding: 3rem;
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 3rem;
      align-items: center;
    }

    .contacto-box h2 {
      font-family: 'Playfair Display', serif;
      font-size: 1.9rem;
      margin-bottom: 1rem;
    }

    .contacto-box p {
      color: var(--gris);
      margin-bottom: 1.5rem;
      font-size: 0.95rem;
    }

    .email-link {
      display: inline-flex;
      align-items: center;
      gap: 0.5rem;
      color: var(--verde);
      font-weight: 500;
      text-decoration: none;
      font-size: 1rem;
      border-bottom: 1.5px solid var(--verde-claro);
      padding-bottom: 0.1rem;
    }

    /* NEWSLETTER */
    .newsletter-title {
      font-family: 'Playfair Display', serif;
      font-size: 1.2rem;
      margin-bottom: 0.5rem;
    }

    .newsletter-desc {
      font-size: 0.88rem;
      color: var(--gris);
      margin-bottom: 1.2rem;
    }

    .newsletter-form {
      display: flex;
      flex-direction: column;
      gap: 0.8rem;
    }

    .newsletter-form input {
      padding: 0.85rem 1.1rem;
      border: 1.5px solid var(--borde);
      border-radius: 0.5rem;
      font-family: 'DM Sans', sans-serif;
      font-size: 0.95rem;
      background: var(--crema);
      color: var(--texto);
      outline: none;
      transition: border-color 0.2s;
    }

    .newsletter-form input:focus { border-color: var(--verde); }

    .newsletter-form button {
      padding: 0.85rem;
      background: var(--verde);
      color: white;
      border: none;
      border-radius: 0.5rem;
      font-family: 'DM Sans', sans-serif;
      font-weight: 500;
      font-size: 0.95rem;
      cursor: pointer;
      transition: background 0.2s;
    }

    .newsletter-form button:hover { background: #1f4d39; }

    /* FOOTER */
    footer {
      text-align: center;
      padding: 2rem;
      font-size: 0.82rem;
      color: var(--gris);
      border-top: 1px solid var(--borde);
      margin-top: 2rem;
    }

    /* ANIMATIONS */
    @keyframes fadeUp {
      from { opacity: 0; transform: translateY(24px); }
      to { opacity: 1; transform: translateY(0); }
    }

    /* MOBILE */
    @media (max-width: 768px) {
      nav { padding: 1rem 1.5rem; }
      .nav-links { display: none; }
      .hero {
        grid-template-columns: 1fr;
        padding: 7rem 1.5rem 3rem;
        gap: 2.5rem;
        text-align: center;
      }
      .hero-photo { order: -1; }
      .photo-frame { width: 220px; height: 260px; }
      .hero-desc { margin: 0 auto 2rem; }
      .section { padding: 3.5rem 1.5rem; }
      .formacion-grid { grid-template-columns: 1fr; }
      .contacto-box { grid-template-columns: 1fr; padding: 2rem; gap: 2rem; }
    }
  </style>
</head>
<body>

  <!-- NAV -->
  <nav>
    <a href="#" class="nav-logo">Jordi Iranzo Martínez</a>
    <ul class="nav-links">
      <li><a href="#areas">Áreas</a></li>
      <li><a href="#formacion">Formación</a></li>
      <li><a href="#contacto">Contacto</a></li>
    </ul>
  </nav>

  <!-- HERO -->
  <section class="hero">
    <div class="hero-text">
      <span class="hero-tag">Técnico Medioambiental</span>
      <h1>Jordi<br><span>Iranzo</span><br>Martínez</h1>
      <p class="hero-desc">
        Especializado en normativa ambiental española y europea, biodiversidad, calidad ambiental y cambio climático, con experiencia en el sector público.
      </p>
      <a href="#contacto" class="hero-cta">Contactar</a>
      <a href="#areas" class="hero-cta-sec">Ver más</a>
    </div>
    <div class="hero-photo">
      <div class="photo-frame">
        <!-- Sustituye "tu_foto.jpg" por el nombre de tu archivo de imagen -->
        <!-- <img src="tu_foto.jpg" alt="Jordi Iranzo Martínez" /> -->
        <div class="photo-placeholder">
          <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5">
            <path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2"/>
            <circle cx="12" cy="7" r="4"/>
          </svg>
          <span>Añade tu foto aquí</span>
        </div>
      </div>
    </div>
  </section>

  <hr class="divider" />

  <!-- ÁREAS -->
  <section class="section" id="areas">
    <div class="section-label">Especialidades</div>
    <h2 class="section-title">Áreas de trabajo</h2>
    <div class="areas-grid">
      <div class="area-card">
        <div class="area-icon">🌿</div>
        <h3>Medio Ambiente</h3>
        <p>Normativa ambiental española y europea, biodiversidad, calidad ambiental, evaluaciones de impacto y cambio climático.</p>
      </div>
      <div class="area-card">
        <div class="area-icon">⚖️</div>
        <h3>Especialización Legal</h3>
        <p>Normativa ambiental y administrativa, cartografía, análisis de datos, informes técnicos y gestoría.</p>
      </div>
      <div class="area-card">
        <div class="area-icon">📝</div>
        <h3>Escritura</h3>
        <p>Redacción técnica y divulgativa sobre medio ambiente, sostenibilidad y temas de actualidad.</p>
      </div>
      <div class="area-card">
        <div class="area-icon">🏛️</div>
        <h3>Oposiciones</h3>
        <p>Preparación de oposiciones de medio ambiente y administrativos a nivel estatal, autonómico (Generalitat Valenciana) y local.</p>
      </div>
    </div>
  </section>

  <hr class="divider" />

  <!-- FORMACIÓN -->
  <section class="section" id="formacion">
    <div class="section-label">Trayectoria</div>
    <h2 class="section-title">Formación y habilidades</h2>
    <div class="formacion-grid">
      <div>
        <div class="stat-box" style="margin-bottom:1.5rem">
          <div class="stat-num">160+</div>
          <div class="stat-label">Certificados en política ambiental, cambio climático, desarrollo sostenible y herramientas digitales</div>
        </div>
        <div class="stat-box" style="background: #1f4d39;">
          <div class="stat-num">🌍</div>
          <div class="stat-label">ONU · Unión Europea · Google y otras instituciones</div>
        </div>
      </div>
      <div>
        <ul class="formacion-list">
          <li><span><strong>Sector público</strong> — Experiencia directa en administración y gestión ambiental</span></li>
          <li><span><strong>Cartografía y SIG</strong> — Análisis espacial y representación de datos geográficos</span></li>
          <li><span><strong>Análisis de datos</strong> — Herramientas digitales aplicadas al medio ambiente</span></li>
          <li><span><strong>Evaluaciones de impacto</strong> — Redacción de informes y estudios técnicos</span></li>
          <li><span><strong>Gestoría ambiental</strong> — Tramitación y asesoría en normativa</span></li>
        </ul>

        <div class="idiomas-row">
          <div class="idioma-tag">🇪🇸 Español <span class="nivel">Nativo</span></div>
          <div class="idioma-tag">🇻🇦 Valenciano <span class="nivel">Fluidez</span></div>
          <div class="idioma-tag">🇬🇧 Inglés <span class="nivel">Fluidez</span></div>
          <div class="idioma-tag">🇮🇹 Italiano <span class="nivel">Competencia</span></div>
          <div class="idioma-tag">🇵🇹 Portugués <span class="nivel">Competencia</span></div>
          <div class="idioma-tag">🇫🇷 Francés <span class="nivel">Competencia</span></div>
          <div class="idioma-tag">🇷🇺 Ruso <span class="nivel">Básico</span></div>
        </div>
      </div>
    </div>
  </section>

  <hr class="divider" />

  <!-- CONTACTO + NEWSLETTER -->
  <section class="section" id="contacto">
    <div class="contacto-box">
      <div>
        <h2 class="section-title" style="margin-bottom:0.8rem">¿En qué puedo ayudarte?</h2>
        <p>Me encantaría contribuir a mejorar el medio ambiente. Estoy abierto a colaboraciones y propuestas de cualquier tipo.</p>
        <a href="mailto:jordi.im@proton.me" class="email-link">
          ✉ jordi.im@proton.me
        </a>
      </div>
      <div>
        <div class="newsletter-title">Recibe mis escritos</div>
        <p class="newsletter-desc">Suscríbete para recibir novedades sobre medio ambiente, oposiciones y más.</p>
        <div class="newsletter-form">
          <input type="email" placeholder="tu@email.com" />
          <button type="button" onclick="this.textContent='✓ ¡Suscrito!'">Suscribirse</button>
        </div>
      </div>
    </div>
  </section>

  <footer>
    © 2026 Jordi Iranzo Martínez · <a href="mailto:jordi.im@proton.me" style="color:var(--verde);text-decoration:none">jordi.im@proton.me</a>
  </footer>

</body>
</html>

<div class="ml-embedded" data-form="N26omP"></div>
