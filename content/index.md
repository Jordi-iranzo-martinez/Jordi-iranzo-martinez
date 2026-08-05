---
title: Técnico de medio ambiente
description: Técnico ambiental ofrece ayuda en temas medioambientales, preparación y realización de oposiciones y gestiones administrativas.
---
     
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="color-scheme" content="light">
<meta name="theme-color" content="#E8E6D8">
<title>Jordi — Técnico ambiental | Consultoría, gestoría y Memlex</title>
<meta name="description" content="Jordi, técnico ambiental especializado en patrimonio natural, biodiversidad, calidad ambiental, cambio climático y derecho administrativo. Consultoría técnico-jurídica, gestoría, apoyo a oposiciones y Memlex.">
<meta property="og:title" content="Jordi — Técnico ambiental">
<meta property="og:description" content="Consultoría técnico-jurídica, gestoría, apoyo a oposiciones y Memlex.">
<meta property="og:type" content="website">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Fraunces:ital,opsz,wght@0,9..144,400;0,9..144,500;0,9..144,600;0,9..144,700;1,9..144,400;1,9..144,500&family=IBM+Plex+Sans:wght@400;500;600&family=IBM+Plex+Mono:wght@400;500;600&display=swap" rel="stylesheet">
<style>
  :root{
    --paper:#E8E6D8;
    --paper-2:#DEDBC7;
    --card:#F5F3E8;
    --ink:#1E2A1C;
    --ink-soft:#4E5A47;
    --moss:#45593A;
    --moss-deep:#2F3F27;
    --moss-tint:#9FB58A;
    --stamp:#9C3421;
    --sienna:#93692C;
    --line:rgba(30,42,28,0.16);
    --font-display:'Fraunces',serif;
    --font-body:'IBM Plex Sans',system-ui,sans-serif;
    --font-mono:'IBM Plex Mono',ui-monospace,monospace;
    --measure:1120px;
  }

  *{box-sizing:border-box;}
  html{scroll-behavior:auto;}
  @media (prefers-reduced-motion:no-preference){
    html{scroll-behavior:smooth;}
  }
  body{
    margin:0;
    background:var(--paper);
    color:var(--ink);
    font-family:var(--font-body);
    font-size:16px;
    line-height:1.6;
    -webkit-font-smoothing:antialiased;
  }
  img,svg{display:block;max-width:100%;}
  a{color:inherit;}
  h1,h2,h3{font-family:var(--font-display);margin:0;color:var(--ink);font-weight:600;letter-spacing:-0.01em;}
  p{margin:0;}
  ul{margin:0;padding:0;list-style:none;}

  .sr-only{
    position:absolute;width:1px;height:1px;padding:0;margin:-1px;
    overflow:hidden;clip:rect(0,0,0,0);white-space:nowrap;border:0;
  }

  :focus-visible{outline:2px solid var(--stamp);outline-offset:3px;}

  .grain{position:fixed;inset:0;width:100%;height:100%;pointer-events:none;z-index:95;mix-blend-mode:multiply;}

  /* layout */
  .section{padding:clamp(4rem,9vw,7.5rem) 1.5rem;position:relative;}
  .section__inner{max-width:var(--measure);margin-inline:auto;}
  .section--panel{background:var(--paper-2);}
  .section--dark{background:var(--ink);color:var(--paper);}
  .section--dark h2,.section--dark h3{color:var(--paper);}

  .eyebrow{
    display:inline-block;font-family:var(--font-mono);font-size:.75rem;
    letter-spacing:.14em;text-transform:uppercase;color:var(--moss);margin-bottom:1rem;
  }
  .section--dark .eyebrow{color:var(--moss-tint);}

  /* nav */
  .nav{
    position:sticky;top:0;z-index:90;
    display:flex;align-items:center;justify-content:space-between;
    padding:1.1rem 1.5rem;
    background:rgba(232,230,216,.88);
    -webkit-backdrop-filter:blur(8px);backdrop-filter:blur(8px);
    border-bottom:1px solid var(--line);
  }
  .nav__brand{display:flex;flex-direction:column;text-decoration:none;line-height:1.1;color:var(--ink);}
  .nav__brand strong{font-family:var(--font-display);font-size:1.35rem;font-weight:600;}
  .nav__brand span{font-family:var(--font-mono);font-size:.63rem;letter-spacing:.1em;text-transform:uppercase;color:var(--ink-soft);}
  .nav__links{display:flex;align-items:center;gap:1.75rem;}
  .nav__link{font-family:var(--font-mono);font-size:.8rem;letter-spacing:.04em;text-decoration:none;color:var(--ink);position:relative;}
  .nav__link::after{
    content:"";position:absolute;left:0;right:0;bottom:-4px;height:1px;background:var(--stamp);
    transform:scaleX(0);transform-origin:right;transition:transform .25s ease;
  }
  .nav__link:hover::after,.nav__link:focus-visible::after{transform:scaleX(1);transform-origin:left;}
  @media (max-width:780px){
    .nav__link{display:none;}
  }

  /* buttons */
  .btn{
    display:inline-flex;align-items:center;gap:.5rem;padding:.85rem 1.4rem;
    font-family:var(--font-mono);font-size:.78rem;letter-spacing:.08em;text-transform:uppercase;
    text-decoration:none;border-radius:2px;border:1px solid transparent;cursor:pointer;
    transition:transform .15s ease,background-color .15s ease,color .15s ease,border-color .15s ease;
  }
  .btn--primary{background:var(--stamp);color:var(--card);}
  .btn--primary:hover{background:var(--moss-deep);transform:translateY(-2px);}
  .btn--secondary{border-color:var(--ink);color:var(--ink);background:transparent;}
  .btn--secondary:hover{background:var(--ink);color:var(--paper);transform:translateY(-2px);}
  .section--dark .btn--secondary{border-color:var(--paper);color:var(--paper);}
  .section--dark .btn--secondary:hover{background:var(--paper);color:var(--ink);}

  /* hero */
  .hero{overflow:hidden;padding-top:clamp(3.5rem,8vw,6rem);}
  .hero__inner{position:relative;z-index:2;max-width:var(--measure);margin-inline:auto;}
  .hero h1{font-size:clamp(3.4rem,10vw,7.2rem);line-height:.92;font-weight:600;margin:.3rem 0 1rem;}
  .hero__subhead{
    font-family:var(--font-display);font-style:italic;font-weight:400;
    font-size:clamp(1.2rem,2.6vw,1.85rem);max-width:30ch;color:var(--moss-deep);margin-bottom:1.5rem;
  }
  .hero__lede{font-size:1.05rem;max-width:52ch;color:var(--ink-soft);margin-bottom:2rem;}
  .tags{display:flex;flex-wrap:wrap;gap:.6rem;margin-bottom:2.25rem;}
  .tag{
    font-family:var(--font-mono);font-size:.72rem;letter-spacing:.05em;text-transform:uppercase;
    padding:.45rem .8rem;border:1px solid var(--line);color:var(--ink-soft);background:rgba(245,243,232,.6);
  }
  .hero__ctas{display:flex;flex-wrap:wrap;gap:1rem;}

  .topo{position:absolute;top:-8%;right:-10%;width:min(58vw,620px);height:auto;z-index:1;opacity:.9;}
  .topo use{fill:none;stroke:var(--sienna);stroke-width:1.1;}

  /* about */
  .about__grid{display:grid;grid-template-columns:1.3fr 1fr;gap:3rem;align-items:start;}
  .about__grid p{max-width:56ch;margin-bottom:1.1rem;color:var(--ink-soft);font-size:1.02rem;}
  .about__grid h2{font-size:clamp(1.9rem,3.4vw,2.6rem);margin-bottom:1.5rem;max-width:26ch;}
  .about__side{display:flex;flex-direction:column;align-items:flex-start;gap:1.5rem;}

  .sello{
    border:2px solid var(--stamp);outline:1px solid var(--stamp);outline-offset:4px;
    color:var(--stamp);font-family:var(--font-mono);font-size:.78rem;letter-spacing:.1em;
    text-transform:uppercase;text-align:center;padding:.9rem 1.3rem;transform:rotate(-5deg);
    align-self:flex-start;margin:.6rem;
  }

  /* services */
  .services h2{font-size:clamp(1.9rem,3.4vw,2.6rem);margin-bottom:2.75rem;}
  .services__grid{display:grid;grid-template-columns:repeat(3,1fr);gap:2.75rem 1.75rem;}
  .ficha{
    position:relative;background:var(--card);border:1px solid var(--line);
    padding:2.1rem 1.6rem 1.75rem;display:flex;flex-direction:column;gap:.85rem;
    transition:transform .2s ease,box-shadow .2s ease,border-color .2s ease;
  }
  .ficha::before{
    content:attr(data-ref);position:absolute;top:-.85rem;left:1.4rem;
    background:var(--sienna);color:var(--card);font-family:var(--font-mono);
    font-size:.66rem;letter-spacing:.07em;text-transform:uppercase;padding:.28rem .55rem;
  }
  .ficha:hover{transform:translateY(-4px);box-shadow:0 16px 26px -20px rgba(30,42,28,.45);border-color:var(--sienna);}
  .ficha h3{font-size:1.3rem;}
  .ficha p{color:var(--ink-soft);font-size:.95rem;}
  .ficha__badge{
    position:absolute;top:-.85rem;right:1.4rem;background:var(--stamp);color:var(--card);
    font-family:var(--font-mono);font-size:.66rem;letter-spacing:.07em;text-transform:uppercase;
    padding:.28rem .55rem;transform:rotate(3deg);
  }

  /* memlex */
  .memlex__grid{display:grid;grid-template-columns:1fr 1fr;gap:3.5rem;align-items:center;}
  .memlex__grid h2{font-size:clamp(1.9rem,3.4vw,2.6rem);margin-bottom:1.25rem;}
  .memlex__grid .lede{max-width:48ch;color:var(--paper-2);font-size:1.02rem;margin-bottom:1.5rem;}
  .memlex__grid p a{color:var(--moss-tint);text-underline-offset:3px;}

  .flashcard{width:100%;max-width:360px;aspect-ratio:3/4;margin-inline:auto;}
  .flashcard-btn{
    display:block;width:100%;height:100%;cursor:pointer;
    background:none;border:none;padding:0;margin:0;font:inherit;color:inherit;text-align:inherit;
    perspective:1400px;
  }
  .flashcard-inner{
    display:block;position:relative;width:100%;height:100%;transform-style:preserve-3d;
    transition:transform .7s cubic-bezier(.4,.15,.2,1),box-shadow .3s ease;
  }
  .flashcard-btn:hover .flashcard-inner,.flashcard-btn:focus-visible .flashcard-inner{
    box-shadow:0 18px 30px -18px rgba(0,0,0,.5);
  }
  .flashcard.is-flipped .flashcard-inner{transform:rotateY(180deg);}
  .flashcard-face{
    display:block;position:absolute;inset:0;backface-visibility:hidden;-webkit-backface-visibility:hidden;
    border:1px solid var(--sienna);background:var(--card);color:var(--ink);
    padding:1.6rem;display:flex;flex-direction:column;justify-content:space-between;
  }
  .flashcard-back{transform:rotateY(180deg);}
  .flashcard .ref{font-family:var(--font-mono);font-size:.68rem;letter-spacing:.08em;text-transform:uppercase;color:var(--moss);}
  .flashcard .cite{font-family:var(--font-display);font-size:1.4rem;line-height:1.32;margin-top:.5rem;}
  .flashcard .hint{font-family:var(--font-mono);font-size:.65rem;color:var(--ink-soft);letter-spacing:.03em;}
  .flashcard .norm-text{font-size:.95rem;line-height:1.55;}
  .flashcard .norm-text strong{color:var(--stamp);}
  .flashcard .norm-text em{color:var(--moss);font-style:italic;}
  .flashcard .norm-text u{text-decoration-color:var(--sienna);}
  .flashcard .norm-text a{color:var(--moss-deep);text-decoration:underline;text-underline-offset:2px;}

  /* contact */
  .contact{text-align:center;}
  .contact__inner{max-width:640px;margin-inline:auto;display:flex;flex-direction:column;align-items:center;}
  .contact__inner h2{font-size:clamp(2.1rem,4vw,3rem);margin-bottom:1rem;}
  .contact__inner p{color:var(--ink-soft);max-width:44ch;margin-bottom:2rem;}
  .contact__inner .signature{margin-top:1.5rem;font-family:var(--font-display);font-style:italic;color:var(--ink-soft);}

  /* footer */
  footer{background:var(--ink);color:var(--paper-2);padding:2rem 1.5rem;text-align:center;}
  .foot__inner{max-width:var(--measure);margin-inline:auto;display:flex;flex-direction:column;gap:.4rem;}
  .foot__inner strong{font-family:var(--font-display);color:var(--paper);}
  .foot__inner a{color:var(--moss-tint);text-decoration:none;}
  .foot__inner small{font-family:var(--font-mono);font-size:.7rem;letter-spacing:.04em;color:var(--ink-soft);}

  /* responsive */
  @media (max-width:900px){
    .about__grid{grid-template-columns:1fr;gap:2rem;}
    .memlex__grid{grid-template-columns:1fr;}
    .memlex .flashcard{margin-top:1rem;}
    .services__grid{grid-template-columns:repeat(2,1fr);}
  }
  @media (max-width:600px){
    .services__grid{grid-template-columns:1fr;}
    .hero__ctas{flex-direction:column;align-items:stretch;}
    .hero__ctas .btn{justify-content:center;}
  }

  @media (prefers-reduced-motion:reduce){
    *,*::before,*::after{animation-duration:.001ms !important;transition-duration:.001ms !important;}
  }
</style>
</head>
<body>

<svg class="grain" aria-hidden="true" focusable="false" xmlns="http://www.w3.org/2000/svg">
  <filter id="grainFilter">
    <feTurbulence type="fractalNoise" baseFrequency="0.85" numOctaves="2" stitchTiles="stitch" result="noise"/>
    <feColorMatrix in="noise" type="matrix" values="0 0 0 0 0  0 0 0 0 0  0 0 0 0 0  0 0 0 0.035 0"/>
  </filter>
  <rect width="100%" height="100%" filter="url(#grainFilter)"/>
</svg>

<header class="nav">
  <a class="nav__brand" href="#top">
    <strong>Jordi</strong>
    <span>Técnico ambiental</span>
  </a>
  <nav class="nav__links" aria-label="Navegación principal">
    <a class="nav__link" href="#sobre-mi">Sobre mí</a>
    <a class="nav__link" href="#servicios">Servicios</a>
    <a class="nav__link" href="#memlex">Memlex</a>
    <a class="nav__link" href="#contacto">Contacto</a>
    <a class="btn btn--primary" href="mailto:jordi.im@proton.me">Escríbeme</a>
  </nav>
</header>

<main>

  <section class="hero section" id="top">
    <svg class="topo" viewBox="0 0 400 400" aria-hidden="true" focusable="false">
      <defs>
        <path id="ring" d="M200,58 C262,52 326,90 344,152 C362,216 340,282 283,321 C227,360 152,354 101,309 C50,264 40,193 71,138 C102,83 138,64 200,58 Z"/>
      </defs>
      <use href="#ring" transform="translate(200 200) scale(0.48) translate(-200 -200)" opacity="0.55"/>
      <use href="#ring" transform="translate(200 200) scale(0.62) translate(-200 -200)" opacity="0.42"/>
      <use href="#ring" transform="translate(200 200) scale(0.76) translate(-200 -200)" opacity="0.32"/>
      <use href="#ring" transform="translate(200 200) scale(0.90) translate(-200 -200)" opacity="0.24"/>
      <use href="#ring" transform="translate(200 200) scale(1.04) translate(-200 -200)" opacity="0.17"/>
      <use href="#ring" transform="translate(200 200) scale(1.18) translate(-200 -200)" opacity="0.10"/>
      <use href="#ring" transform="translate(200 200) scale(1.32) translate(-200 -200)" opacity="0.06"/>
    </svg>

    <div class="hero__inner">
      <p class="eyebrow">Técnico de medio ambiente</p>
      <h1>Jordi</h1>
      <p class="hero__subhead">Patrimonio natural, calidad ambiental, cambio climático y derecho administrativo, en un mismo expediente.</p>
      <p class="hero__lede">Consultoría técnico-jurídica, gestoría y apoyo gratuito a quienes preparan oposiciones. Y Memlex: tarjetas de memoria con la norma tal cual está escrita.</p>
      <ul class="tags">
        <li class="tag">Patrimonio natural y biodiversidad</li>
        <li class="tag">Calidad ambiental</li>
        <li class="tag">Cambio climático</li>
        <li class="tag">Derecho administrativo</li>
      </ul>
      <div class="hero__ctas">
        <a class="btn btn--primary" href="mailto:jordi.im@proton.me">Escríbeme</a>
        <a class="btn btn--secondary" href="#servicios">Ver servicios</a>
      </div>
    </div>
  </section>

  <section class="about section section--panel" id="sobre-mi">
    <div class="section__inner">
      <div class="about__grid">
        <div>
          <p class="eyebrow">Sobre mí</p>
          <h2>Dos idiomas que pocas veces se hablan bien a la vez</h2>
          <p>Soy técnico ambiental especializado en patrimonio natural y biodiversidad, calidad ambiental, cambio climático y derecho administrativo. La mayor parte de mi experiencia viene del sector público, tramitando expedientes y resolviendo justo lo que ahora ofrezco resolver para ti.</p>
          <p>Trabajo en la intersección donde casi nadie se siente cómodo: la que hay entre el informe técnico y el artículo de la ley que lo exige.</p>
        </div>
        <div class="about__side">
          <div class="sello" aria-hidden="true">Sector<br>público</div>
          <a class="btn btn--secondary" href="https://www.dropbox.com/scl/fo/0m7bpreh315tgx6utrqm9/ANplIn7xOGQuA_WF5KekhIs?rlkey=nuyjqnxp5i18zb0haqr5synme&amp;st=zhgf7l8p&amp;dl=0" target="_blank" rel="noopener noreferrer">Ver certificaciones</a>
        </div>
      </div>
    </div>
  </section>

  <section class="services section" id="servicios">
    <div class="section__inner">
      <p class="eyebrow">Servicios</p>
      <h2>¿En qué puedo ayudarte?</h2>
      <div class="services__grid">
        <article class="ficha" data-ref="Exp. CTJ">
          <h3>Consultoría técnico-jurídica</h3>
          <p>Estudios ambientales y de impacto ambiental, gestión de residuos y asesoramiento técnico-jurídico para proyectos y expedientes.</p>
        </article>
        <article class="ficha" data-ref="Exp. GES">
          <h3>Gestoría</h3>
          <p>Trámites administrativos, representación ante la administración y acompañamiento en la tramitación de expedientes.</p>
        </article>
        <article class="ficha" data-ref="Exp. OPO">
          <span class="ficha__badge">Gratis</span>
          <h3>Oposiciones</h3>
          <p>Dudas, resolución de preguntas y una charla si la necesitas. Apoyo para quien prepara oposiciones de la rama ambiental.</p>
        </article>
        <article class="ficha" data-ref="Ref. MLX">
          <h3>Memlex</h3>
          <p>Tarjetas de memoria con la literalidad de la norma, en RemNote y con formato enriquecido: negrita, cursiva, subrayado e hipervínculos.</p>
        </article>
        <article class="ficha" data-ref="Ref. DIV">
          <h3>Educación y divulgación</h3>
          <p>Artículos y contenidos de divulgación ambiental y jurídica, para acercar la norma y la técnica a quien las necesita.</p>
        </article>
        <article class="ficha" data-ref="Var.">
          <h3>Otros</h3>
          <p>Colaboraciones, propuestas y proyectos a medida. Si tienes una idea, hablemos.</p>
        </article>
      </div>
    </div>
  </section>

  <section class="memlex section section--dark" id="memlex">
    <div class="section__inner">
      <div class="memlex__grid">
        <div>
          <p class="eyebrow">Memlex</p>
          <h2>La norma, tal cual es</h2>
          <p class="lede">Tarjetas de memoria en RemNote con la literalidad del artículo: negrita, cursiva, subrayado e hipervínculos — para memorizar exactamente lo que dice la norma, ni una palabra de más ni de menos.</p>
          <p><a href="mailto:jordi.im@proton.me">¿Quieres probarlo? Escríbeme →</a></p>
        </div>
        <div>
          <div class="flashcard" id="flashcard-demo">
            <button class="flashcard-btn" type="button" aria-pressed="false" aria-label="Tarjeta de ejemplo de Memlex. Púlsala para ver el reverso con formato enriquecido.">
              <span class="flashcard-inner">
                <span class="flashcard-face flashcard-front">
                  <span class="ref">Ley 21/2013</span>
                  <span class="cite">Art. 35 — Evaluación ambiental ordinaria</span>
                  <span class="hint">↻ Pulsa para ver el reverso</span>
                </span>
                <span class="flashcard-face flashcard-back">
                  <span class="norm-text">Se someterán a evaluación ambiental <strong>ordinaria</strong> los proyectos que puedan tener efectos <em>significativos</em> sobre el <u>patrimonio natural</u>, incluidos aquellos con incidencia en <a href="#memlex">la Red Natura 2000</a>.</span>
                  <span class="hint">↻ Pulsa para volver</span>
                </span>
              </span>
            </button>
          </div>
          <p class="sr-only">Ejemplo de tarjeta Memlex: el anverso muestra la referencia del artículo; el reverso muestra el texto de la norma con negrita, cursiva, subrayado e hipervínculo.</p>
        </div>
      </div>
    </div>
  </section>

  <section class="contact section" id="contacto">
    <div class="section__inner">
      <div class="contact__inner">
        <p class="eyebrow">Contacto</p>
        <h2>Hablemos</h2>
        <p>Consultoría, gestoría, oposiciones, Memlex o una propuesta distinta — cuéntame qué necesitas.</p>
        <a class="btn btn--primary" href="mailto:jordi.im@proton.me">jordi.im@proton.me</a>
        <p class="signature">Un saludo, Jordi</p>
      </div>
    </div>
  </section>

</main>

<footer>
  <div class="foot__inner">
    <strong>Jordi</strong>
    <p>Técnico ambiental — patrimonio natural, calidad ambiental, cambio climático y derecho administrativo</p>
    <a href="mailto:jordi.im@proton.me">jordi.im@proton.me</a>
    <small>© 2026</small>
  </div>
</footer>

<script>
  document.querySelectorAll('.flashcard').forEach(function(card){
    var btn = card.querySelector('.flashcard-btn');
    if(!btn) return;
    btn.addEventListener('click', function(){
      var flipped = card.classList.toggle('is-flipped');
      btn.setAttribute('aria-pressed', flipped ? 'true' : 'false');
    });
  });
</script>

</body>
</html>
