---
layout: page
title: Camino
permalink: /camino/
---

Camino de Santiago
April 2019

{% for camino_day in site.camino %}
  <a href="{{ camino_day.url }}">
    Day {{ camino_day.day }} - Location {{ camino_day.destination }} - Walked {{ camino_day.walked_distance }} km
  </a>
{% endfor %}
