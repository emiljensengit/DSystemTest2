---
permalink: /designandcode/spinner/
layout: styleguide
type: element
title: Spinner
category: UI components
subcategory: Design og kode
lead: Spinner lead
---

{% include code/preview.html component="spinner" %}
{% include code/accordion.html component="spinner" %}
<div class="accordion-bordered">
  <button class="button-unstyled accordion-button"
      aria-expanded="true" aria-controls="code-spinner-docs">
    Implementering
  </button>
  <div id="code-spinner-docs" aria-hidden="false" class="accordion-content">
    <p>For at implementere en spinner tilføjes en <code>.spinner</code> class på en lukket div.</p>
    <ul>
    <li>Eksempel: <code>&lt;div class="spinner"&gt;&lt;/div&gt;</code></li>
    </ul>
    <p>For at ændre spinnerens størrelse kan <code>font-size</code> gøres større eller mindre.</p>
  </div>
</div>
