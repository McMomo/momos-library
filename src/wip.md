---
layout: base.njk
title: WIP
tags: navigation
icon: /assets/014-progress.png
---

## Wery important posts

{% for post in collections.wip %}
<a href="{{ post.url }}">{{ post.data.title }}</a>
{% endfor %}