---
title: Research
permalink: /research/
layout: default
---

<div class="card-grid">
  {% for item in site.research %}
    {% include research-card.html item=item %}
  {% endfor %}
</div>
