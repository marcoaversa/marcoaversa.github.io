---
layout: page
permalink: /publications/
title: publications
description: 
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

{% bibliography -f {{ site.scholar.bibliography }} %}

{% if entry.key == "aversa2023diffinfinite" %}
  <img src="assets/img/1.jpg" />
  <p>{{ entry.abstract }}</p>
{% elsif entry.key == "oala2023data" %}
  <img src="assets/img/2.jpg" />
  <p>{{ entry.abstract }}</p>
{% else %}
  <!-- Default rendering for other entries -->
{% endif %}

</div>
