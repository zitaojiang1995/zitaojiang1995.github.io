---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---
<div class="lab-hero">

  <div class="lab-hero-label">SETSUNAN UNIVERSITY · DEPARTMENT OF LIVING ENVIRONMENT DESIGN</div>

  <h1>Building & Urban<br>Environmental Dynamics Laboratory</h1>

  <div class="lab-hero-jp">
    建築・都市環境ダイナミクス研究室
  </div>

  <p>
    Exploring airflow, thermal environments, and environmental
    performance in buildings and cities.
  </p>

  <div class="lab-hero-tags">
    <span>Airflow</span>
    <span>Natural Ventilation</span>
    <span>Urban Microclimate</span>
    <span>Building Energy</span>
    <span>Data-driven Modeling</span>
  </div>

  <div class="lab-hero-buttons">
    <a href="/research/" class="btn btn--primary">Explore Our Research</a>
    <a href="/lab/" class="btn">Meet the Lab</a>
  </div>

</div>
---
# Building & Urban Environmental Dynamics Laboratory

### Department of Living Environment Deisng, Faculty of Science and Engineering, Setsunan University

Our laboratory investigates airflow, thermal environments, and environmental performance in buildings and cities.

We combine **Computational Fluid Dynamics (CFD), wind tunnel experiments, field measurements, and data-driven modeling** to study natural ventilation, indoor airflow, urban microclimate, building energy, and environmental control.
---
<h2 class="section-title">Latest News</h2>

<div class="news-list">

{% assign english_posts = site.posts | where: "lang", "en" %}
{% for post in english_posts limit:4 %}

<a class="news-item" href="{{ post.url }}">
  <span class="news-date">{{ post.date | date: "%Y.%m.%d" }}</span>
  <span class="news-category">{{ post.category | upcase }}</span>
  <span class="news-title">{{ post.title }}</span>
  <span class="news-arrow">→</span>
</a>

{% endfor %}

</div>

<div class="section-more">
  <a href="/news/">View all news →</a>
</div>
---

