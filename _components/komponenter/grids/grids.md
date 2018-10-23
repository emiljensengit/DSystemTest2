---
permalink: /designandcode/grids/
redirect_from:
- /grids/
layout: styleguide
type: component
title: Grid
category: UI components
subcategory: Design og kode
lead: Frontend Styleguiden benytter Boostrap's mobile-first flexbox grid til opbygning af sider. Gridsystemet er et standard 12-kolonne system, med fem responsive breakpoints.
---


<h2 class="h2" id="introduction">Introduktion</h2>
<p>Den fællesoffentlige styleguide (FSG) bygger på USWD. USWD kommer med et grid out-of-the-box der hedder <a href="https://neat.bourbon.io/">NEAT</a>. NEAT er et såkaldt 'Float grid' da den benygger sig af css' float-property. Da float-grids ikke gør brug af den nyeste teknologi vil vi gerne tilbyde et yderligere grid-system i den fællesoffentlige styleguide som benytter flexbox. Et flexbox grid gør det bl.a. nemmere for udviklere at centrere elementer, ændre på rækkefølgen af elementer uden af ændre i sidestrukturen og meget mere.</p>
<p>Som flexbox grid har vi valgt at inkludere grid-systemet fra <a href="https://getbootstrap.com/">Bootstrap 4</a>. Det er valgfrit om man vil bruge USWD’s grid eller Flexbox-griddet. Standard indstilling er sat til flexbox gridsystemt. </p>
<p>Dokumentation på dette site viser hvordan flexbox-gridsystemet benyttes.</p>



<h2 class="h2" id="grid-change">Skift mellem grid-systemer</h2>
<p>Som udvikler kan du konfigurer koden således at USWD’s grid benyttes i steden for flexbox griddet.</p>
<ol>
    <li>Åben filen: /src/stylesheets/core/_variables.scss</li>
    <li>I _variables.scss finder du følgende to variable: 
        <br>
        <span class="highlight">$enable-bs-grid:   true !default;</span><br>
        <span class="highlight">$enable-uswd-grid: false !default;</span><br>
    </li>
    <li>Ved at sætte <i>$enable-uswd-grid</i> til true og <i>$enable-bs-grid</i> til false vil FSG nu benytte USWD’s gridsystem.</li>
</ol>
<p>Ønsker du yderligere information om USWD’s gridsystem kan du finde dokumentationen på <a href="https://designsystem.digital.gov/components/grids/">USWDs website</a>.</p>


<h2 class="h2" id="how-it-works">Flexbox grid</h2>
<p>Som beskrevet ovenfor kommer FSG med Bootstrap 4 gridsystem out-of-the-box. Du kan derfor finde dokumentation på griddet på Bootstrap hjemmeside <a href="https://getbootstrap.com/docs/4.1/layout/grid/">her</a>.</p>
