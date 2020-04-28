---
layout: page
title: Camino
permalink: /camino/
---

Camino de Santiago
April 2019

{% for camino_day in site.camino %}
  <a href="{{ camino_day.url }}">
    Day {{ camino_day.day }}: {{ camino_day.location }}
  </a>
{% endfor %}
