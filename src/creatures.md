---
layout: base.njk
title: Are you a friend or a fiend?
tags: navigation
icon: /assets/008-orc.png
---

## Are you a friend or a fiend?

{% for creature in collections.creatures %}
<a href="{{ creature.url }}">{{ creature.data.title }}</a>
{% endfor %}