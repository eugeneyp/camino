---
layout: page
title: Pilgrimage
permalink: /pilgrimage/
---

## Camino de Santiago

In the spring of 2019, I stripped down my life into what I can fit into a backpack and started the pilgrimage walk of Camino de Santiago, crossing Spain in 40 days and over 800km. I wanted to bring my mind closer to my heart and to my feet on the ground, and closer in daily encounters with the sacred. 

{% assign sorted = site.camino | sort: 'day' %}
{% for camino_day in sorted %}
  <a href="{{ camino_day.url }}">
    {{ camino_day.title }}
  </a>
   {{ camino_day.walked_distance }} km
{% endfor %}

## Prayers and Poems

{% assign collection_pilgrimage = site.pilgrimage %}

{% for post in collection_pilgrimage %}
  <a href="{{ post.url }}">
    {{ post.title }}
  </a>
{% endfor %}

