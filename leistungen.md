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
  </header>

  <div class="optiplan-service-tiles">

    <!-- Erste Kachelreihe -->
    <div class="optiplan-tile-row">

      <button class="optiplan-tile" type="button" data-service="0" aria-expanded="false">
        <span class="optiplan-tile-title">Technische Gebäudeplanung</span>
      </button>

      <button class="optiplan-tile" type="button" data-service="1" aria-expanded="false">
        <span class="optiplan-tile-title">Beratung &amp; Konzepte</span>
      </button>

      <button class="optiplan-tile" type="button" data-service="2" aria-expanded="false">
        <span class="optiplan-tile-title">Berechnung &amp; Dimensionierung</span>
      </button>

    </div>

    <!-- Gemeinsames Textfenster -->
    <section class="optiplan-service-panel" id="service-panel" aria-live="polite" hidden>
      <div class="optiplan-service-panel-header">
        <h3 id="service-panel-title"></h3>
        <button type="button" class="optiplan-service-close" aria-label="Leistungsbeschreibung schließen">×</button>
      </div>
      <div id="service-panel-content"></div>
    </section>

    <!-- Zweite Kachelreihe -->
    <div class="optiplan-tile-row">

      <button class="optiplan-tile" type="button" data-service="3" aria-expanded="false">
        <span class="optiplan-tile-title">Ausschreibung &amp; Vergabe</span>
      </button>

      <button class="optiplan-tile" type="button" data-service="4" aria-expanded="false">
        <span class="optiplan-tile-title">Bauüberwachung &amp; Kontrolle</span>
      </button>

      <button class="optiplan-tile" type="button" data-service="5" aria-expanded="false">
        <span class="optiplan-tile-title">Abnahme &amp; Projektabschluss</span>
      </button>

    </div>

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
      panel.hidden = false;

      tiles.forEach(other => {
        const selected = other === tile;
        other.classList.toggle("is-active", selected);
        other.setAttribute("aria-expanded", String(selected));
      });
    });
  });

  closeButton.addEventListener("click", closePanel);
});
</script>
