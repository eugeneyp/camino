---
layout: page
title: Camino
permalink: /camino/
---

Camino de Santiago
April 2019

{% for camino_day in site.camino %}
  <a href="{{ camino_day.url }}">
    {{ camino_day.title }}
  </a>
{% endfor %}
