---
layout: base.njk
title: WIP
tags: navigation
teaser: /assets/topo3_black.png
color: --blue
---

## Wery important posts

{% for post in collections.wip %}
<a href="{{ post.url }}">{{ post.data.title }}</a>
{% endfor %}