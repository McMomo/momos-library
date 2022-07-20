---
layout: base.njk
title: Prepare yourself thursday is comming!
tags: navigation
icon: /assets/011-edit.png
---

## Prepare yourself thursday is comming!

{% for note in collections.notes %}
<a href="{{ note.url }}">{{ note.data.title }}</a>
{% endfor %}