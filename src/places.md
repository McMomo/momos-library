---
layout: base.njk
title: All the different places
tags: navigation
teaser: /assets/topo_grey.png
color: --dark-blue
---

## All the different places

{% for place in collections.places %}
<a href="{{ place.url }}">{{ place.data.title }}</a>
{% endfor %}