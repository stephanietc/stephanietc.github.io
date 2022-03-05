---
permalink: /updates/
title: "Updates"
layout: archive
author_profile: true
---

{% for post in site.posts %}
  {% unless post.hidden %}
    {% include archive-posts.html %}
  {% endunless %}
{% endfor %}
