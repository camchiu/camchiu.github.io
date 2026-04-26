---
layout: default
title: "Research"
author_profile: true
permalink: /research/
---

<div class="research-list">

  {% for project in site.research %}

  <a class="card-link" href="{{ project.url | relative_url }}">

    <div class="card-horizontal">

      <div class="card-image">
        <img src="{{ project.image | relative_url }}" alt="{{ project.title }}">
      </div>

      <div class="card-content">
        <h2>{{ project.title }}</h2>
        <p>{{ project.excerpt }}</p>
      </div>

    </div>

  </a>

  {% endfor %}

</div>
