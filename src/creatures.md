---
layout: base.njk
title: Are you a friend or a fiend?
tags: navigation
icon: /assets/zombi_cat.png
color: --green-blue
---

## Are you a friend or a fiend?

{% for creature in collections.creatures %}
<a href="{{ creature.url }}">{{ creature.data.title }}</a>
{% endfor %}