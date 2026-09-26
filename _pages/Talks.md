---
permalink: /Talks/
title: "Conferences, workshops and seminars"
---
<style>
  .presentation-section {
    margin-bottom: 40px;
  }

  .presentation-section:first-of-type {
    margin-top: 1.2em;
  }

  .year-heading {
    font-size: 1.1em;
    font-weight: bold;
    margin-bottom: 15px;
    border-bottom: 1px solid #000;
    padding-bottom: 3px;
    color: #000;
    display: flex;
    justify-content: space-between;
    align-items: center;
    cursor: pointer;
    user-select: none;
  }

  .year-heading .toggle-year-wrap {
    display: flex;
    align-items: center;
    gap: 8px;
  }

  .year-heading .toggle-hint {
    font-size: 0.78em;
    color: #bbb;
    font-weight: normal;
    font-style: italic;
  }

  .year-heading .toggle-year {
    color: #800020;
    font-size: 0.95em;
    font-family: Arial, sans-serif;
    outline: 1.2px solid #800020;
    border-radius: 3px;
    padding: 0px 3px;
    line-height: 1;
    display: inline-block;
    transition: background 0.15s;
  }

  .year-heading:hover .toggle-year {
    background: rgba(128, 0, 32, 0.08);
  }

  .presentation {
    display: grid;
    grid-template-columns: 55px minmax(0, 1fr) auto;
    column-gap: 24px;
    align-items: baseline;
    margin-bottom: 10px;
  }

  .presentation-date {
    font-weight: normal;
    color: #000;
    white-space: nowrap;
  }

  .presentation-details {
    color: #000;
    line-height: 1.5;
  }

  .presentation-place {
    color: #888;
    font-size: 0.92em;
    line-height: 1.5;
    text-align: right;
    white-space: nowrap;
  }

  @media (max-width: 640px) {
    .presentation {
      grid-template-columns: 50px minmax(0, 1fr);
      row-gap: 2px;
      margin-bottom: 14px;
    }

    .presentation-place {
      grid-column: 2;
      text-align: left;
      white-space: normal;
    }
  }
</style>

<div class="presentation-section">
  <div class="year-heading" onclick="toggleYear(this)">
    <span>2026</span>
    <span class="toggle-year-wrap"><span class="toggle-hint">Click to collapse</span><span class="toggle-year">▾</span></span>
  </div>
  <div class="year-content">
    <div class="presentation">
      <div class="presentation-date">17/08</div>
      <div class="presentation-details">
        PRISM/STEG Brown Bag series, <a href="https://commerce.uct.ac.za/prism/about" target="_blank" style="color: #800020;">University of Cape Town (UCT)</a>
      </div>
      <div class="presentation-place">Cape Town, South Africa</div>
    </div>
    <div class="presentation">
      <div class="presentation-date">23/07</div>
      <div class="presentation-details">
        Seminar, <a href="https://stat.unido.org/unido-statistics" target="_blank" style="color: #800020;">United Nations Industrial Development Organization (UNIDO)</a>
      </div>
      <div class="presentation-place">Vienna, Austria</div>
    </div>
    <div class="presentation">
      <div class="presentation-date">20/04</div>
      <div class="presentation-details">
        Eleventh Joint Research Workshop, <span style="color: #800020;">Paris 1 - FESP (Cairo University)</span>
      </div>
      <div class="presentation-place">Paris, France</div>
    </div>
    <div class="presentation">
      <div class="presentation-date">17/04</div>
      <div class="presentation-details">
        EPADAL seminar, <a href="http://www.iheal.univ-paris3.fr/fr/node/265" target="_blank" style="color: #800020;">Institute of Latin American Studies (Paris 3)</a>
      </div>
      <div class="presentation-place">Paris, France</div>
    </div>
    <div class="presentation">
      <div class="presentation-date">11/04</div>
      <div class="presentation-details">
        Ma thèse en scène, <a href="https://www.citeco.fr/" target="_blank" style="color: #800020;">Cité de l'économie</a>
      </div>
      <div class="presentation-place">Paris, France</div>
    </div>
    <div class="presentation">
      <div class="presentation-date">18/03</div>
      <div class="presentation-details">
        Internal seminar, <a href="https://dipartimenti.unicatt.it/politica_economica?rdeLocaleAttr=en" target="_blank" style="color: #800020;">Università Cattolica del Sacro Cuore</a>
      </div>
      <div class="presentation-place">Milan, Italy</div>
    </div>
  </div>
</div>

<div class="presentation-section">
  <div class="year-heading" onclick="toggleYear(this)">
    <span>2025</span>
    <span class="toggle-year-wrap"><span class="toggle-hint">Click to expand</span><span class="toggle-year">▸</span></span>
  </div>
  <div class="year-content" style="display:none;">
    <div class="presentation">
      <div class="presentation-date">16/12</div>
      <div class="presentation-details">
        Internal seminar, <a href="https://unu.edu/merit/event/unu-merit-internal-conference-2025" target="_blank" style="color: #800020;">United Nations University — MERIT</a>
      </div>
      <div class="presentation-place">Maastricht, Netherlands</div>
    </div>
    <div class="presentation">
      <div class="presentation-date">25/09</div>
      <div class="presentation-details">
        Research week, <a href="https://unu.edu/merit/event/unu-merit-internal-conference-2025" target="_blank" style="color: #800020;">United Nations University — MERIT</a>
      </div>
      <div class="presentation-place">Maastricht, Netherlands</div>
    </div>
    <div class="presentation">
      <div class="presentation-date">10/07</div>
      <div class="presentation-details">
        Internal seminar, <a href="https://dipartimenti.unicatt.it/politica_economica?rdeLocaleAttr=en" target="_blank" style="color: #800020;">Università Cattolica del Sacro Cuore</a>
      </div>
      <div class="presentation-place">Milan, Italy</div>
    </div>
    <div class="presentation">
      <div class="presentation-date">19/06</div>
      <div class="presentation-details">
        Internal seminar, <a href="https://internalsem.wordpress.com/2025/06/12/yanis-bekhti/" target="_blank" style="color: #800020;">Paris 1 Panthéon-Sorbonne University</a>
      </div>
      <div class="presentation-place">Paris, France</div>
    </div>
  </div>
</div>

<div class="presentation-section">
  <div class="year-heading" onclick="toggleYear(this)">
    <span>2024</span>
    <span class="toggle-year-wrap"><span class="toggle-hint">Click to expand</span><span class="toggle-year">▸</span></span>
  </div>
  <div class="year-content" style="display:none;">
    <div class="presentation">
      <div class="presentation-date">15/09</div>
      <div class="presentation-details">
        Rethinking Development in Latin America and the Caribbean: A Mexican Perspective, <a href="https://www.gob.mx/sre/prensa/young-researchers-from-three-continents-propose-solutions-to-latin-american-and-caribbean-challenges?idiom=en" target="_blank" style="color: #800020;">UAM · CAF · YSI</a>
      </div>
      <div class="presentation-place">Mexico City, Mexico</div>
    </div>
    <div class="presentation">
      <div class="presentation-date">26/06</div>
      <div class="presentation-details">
        Internal seminar, <a href="https://dipartimenti.unicatt.it/politica_economica?rdeLocaleAttr=en" target="_blank" style="color: #800020;">Università Cattolica del Sacro Cuore</a>
      </div>
      <div class="presentation-place">Milan, Italy</div>
    </div>
  </div>
</div>

<script>
  function toggleYear(heading) {
    const content = heading.nextElementSibling;
    const arrow = heading.querySelector('.toggle-year');
    const hint = heading.querySelector('.toggle-hint');
    const isOpen = content.style.display !== 'none';
    content.style.display = isOpen ? 'none' : 'block';
    arrow.textContent = isOpen ? '▸' : '▾';
    hint.textContent = isOpen ? 'Click to expand' : 'Click to collapse';
  }
</script>


