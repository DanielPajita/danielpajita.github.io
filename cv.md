---
title: "Currículum vitae"
permalink: /cv/
---

{% include menu.html %}

<style>
  /* ==================================================
     DISEÑO GENERAL
     ================================================== */

  .cv-page {
    --cv-card: #ffffff;
    --cv-border: #d8dee4;
    --cv-muted: #57606a;
    --cv-button: #17344b;
    --cv-button-text: #ffffff;
  }

  /* Compatibilidad con modo oscuro */
  html[data-theme="dark"] .cv-page {
    --cv-card: #161b22;
    --cv-border: #30363d;
    --cv-muted: #a0aab5;
    --cv-button: #245b80;
    --cv-button-text: #ffffff;
  }

  /* ==================================================
     ENCABEZADO
     ================================================== */

  .cv-page .cv-header {
    margin: 35px 0 45px;
  }

  .cv-page .cv-header h1 {
    font-size: clamp(36px, 5vw, 60px);
    font-weight: 700;
    letter-spacing: -1.5px;
    line-height: 1.15;
    margin: 0 0 15px;
    border: none;
  }

  .cv-page .cv-subtitle {
    color: var(--cv-muted);
    font-size: 18px;
    line-height: 1.6;
    margin: 0;
  }

  /* ==================================================
     TARJETAS
     ================================================== */

  .cv-page .cv-grid {
    display: grid;
    grid-template-columns:
      minmax(0, 1.5fr) minmax(260px, 1fr);
    gap: 22px;
    align-items: start;
  }

  .cv-page .cv-card {
    background: var(--cv-card);
    border: 1px solid var(--cv-border);
    border-radius: 18px;
    padding: 28px;
    min-width: 0;
  }

  .cv-page .cv-label {
    color: var(--cv-muted);
    font-size: 12px;
    font-weight: 700;
    letter-spacing: 1.5px;
    text-transform: uppercase;
    margin-bottom: 25px;
  }

  .cv-page .cv-card h2 {
    font-size: 23px;
    line-height: 1.35;
    margin: 0 0 18px;
    border: none;
  }

  .cv-page .cv-card p {
    line-height: 1.7;
    margin: 0 0 16px;
  }

  /* ==================================================
     FORMACIÓN ACADÉMICA
     ================================================== */

  .cv-page .cv-education {
    padding: 15px 0;
    border-bottom: 1px solid var(--cv-border);
  }

  .cv-page .cv-education:first-of-type {
    padding-top: 0;
  }

  .cv-page .cv-education:last-child {
    border-bottom: none;
    padding-bottom: 0;
  }

  .cv-page .cv-education h3 {
    font-size: 17px;
    margin: 0 0 6px;
    border: none;
  }

  .cv-page .cv-education p {
    color: var(--cv-muted);
    font-size: 14px;
    margin: 0;
  }

  /* ==================================================
     BOTÓN DE DESCARGA DEL CV
     ================================================== */

  .cv-page a.cv-download {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    gap: 10px;
    background: var(--cv-button);
    color: var(--cv-button-text) !important;
    font-weight: 600;
    text-decoration: none;
    border-radius: 28px;
    padding: 12px 20px;
    margin-top: 10px;
  }

  html[data-theme="dark"] .cv-page a.cv-download {
    color: #ffffff !important;
  }

  .cv-page .cv-download img {
    width: 24px;
    height: 24px;
    object-fit: contain;
    flex-shrink: 0;
  }

  .cv-page .cv-download:hover {
    opacity: 0.88;
    text-decoration: none;
  }

  .cv-page .cv-download:focus-visible {
    outline: 2px solid #58a6ff;
    outline-offset: 3px;
  }

  /* ==================================================
     VISUALIZACIÓN DEL PDF
     ================================================== */

  .cv-page .cv-preview {
    margin-top: 30px;
    border-top: 1px solid var(--cv-border);
    padding-top: 20px;
  }

  .cv-page .cv-preview summary {
    cursor: pointer;
    font-weight: 600;
    padding: 10px 0;
  }

  .cv-page .cv-preview iframe {
    width: 100%;
    height: 950px;
    border: 1px solid var(--cv-border);
    border-radius: 8px;
    margin-top: 15px;
    background: white;
  }

  /* ==================================================
     PANTALLAS PEQUEÑAS
     ================================================== */

  @media (max-width: 750px) {
    .cv-page .cv-grid {
      grid-template-columns: 1fr;
    }

    .cv-page .cv-card {
      padding: 22px;
    }

    .cv-page .cv-preview iframe {
      height: 650px;
    }

    .cv-page .cv-header {
      margin: 25px 0 30px;
    }
  }
</style>

<section class="cv-page">

  <!-- Encabezado -->
  <header class="cv-header">

    <h1>Currículum vitae</h1>

    <p class="cv-subtitle">
      Formación académica, experiencia profesional
      y métodos cuantitativos aplicados a la investigación.
    </p>

  </header>

  <!-- Tarjetas principales -->
  <div class="cv-grid">

    <!-- Resumen profesional -->
    <div class="cv-card">

      <div class="cv-label">Resumen profesional</div>

      <h2>
        Economista especializado en análisis económico y de datos
      </h2>

      <p>
        Economista con experiencia en análisis de datos,
        investigación aplicada y evaluación de políticas públicas,
        principalmente en el sector público peruano.
      </p>

      <p>
        Mi trabajo comprende el procesamiento de información
        estadística, el análisis econométrico y la aplicación
        de métodos cuantitativos al estudio de problemas
        económicos y sociales.
      </p>

      <!-- Descarga directa del PDF -->
      <a class="cv-download"
         href="{{ '/documentos/cv/CV_Daniel_Pajita.pdf' | relative_url }}"
         download="CV_Daniel_Pajita.pdf"
         type="application/pdf">

        <img src="{{ '/imagenes/cv.svg' | relative_url }}"
             alt=""
             aria-hidden="true"
             width="24"
             height="24">

        Descargar CV en PDF

      </a>

    </div>

    <!-- Formación académica -->
    <div class="cv-card">

      <div class="cv-label">Formación académica</div>

      <div class="cv-education">

        <h3>Maestría en Ciencia de Datos</h3>

        <p>
          Pontificia Universidad Católica de Chile
        </p>

        <p>En curso</p>

      </div>

      <div class="cv-education">

        <h3>Bachiller en Economía</h3>

        <p>
          Universidad Nacional del Callao
        </p>

        <p>2015</p>

      </div>

    </div>

  </div>

  <!-- Visualización opcional del CV -->
  <div class="cv-preview">

    <details>

      <summary>Ver currículum completo</summary>

      <iframe
        src="{{ '/documentos/cv/CV_Daniel_Pajita.pdf' | relative_url }}"
        title="Currículum vitae en PDF"
        loading="lazy">
      </iframe>

      <p>
        <a href="{{ '/documentos/cv/CV_Daniel_Pajita.pdf' | relative_url }}"
           target="_blank"
           rel="noopener noreferrer">
          Abrir PDF en una pestaña nueva
        </a>
      </p>

    </details>

  </div>

</section>