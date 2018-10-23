---
type: component
title: Titler
parent: typography
order: 02
---


<p>Alle HTML titler, <code>&lt;h1&gt;</code> til <code>&lt;h6&gt;</code>, er stylet. Kan benyttes enten vis tags, klasser eller mixins.</p>

{% include code/preview.html component="headings" %}
{% include code/accordion.html component="headings" %}

<div class="accordion-bordered">
  <button class="button-unstyled accordion-button"
      aria-expanded="false" aria-controls="headings-docs-tech">
    Implementering
  </button>
  <div id="headings-docs-tech" aria-hidden="true" class="accordion-content">
    <p>Alle headings (h1-h6) er stylet med mixins, som styrer hver enkel headings font-family, font-size, line-height, font-weight og color. </p>
      <div class="code-highlight">
        <code>
          @mixin h1{ <br>
          &nbsp;&nbsp;&nbsp;font-family: $font-name; <br>
          &nbsp;&nbsp;&nbsp;font-size: $h1-font-size; <br>
          &nbsp;&nbsp;&nbsp;line-height: $h1-line-height; <br>
          &nbsp;&nbsp;&nbsp;font-weight: $font-weight-bold; <br>
          &nbsp;&nbsp;&nbsp;color: $color-black;<br>
        }
        </code>
      </div>
      <div class="code-highlight">
        <code>
          h1, .h1 {<br>
          &nbsp;&nbsp;&nbsp;@include h1;<br>
          }
        </code>
      </div>
      <p>Der er oprettet klasser for hver heading, som arver styling fra heading mixins. Dette betyder at hvis der ønskes en h1 med styling fra h2, skal klassen .h2 blot indsættes på &lt;h1 class="h2"&gt;</p>
  </div>
</div>
<div class="accordion-bordered accordion-docs">
  <button class="button-unstyled accordion-button"
      aria-expanded="true" aria-controls="link-docs">
    Brugervenlighed
  </button>
  <div id="link-docs" class="accordion-content">
    
  </div>
</div>
