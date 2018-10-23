---
permalink: /designandcode/sidenav/
layout: styleguide
type: component
title: Sidenavigation
category: UI components
subcategory: Design og kode
lead: 
---

{% include code/preview.html component="sidenav--compare" %}
{% include code/accordion.html component="sidenav--compare" %}
<div class="accordion-bordered">
  <button class="button-unstyled accordion-button"
      aria-expanded="true" aria-controls="sidenav-tech-docs">
    Implementering
  </button>
  <div id="sidenav-tech-docs" aria-hidden="false" class="accordion-content">
    <h4>Sidenavigation</h4>
    <h5>Aktivte menupunkter</h5>
    <ul>
      <li>Teksten i det aktive menupunkt bliver styret af primærfarven, som og sættes med variablen <code>$color-primary</code></li>
      <li>Aktive menupunkter skal have <code>.current</code> klassen.</li>
      <li>Kun det sidste aktive menupunkt skal i stedet have <code>.active</code> klassen.</li>
    </ul>
    <h5>Tilføj ikon og information i sidenavigation</h5>
    <ul>
      <li>For at tilføje et ikon til et punkt i sidenavigationen bruges klassen <code>.sidenav-icon-before</code>.</li>
      <li>For at tilføje information til et punkt i sidenavigationen bruges klassen <code>.sidenav-information</code>.</li>
      <li>Ikoner og informationer kan også sammensættes i én sidenavigation</li>
    </ul>
  </div>
</div>
<div class="accordion-bordered accordion-docs">
  <button class="button-unstyled accordion-button"
      aria-expanded="true" aria-controls="sidenav-docs">
    Brugervenlighed
  </button>
  <div id="sidenav-docs" class="accordion-content">
    
  </div>
</div>