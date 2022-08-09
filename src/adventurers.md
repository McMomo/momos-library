---
layout: base.njk
title: Everything for the dachshund, everything for the club!
tags: navigation
icon: /assets/gems_black.png
color: --red
---

## Everything for the dachshund, everything for the club!

{% for adventurer in collections.adventurers %}
<a href="{{ adventurer.url }}">{{ adventurer.data.title }}</a>
{% endfor %}