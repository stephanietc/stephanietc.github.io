---
layout: archive
title: "Research"
permalink: /research/
sidebar:
  nav: research
---

<div class="grid__wrapper">
  {% assign itemscurrent = site.current | sort: 'order' %}
  {% for post in itemscurrent reversed %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
  {% assign itemspast = site.past | sort: 'order' %}  
  {% for post in itemspast reversed %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>
