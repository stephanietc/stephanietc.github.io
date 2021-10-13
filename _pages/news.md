---
permalink: /news/
title: "News"
layout: archive
author_profile: true
---

{% for post in site.posts %}
  {% unless post.hidden %}
    {% include archive-single.html %}
  {% endunless %}
{% endfor %}
