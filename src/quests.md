---
layout: base.njk
title: What did just happen?
tags: navigation
icon: /assets/waves_orange.png
---

## What did just happen?

{% for quest in collections.quests %}
<a href="{{ quest.url }}">{{ quest.data.title }}</a>
{% endfor %}