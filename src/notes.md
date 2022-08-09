---
layout: base.njk
title: Prepare yourself thursday is comming!
tags: navigation
icon: /assets/waves_orange.png
---

## Prepare yourself thursday is comming!

{% for note in collections.notes %}
<a href="{{ note.url }}">{{ note.data.title }}</a>
{% endfor %}