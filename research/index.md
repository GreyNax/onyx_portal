---
layout: page
title: Research
permalink: /research/
---

## Research & Technical Documentation

{% for item in site.research %}
- [{{ item.title }}]({{ item.url }})
  {% if item.description %}
  <br>{{ item.description }}
  {% endif %}
{% endfor %}

