---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---
<div class="container">
<div class="grid__wrapper">
  {% assign itemsprojects = site.projects | sort: 'order' %}  
  {% for post in itemsprojects reversed %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>
</div>
