---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---
<div class="container">
<div class="grid__wrapper">
  {% assign itemspast = site.past | sort: 'order' %}  
  {% for post in itemspast reversed %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>
</div>
