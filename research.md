---
layout: single
title: "Research"
author_profile: true
permalink: /research/
---

My astrophysics research focuses on stellar evolution, exoplanets, and pulsation timing variations.

<div class="research-list">

  {% for project in site.research %}

    <a class="card-link" href="{{ project.url | relative_url }}">

      <div class="card-horizontal">

        {% if project.image %}
        <div class="card-image">
          <img src="{{ project.image | relative_url }}" alt="{{ project.title }}">
        </div>
        {% endif %}

        <div class="card-content">
          <h2>{{ project.title }}</h2>
          <p>{{ project.excerpt }}</p>
        </div>

      </div>

    </a>

  {% endfor %}

</div>
