---
layout: single
title: "Leistungen"
permalink: /leistungen/
---

<div class="services-page">

  <header class="services-intro">
    <p class="services-kicker">OPTIPLAN / LEISTUNGEN</p>
    <h2>Was wir für Sie tun.</h2>
    <p>
      Wir planen und begleiten technische Gebäudeausrüstung –
      von der ersten Konzeption bis zur fertigen Ausführung.
    </p>
    <p class="services-hint" id="services-hint">Leistung auswählen, um mehr zu erfahren.</p>
  </header>

  <div class="optiplan-service-tiles" aria-describedby="services-hint">



<button
  class="optiplan-tile optiplan-tile--illustrated"
  type="button"
  data-service="0"
  aria-expanded="false"
  aria-controls="service-panel"
  aria-label="Technische Gebäudeplanung"
>
  <span class="optiplan-tile-visual" aria-hidden="true">
    <img
    class="optiplan-tile-artwork"
    src="{{ '/assets/leistung-gebaeudeplanung.png' | relative_url }}"
    alt=""
   width="1254" height="1254">
  </span>
  <span class="optiplan-tile-caption">Technische<br>Gebäudeplanung</span>
</button>
<button
  class="optiplan-tile optiplan-tile--illustrated"
  type="button"
  data-service="1"
  aria-expanded="false"
  aria-controls="service-panel"
  aria-label="Beratung und Konzepte"
>
  <span class="optiplan-tile-visual" aria-hidden="true">
    <img
    class="optiplan-tile-artwork"
    src="{{ '/assets/leistung-beratung-konzepte.png' | relative_url }}"
    alt=""
   width="1254" height="1254">
  </span>
  <span class="optiplan-tile-caption">Beratung &amp;<br>Konzepte</span>
</button>

      <button
  class="optiplan-tile optiplan-tile--illustrated"
  type="button"
  data-service="2"
  aria-expanded="false"
  aria-controls="service-panel"
  aria-label="Berechnung und Dimensionierung"
>
  <span class="optiplan-tile-visual" aria-hidden="true">
    <img
    class="optiplan-tile-artwork"
    src="{{ '/assets/leistung-berechnung-dimensionierung.png' | relative_url }}"
    alt=""
   width="1254" height="1254">
  </span>
  <span class="optiplan-tile-caption">Berechnung &amp;<br>Dimensionierung</span>
</button>

    <!-- Gemeinsames Textfenster folgt der ausgewählten Bildschirmzeile. -->
    <section class="optiplan-service-panel" id="service-panel" aria-labelledby="service-panel-title" aria-live="polite" hidden>
      <div class="optiplan-service-panel-header">
        <h3 id="service-panel-title"></h3>
        <button type="button" class="optiplan-service-close" aria-label="Leistungsbeschreibung schließen">×</button>
      </div>
      <div id="service-panel-content"></div>
    </section>



      <button
  class="optiplan-tile optiplan-tile--illustrated"
  type="button"
  data-service="3"
  aria-expanded="false"
  aria-controls="service-panel"
  aria-label="Ausschreibung und Vergabe"
>
  <span class="optiplan-tile-visual" aria-hidden="true">
    <img
    class="optiplan-tile-artwork"
    src="{{ '/assets/leistung-ausschreibung-vergabe.png' | relative_url }}"
    alt=""
   width="1254" height="1254">
  </span>
  <span class="optiplan-tile-caption">Ausschreibung &amp;<br>Vergabe</span>
</button>

      <button
  class="optiplan-tile optiplan-tile--illustrated"
  type="button"
  data-service="4"
  aria-expanded="false"
  aria-controls="service-panel"
  aria-label="Bauüberwachung und Kontrolle"
>
  <span class="optiplan-tile-visual" aria-hidden="true">
    <img
    class="optiplan-tile-artwork"
    src="{{ '/assets/leistung-bauueberwachung-kontrolle.png' | relative_url }}"
    alt=""
   width="1254" height="1254">
  </span>
  <span class="optiplan-tile-caption">Bauüberwachung &amp;<br>Kontrolle</span>
</button>

      <button
  class="optiplan-tile optiplan-tile--illustrated"
  type="button"
  data-service="5"
  aria-expanded="false"
  aria-controls="service-panel"
  aria-label="Abnahme und Projektabschluss"
>
  <span class="optiplan-tile-visual" aria-hidden="true">
    <img
    class="optiplan-tile-artwork"
    src="{{ '/assets/leistung-abnahme-projektabschluss.png' | relative_url }}"
    alt=""
   width="1254" height="1254">
  </span>
  <span class="optiplan-tile-caption">Abnahme &amp;<br>Projektabschluss</span>
</button>

  </div>
</div>

<script>
document.addEventListener("DOMContentLoaded", function () {
  const services = [
    {
      title: "Technische Gebäudeplanung",
      content: `<p>Wir planen die technische Ausstattung von Gebäuden in den Bereichen Heizung, Lüftung, Sanitär, Kälte und Energie. Dazu gehören die Entwicklung technischer Konzepte, Berechnungen sowie Entwurfs-, Einreich-, Ausschreibungs- und Ausführungsplanung.</p>`
    },
    {
      title: "Beratung & Konzepte",
      content: `<p>Wir beraten Bauherren bei technischen Fragestellungen und entwickeln geeignete Lösungen für Neubauten, Umbauten und Sanierungen. Bestehende Anlagen werden beurteilt und mögliche Varianten hinsichtlich Funktion, Wirtschaftlichkeit und Umsetzbarkeit verglichen.</p>
      <p>Nicht jede Fragestellung erfordert einen vollständigen Planungsauftrag. Wir unterstützen auch bei einzelnen technischen Fragen, Kontrollen vor Ort oder einer unabhängigen Einschätzung bestehender oder geplanter Lösungen.</p>`
    },
    {
      title: "Berechnung & Dimensionierung",
      content: `<p>Wir berechnen und dimensionieren technische Anlagen und deren Komponenten. Dazu gehören je nach Projekt beispielsweise Heiz- und Kühllasten, Luftmengen, Rohr- und Kanalnetze sowie die erforderlichen Leistungen technischer Anlagen.</p>`
    },
    {
      title: "Ausschreibung & Vergabe",
      content: `<p>Wir erstellen technische Ausschreibungen und Leistungsverzeichnisse, prüfen Angebote und unterstützen den Bauherrn bei der technischen und wirtschaftlichen Bewertung sowie bei der Vergabe.</p>`
    },
    {
      title: "Bauüberwachung & Kontrolle",
      content: `<p>Wir kontrollieren die technische Ausführung auf der Baustelle und prüfen, ob die Arbeiten entsprechend Planung, Ausschreibung und vereinbarten Anforderungen umgesetzt werden. Festgestellte Abweichungen und offene Punkte werden dokumentiert und mit den Beteiligten abgestimmt.</p>`
    },
    {
      title: "Abnahme & Projektabschluss",
      content: `<p>Wir begleiten die Fertigstellung der technischen Anlagen, kontrollieren Leistungen und Unterlagen und unterstützen bei Abnahmen, Mängelfeststellungen und der technischen Übergabe.</p>`
    }
  ];

  const tiles = document.querySelectorAll(".optiplan-tile");
  const panel = document.getElementById("service-panel");
  const panelTitle = document.getElementById("service-panel-title");
  const panelContent = document.getElementById("service-panel-content");
  const closeButton = document.querySelector(".optiplan-service-close");
  let active = null;

  const narrowLayout = window.matchMedia("(max-width: 768px)");

  function positionPanel(index) {
    const lastInRow = narrowLayout.matches ? index : Math.min(Math.floor(index / 3) * 3 + 2, tiles.length - 1);
    tiles[lastInRow].after(panel);
  }

  narrowLayout.addEventListener("change", function () {
    if (active !== null) positionPanel(active);
  });

  function closePanel() {
    panel.hidden = true;
    active = null;
    tiles.forEach(tile => {
      tile.classList.remove("is-active");
      tile.setAttribute("aria-expanded", "false");
    });
  }

  tiles.forEach(tile => {
    tile.addEventListener("click", function () {
      const index = Number(tile.dataset.service);

      if (active === index) {
        closePanel();
        return;
      }

      active = index;
      panelTitle.textContent = services[index].title;
      panelContent.innerHTML = services[index].content;
      positionPanel(index);
      panel.hidden = false;

      tiles.forEach(other => {
        const selected = other === tile;
        other.classList.toggle("is-active", selected);
        other.setAttribute("aria-expanded", String(selected));
      });
    });
  });

  closeButton.addEventListener("click", function () {
    const previous = active;
    closePanel();
    if (previous !== null) tiles[previous].focus();
  });

  panel.addEventListener("keydown", function (event) {
    if (event.key === "Escape") closeButton.click();
  });
});
</script>
<!-- GitHub Pages: erneute Veröffentlichung -->
