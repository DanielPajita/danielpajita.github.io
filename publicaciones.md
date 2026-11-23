---
title: "Publicaciones"
permalink: /publicaciones/
---

{% include menu.html %}

<style>

  /* ==================================================
     NAVEGACIÓN LATERAL
     ================================================== */

  .pub-layout {
    display: grid;
    grid-template-columns: 200px minmax(0, 1fr);
    gap: 32px;
    align-items: start;
    margin-top: 24px;
  }

  .pub-sidebar {
    position: sticky;
    top: 90px;
    max-height: calc(100vh - 110px);
    overflow-y: auto;
    font-size: 14px;
    padding-right: 15px;
    border-right: 1px solid #d8dee4;
  }

  .pub-sidebar a {
    display: block;
    padding: 7px 10px;
    color: inherit;
    text-decoration: none;
    line-height: 1.4;
    border-left: 2px solid transparent;
    transition: color 0.2s ease;
  }

  .pub-sidebar a:hover {
    color: #0969da;
    text-decoration: none;
  }

  .pub-sidebar a.active {
    color: #0969da;
    border-left-color: #0969da;
    font-weight: 600;
  }

  .pub-sidebar .pub-nav-main {
    font-weight: 600;
    margin-top: 6px;
  }

  .pub-content {
    min-width: 0;
  }

  .pub-content [id] {
    scroll-margin-top: 100px;
  }

  /* ==================================================
     PUBLICACIONES INSTITUCIONALES
     ================================================== */

  .pub-entity-list {
    margin-top: 20px;
  }

  .pub-entity {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    gap: 24px;
    padding: 22px 0;
    border-bottom: 1px solid #d8dee4;
  }

  .pub-entity:first-child {
    border-top: 1px solid #d8dee4;
  }

  .pub-entity-text {
    flex: 1;
    min-width: 0;
  }

  .pub-entity-text h3 {
    margin: 0 0 12px 0;
    border: none;
  }

  .pub-entity-text ul {
    margin: 0;
    padding-left: 18px;
  }

  .pub-entity-text li {
    margin-bottom: 10px;
    line-height: 1.65;
  }

  .pub-entity-logo {
    width: 170px;
    min-width: 170px;
    display: flex;
    justify-content: flex-end;
    align-items: flex-start;
  }

  .pub-entity-logo img {
    max-width: 150px;
    max-height: 56px;
    width: auto;
    height: auto;
    object-fit: contain;
    display: block;
  }

  /* ==================================================
     MODO OSCURO
     ================================================== */

  html[data-theme="dark"] .pub-entity {
    border-bottom: 1px solid #30363d;
  }

  html[data-theme="dark"] .pub-entity:first-child {
    border-top: 1px solid #30363d;
  }

  html[data-theme="dark"] .pub-sidebar {
    border-color: #30363d;
  }

  html[data-theme="dark"] .pub-sidebar a:hover,
  html[data-theme="dark"] .pub-sidebar a.active {
    color: #58a6ff;
  }

  html[data-theme="dark"] .pub-sidebar a.active {
    border-left-color: #58a6ff;
  }

  /* ==================================================
     DISEÑO RESPONSIVO
     ================================================== */

  @media (max-width: 900px) {

    .pub-layout {
      grid-template-columns: 170px minmax(0, 1fr);
      gap: 20px;
    }

    .pub-entity-logo {
      width: 120px;
      min-width: 120px;
    }

    .pub-entity-logo img {
      max-width: 110px;
    }

  }

  @media (max-width: 760px) {

    .pub-layout {
      grid-template-columns: 1fr;
      gap: 20px;
    }

    .pub-sidebar {
      position: static;
      max-height: none;
      border-right: none;
      border-bottom: 1px solid #d8dee4;
      padding-right: 0;
      padding-bottom: 15px;
    }

    .pub-entity {
      flex-direction: column-reverse;
      align-items: flex-start;
    }

    .pub-entity-logo {
      width: 100%;
      min-width: 0;
      justify-content: flex-start;
    }

    .pub-entity-logo img {
      max-width: 140px;
      max-height: 52px;
    }

  }

  /* ==================================================
     DESPLAZAMIENTO SUAVE
     ================================================== */

  @media (prefers-reduced-motion: no-preference) {
    html {
      scroll-behavior: smooth;
    }
  }

</style>

<!-- ==================================================
     CONTENEDOR PRINCIPAL
     ================================================== -->

<div class="pub-layout">

  <!-- MENÚ LATERAL -->

  <nav class="pub-sidebar" aria-label="Índice de publicaciones">

    <a href="#articulos-cientificos" class="pub-nav-main">
      Artículos científicos
    </a>

    <a href="#informes-institucionales" class="pub-nav-main">
      Informes y reportes institucionales
    </a>

    <a href="#colaboraciones" class="pub-nav-main">
      Colaboraciones y contribuciones
    </a>

  </nav>

  <!-- CONTENIDO PRINCIPAL -->

  <div class="pub-content" markdown="1">

# Publicaciones

Esta sección reúne artículos científicos, informes y reportes institucionales, y otras colaboraciones en las que he participado durante mi trayectoria académica y profesional.

## Artículos científicos
{: #articulos-cientificos}

**Sistema de demanda QUAIDS para bebidas no alcohólicas en hogares pobres y no pobres del Perú, 2012–2016**

**Pajita Dominguez, D.** & Baldeón Arrunátegui, A. (2017).

*Revista Horizonte Económico*, N.º 6. Instituto de Investigación de la Facultad de Ciencias Económicas de la Universidad Nacional del Callao, Callao, Perú.  
[Consultar publicación](https://fce.unac.edu.pe/unidad-de-investigacion/paper-de-investigadores/)

---

**Determinantes del embarazo y maternidad en los adolescentes del Perú**

Huarancca Bellido, M. & **Pajita Dominguez, D.** (2017).

*Revista Horizonte Económico*, N.º 5, pp. 113–126. Instituto de Investigación de la Facultad de Ciencias Económicas de la Universidad Nacional del Callao, Callao, Perú.  
[Consultar artículo (PDF)](https://drive.google.com/file/d/1rJe4pLNm_YngnIUXJ-1BMEzpHSc69IsL/view)

---

**La obesidad en el mundo**

Malo Serrano, M., Castillo, N. & **Pajita, D.** (2017).

*Anales de la Facultad de Medicina*, 78(2), pp. 67–72. Universidad Nacional Mayor de San Marcos, Lima, Perú.  
[Consultar artículo (PDF)](https://www.redalyc.org/pdf/379/37952105011.pdf) · [DOI](https://doi.org/10.15381/anales.v78i2.13213)

## Informes y reportes institucionales
{: #informes-institucionales}

Documentos técnicos en cuya elaboración he participado como parte de equipos de investigación, análisis económico y evaluación de políticas públicas durante mi trayectoria profesional.

<div class="pub-entity-list" markdown="0">

  <!-- PRODUCE -->

  <div class="pub-entity">

    <div class="pub-entity-text">

      <h3 id="produce">Ministerio de la Producción (PRODUCE)</h3>

      <ul>

        <li>
          <strong>Evaluación de Resultados de la Estrategia PROCOMPITE 2019–2023</strong> (2026).
          <a href="https://www.producempresarial.pe/evaluacion-de-resultados-de-la-estrategia-procompite-2019-2023/">Consultar</a>
        </li>

        <li>
          <strong>Evaluación de Resultados – Concurso MIPYME Digital 2020–2021</strong> (2026).
          <a href="https://www.producempresarial.pe/evaluacion-de-resultados-concurso-mipyme-digital-2020-2021/">Consultar</a>
        </li>

      </ul>

    </div>

    <div class="pub-entity-logo">
      <img src="{{ '/imagenes/produce.png' | relative_url }}" alt="PRODUCE">
    </div>

  </div>

  <!-- MTPE -->

  <div class="pub-entity">

    <div class="pub-entity-text">

      <h3 id="mtpe">Ministerio de Trabajo y Promoción del Empleo (MTPE)</h3>

      <ul>

        <li>
          <strong>Informe Anual del Empleo Juvenil en el Perú 2018</strong>.
          <a href="https://www.gob.pe/institucion/mtpe/informes-publicaciones/394337-informe-anual-del-empleo-juvenil-en-el-peru-2018">Consultar</a>
        </li>

        <li>
          <strong>Informe Anual del Empleo 2018</strong>.
          <a href="https://www.gob.pe/institucion/mtpe/informes-publicaciones/353779-informe-anual-del-empleo-2018">Consultar</a>
        </li>

        <li>
          <strong>Encuesta de Demanda Ocupacional 2018 – Informe Nacional</strong>.
          <a href="https://cdn.www.gob.pe/uploads/document/file/303305/EDO_2018_Nacional-vf.pdf">Consultar</a>
        </li>

        <li>
          <strong>Informe Anual del Empleo del Adulto Mayor en el Perú 2017</strong>.
          <a href="https://www.gob.pe/institucion/mtpe/informes-publicaciones/266352-informe-anual-del-empleo-del-adulto-mayor-en-el-peru-2017">Consultar</a>
        </li>

        <li>
          <strong>La Mujer en el Mercado Laboral Peruano – Informe Anual 2016</strong>.
          <a href="https://www.gob.pe/institucion/mtpe/informes-publicaciones/21767-informe-de-la-mujer-en-el-mercado-laboral">Consultar</a>
        </li>

      </ul>

    </div>

    <div class="pub-entity-logo">
      <img src="{{ '/imagenes/mtpe.png' | relative_url }}" alt="MTPE">
    </div>

  </div>

  <!-- OSINERGMIN -->

  <div class="pub-entity">

    <div class="pub-entity-text">

      <h3 id="osinergmin">Organismo Supervisor de la Inversión en Energía y Minería (Osinergmin)</h3>

      <ul>

        <li>
          <strong>Reporte Semestral de Monitoreo del Mercado de Gas Natural N.º 6 – Segundo semestre de 2014</strong>.
          <a href="https://www.gob.pe/institucion/osinergmin/informes-publicaciones/1298025-rsmm-gas-natural-n-6-segundo-semestre-de-2014">Consultar</a>
        </li>

      </ul>

    </div>

    <div class="pub-entity-logo">
      <img src="{{ '/imagenes/osinergmin.jpg' | relative_url }}" alt="Osinergmin">
    </div>

  </div>

</div>

## Colaboraciones y contribuciones
{: #colaboraciones}

Publicaciones académicas e institucionales en las que he contribuido mediante el apoyo a la investigación, procesamiento de información, análisis estadístico y estimaciones econométricas, con participación consignada en los reconocimientos de los documentos.

<div class="pub-entity-list" markdown="0">

  <!-- PNUD -->

  <div class="pub-entity">

    <div class="pub-entity-text">

      <h3 id="pnud">Programa de las Naciones Unidas para el Desarrollo (PNUD)</h3>

      <ul>

        <li>
          <strong>Políticas de protección social y laboral en el Perú. Una espiral de buenas intenciones, malos resultados y peores respuestas</strong> (2021).
          <a href="https://files.acquia.undp.org/public/migration/latinamerica/undp-rblac-PNUD_bckPapers17-OK.pdf">Consultar</a>
          <br>
          <strong>Contribución:</strong> apoyo en la investigación.
        </li>

        <li>
          <strong>Políticas de protección social y laboral en la República Dominicana</strong> (2021).
          <a href="https://files.acquia.undp.org/public/migration/latinamerica/undp-rblac-PNUD_bckPapers18-OK.pdf">Consultar</a>
          <br>
          <strong>Contribución:</strong> apoyo en el procesamiento estadístico.
        </li>

        <li>
          <strong>Políticas de protección social y laboral en Ecuador</strong> (2021).
          <a href="https://files.acquia.undp.org/public/migration/latinamerica/undp-rblac-PNUD_bckPapers19_e.pdf">Consultar</a>
          <br>
          <strong>Contribución:</strong> apoyo en el procesamiento estadístico.
        </li>

      </ul>

    </div>

    <div class="pub-entity-logo">
      <img src="{{ '/imagenes/PNUD.png' | relative_url }}" alt="PNUD">
    </div>

  </div>

  <!-- OIT -->

  <div class="pub-entity">

    <div class="pub-entity-text">

      <h3 id="oit">Organización Internacional del Trabajo (OIT)</h3>

      <ul>

        <li>
          <strong>Panorama Laboral 2019. América Latina y el Caribe</strong> (2020).
          <a href="https://www.ilo.org/es/publications/panorama-laboral-2019-america-latina-y-el-caribe">Consultar</a>
          <br>
          <strong>Contribución:</strong> consultoría en estadísticas y estimaciones.
        </li>

        <li>
          <strong>Mujeres en el mundo del trabajo: Retos pendientes hacia una efectiva equidad en América Latina y el Caribe (Panorama Laboral Temático, N.º 5)</strong> (2019).
          <a href="https://www.ilo.org/es/publications/mujeres-en-el-mundo-del-trabajo-retos-pendientes-hacia-una-efectiva-equidad">Consultar</a>
          <br>
          <strong>Contribución:</strong> manejo computacional y econométrico de las encuestas de hogares.
        </li>

      </ul>

    </div>

    <div class="pub-entity-logo">
      <img src="{{ '/imagenes/OIT.png' | relative_url }}" alt="OIT">
    </div>

  </div>

</div>

  </div>

</div>

<!-- ==================================================
     DETECCIÓN AUTOMÁTICA DE LA SECCIÓN ACTIVA
     ================================================== -->

<script>

document.addEventListener("DOMContentLoaded", function () {

  const links = Array.from(
    document.querySelectorAll(".pub-sidebar a")
  );

  const sections = links
    .map(link => document.getElementById(
      link.getAttribute("href").substring(1)
    ))
    .filter(Boolean);

  if (!sections.length) return;

  function updateActiveSection() {

    let current = sections[0].id;

    sections.forEach(section => {

      if (section.getBoundingClientRect().top <= 120) {
        current = section.id;
      }

    });

    // Detectar la última sección al llegar al final de la página.

    const scrollableHeight =
      document.documentElement.scrollHeight - window.innerHeight;

    const reachedBottom =
      scrollableHeight > 0 &&
      window.scrollY >= scrollableHeight - 5;

    if (reachedBottom) {
      current = sections[sections.length - 1].id;
    }

    // Actualizar el enlace activo.

    links.forEach(link => {

      const active =
        link.getAttribute("href") === "#" + current;

      link.classList.toggle("active", active);

      if (active) {
        link.setAttribute("aria-current", "location");
      } else {
        link.removeAttribute("aria-current");
      }

    });

  }

  window.addEventListener(
    "scroll",
    updateActiveSection,
    { passive: true }
  );

  window.addEventListener(
    "resize",
    updateActiveSection
  );

  window.addEventListener(
    "load",
    updateActiveSection
  );

  updateActiveSection();

});

</script>