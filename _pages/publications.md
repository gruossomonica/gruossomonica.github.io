---
layout: page
permalink: /publications/
title: Publications
description: Publications in reversed chronological order
nav: true
nav_order: 5
---

## Papers

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>

## Preprints

- __Evaluation of Virtual Reality Interaction Techniques for 3D Graph Exploration__
<br>N. Capece, U. Erra, D. Malandrino, M. M. North, and M. Gruosso
<br>[[arXiv](https://doi.org/10.2312/gch.20201301)]


## Posters
- __A Motion Picture Content Rating Model for Supporting Automatic Classification using Deep Neural Network__
<br>M. Gruosso, N. Capece, U. Erra, N. Lopardo
<br>_ACDL 2019 &ndash; 2nd Advanced Course on Data Science &amp; Machine Learning_
<br>Certosa di Pontignano (Siena), Italy, July 15-19, 2019
<br>[[Poster](http://graphics.unibas.it/www/mgruosso/posters/poster_70x90cm.pdf)]
   
    
## Presentations
- __Image Processing using Convolutional Neural Networks__
<br>M. Gruosso
<br>_Sam Ratulangi University_
<br>September 28, 2021 - online
<br>[[Slides](http://graphics.unibas.it/www/mgruosso/slides/workshop_28_09_21.pptx)] [[Oral Presentation](https://www.youtube.com/watch?v=HlsWxLlPxB4)]
- <b>Convolutional neural networks for image analysis</b>
<br>M. Gruosso
<br><i>University of Basilicata</i>
<br>Potenza, Italy, January 15, 2020