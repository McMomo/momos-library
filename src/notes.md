---
layout: base.njk
title: Prepare yourself thursday is comming!
tags: navigation
icon: /assets/ex_libris.png
color: --yellow
---

## Prepare yourself thursday is comming!

{% for note in collections.notes %}
<a href="{{ note.url }}">{{ note.data.title }}</a>
{% endfor %}