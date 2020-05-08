---
layout: page
title: Camino
permalink: /camino/
---

In the spring of 2019, I walked the Camino de Santiago, across Spain in 40 days and over 800km. 

{% assign sorted = (site.camino | sort: 'day') %}
{% for camino_day in sorted %}
  <a href="{{ camino_day.url }}">
    {{ camino_day.title }}
  </a>
{% endfor %}

