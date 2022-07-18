---
title: The Library of Momo
layout: base.njk
templateEngineOverride: njk,md
---

{% for navigation in collections.navigation %}
<a href="{{ navigation.url }}">{{ navigation.data.title }}</a>
{% endfor %}