---
layout: single
title: "Research"
permalink: /research/
---

My astrophysics research focuses on stellar evolution, exoplanets, and pulsation timing variations.

<div class="card">
    {% for research in site.research %}
    <h2>{{ research.title }}</h2>
        <div class="row" id="{{research.title}}">
            <div class="col-md-8">
                <div class="text-div">
                    <p>{{ research.content }}</p>
                </div>
            </div>
            <div class="col-md-4">
                <img src="{{ research.image | relative_url }}" alt="{{ research.title }}" class="img-fluid">
            </div>
        </div>
    {% endfor %}
</div>
