---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
<div class="container">
<h2 style="clear:both"> Current Projects</h2>
<div class="grid__wrapper">
  {% assign itemscurrent = site.current | sort: 'order' %}
  {% for post in itemscurrent reversed %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>
<h2 style="clear:both"> Past Projects</h2>
<div class="grid__wrapper">
  {% assign itemspast = site.past | sort: 'order' %}  
  {% for post in itemspast reversed %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>
</div>
