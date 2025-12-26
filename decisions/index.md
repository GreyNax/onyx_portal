---
layout: page
title: Design Decisions
permalink: /decisions/
---

## Key Design Decisions

{% for decision in site.decisions %}
- [{{ decision.title }}]({{ decision.url }}) - {{ decision.date | date: "%B %d, %Y" }}
  {% if decision.description %}
  <br>{{ decision.description }}
  {% endif %}
{% endfor %}

