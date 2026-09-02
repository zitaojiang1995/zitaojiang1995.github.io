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

  <div class="lab-hero-label">
    SETSUNAN UNIVERSITY · DEPARTMENT OF LIVING ENVIRONMENT DESIGN
  </div>

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


<h2 class="section-title">Research Areas</h2>

<div class="research-grid">

  <a class="research-card" href="/research/#building-airflow-and-natural-ventilation">
    <div class="research-number">01</div>
    <h3>Building Airflow &<br>Natural Ventilation</h3>
    <p>
      Natural ventilation, indoor airflow, contaminant transport,
      and ventilation effectiveness.
    </p>
    <span>Explore →</span>
  </a>

  <a class="research-card" href="/research/#urban-microclimate-and-outdoor-thermal-environment">
    <div class="research-number">02</div>
    <h3>Urban Microclimate &<br>Outdoor Environment</h3>
    <p>
      Urban thermal environments, waterfront cooling,
      solar exposure, and environmental measurement.
    </p>
    <span>Explore →</span>
  </a>

  <a class="research-card" href="/research/#data-driven-building-physics">
    <div class="research-number">03</div>
    <h3>Data-driven<br>Building Physics</h3>
    <p>
      Reduced-order modeling, POD, DeepONet,
      physics-informed learning, sparse sensing, and digital twins.
    </p>
    <span>Explore →</span>
  </a>

  <a class="research-card" href="/research/#building-energy-and-climate-responsive-design">
    <div class="research-number">04</div>
    <h3>Building Energy &<br>Environmental Control</h3>
    <p>
      Building energy simulation, natural ventilation potential,
      environmental sensing, and control.
    </p>
    <span>Explore →</span>
  </a>

</div>

<div class="section-more">
  <a href="/research/">View all research →</a>
</div>
