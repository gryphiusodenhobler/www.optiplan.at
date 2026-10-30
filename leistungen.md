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

  <div class="services-accordion">

    <details class="service-item">
      <summary>
        <span class="service-number">01</span>
        <span class="service-title">Technische Gebäudeplanung</span>
        <span class="service-arrow" aria-hidden="true"></span>
      </summary>
      <div class="service-content">
        <p>
          Wir planen die technische Ausstattung von Gebäuden in den Bereichen
          Heizung, Lüftung, Sanitär, Kälte und Energie. Dazu gehören die
          Entwicklung technischer Konzepte, Berechnungen sowie Entwurfs-,
          Einreich-, Ausschreibungs- und Ausführungsplanung.
        </p>
      </div>
    </details>

    <details class="service-item">
      <summary>
        <span class="service-number">02</span>
        <span class="service-title">Beratung &amp; Konzepte</span>
        <span class="service-arrow" aria-hidden="true"></span>
      </summary>
      <div class="service-content">
        <p>
          Wir beraten Bauherren bei technischen Fragestellungen und entwickeln
          geeignete Lösungen für Neubauten, Umbauten und Sanierungen.
          Bestehende Anlagen werden beurteilt und mögliche Varianten
          hinsichtlich Funktion, Wirtschaftlichkeit und Umsetzbarkeit verglichen.
        </p>
      </div>
    </details>

    <details class="service-item">
      <summary>
        <span class="service-number">03</span>
        <span class="service-title">Berechnung &amp; Dimensionierung</span>
        <span class="service-arrow" aria-hidden="true"></span>
      </summary>
      <div class="service-content">
        <p>
          Wir berechnen und dimensionieren technische Anlagen und deren
          Komponenten. Dazu gehören je nach Projekt beispielsweise Heiz-
          und Kühllasten, Luftmengen, Rohr- und Kanalnetze sowie die
          erforderlichen Leistungen technischer Anlagen.
        </p>
      </div>
    </details>

    <details class="service-item">
      <summary>
        <span class="service-number">04</span>
        <span class="service-title">Ausschreibung &amp; Vergabe</span>
        <span class="service-arrow" aria-hidden="true"></span>
      </summary>
      <div class="service-content">
        <p>
          Wir erstellen technische Ausschreibungen und Leistungsverzeichnisse,
          prüfen Angebote und unterstützen den Bauherrn bei der technischen
          und wirtschaftlichen Bewertung sowie bei der Vergabe.
        </p>
      </div>
    </details>

    <details class="service-item">
      <summary>
        <span class="service-number">05</span>
        <span class="service-title">Bauüberwachung &amp; Kontrolle</span>
        <span class="service-arrow" aria-hidden="true"></span>
      </summary>
      <div class="service-content">
        <p>
          Wir kontrollieren die technische Ausführung auf der Baustelle und
          prüfen, ob die Arbeiten entsprechend Planung, Ausschreibung und
          vereinbarten Anforderungen umgesetzt werden. Festgestellte
          Abweichungen und offene Punkte werden dokumentiert und mit
          den Beteiligten abgestimmt.
        </p>
      </div>
    </details>

    <details class="service-item">
      <summary>
        <span class="service-number">06</span>
        <span class="service-title">Abnahme &amp; Projektabschluss</span>
        <span class="service-arrow" aria-hidden="true"></span>
      </summary>
      <div class="service-content">
        <p>
          Wir begleiten die Fertigstellung der technischen Anlagen,
          kontrollieren Leistungen und Unterlagen und unterstützen bei
          Abnahmen, Mängelfeststellungen und der technischen Übergabe.
        </p>
      </div>
    </details>

    <details class="service-item">
      <summary>
        <span class="service-number">07</span>
        <span class="service-title">Technische Beratung im Detail</span>
        <span class="service-arrow" aria-hidden="true"></span>
      </summary>
      <div class="service-content">
        <p>
          Nicht jede Fragestellung erfordert einen vollständigen Planungsauftrag.
          Wir unterstützen auch bei einzelnen technischen Fragen, Kontrollen
          vor Ort oder einer unabhängigen Einschätzung bestehender oder
          geplanter Lösungen.
        </p>
      </div>
    </details>

  </div>
</div>

<script>
document.addEventListener("DOMContentLoaded", function () {
  const items = document.querySelectorAll(".services-accordion .service-item");

  items.forEach(function (item) {
    item.addEventListener("toggle", function () {
      if (!item.open) return;

      items.forEach(function (other) {
        if (other !== item) other.open = false;
      });
    });
  });
});
</script>
