---
permalink: /
title: ""
excerpt: ""
author_profile: false
classes: home-wide
redirect_from:
  - /about/
  - /about.html
---
<div class="lab-hero lab-hero-photo">

  <div class="lab-hero-content">

    <div class="lab-hero-label">
      BUILDING &amp; URBAN ENVIRONMENTAL DYNAMICS
    </div>

    <h1>
      Understanding environmental flows<br>
      in buildings and cities
    </h1>

    <p>
      From fundamental flow phenomena to
      climate-responsive built environments.
    </p>

    <div class="lab-hero-buttons">
      <a href="/research/" class="hero-btn">
        Explore Our Research →
      </a>
    </div>

  </div>

  <div class="hero-photo-caption">
    Clouds above the mountains, Japan<br>
    <span>Photo by Zitao Jiang</span>
  </div>

</div>

<h2 class="section-title">最新ニュース</h2>


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

<h2 class="section-title">Collaboration</h2>

<div class="collaboration-section">

  <div class="collaboration-main">
    <h3>We welcome research collaborations</h3>

    <p>
      We welcome collaborations with companies, universities,
      research institutes, and public organizations.
      Our laboratory addresses practical challenges in building and urban
      environments by combining numerical simulation, experiments,
      field measurements, and data-driven approaches.
    </p>

    <p>
      We are also particularly interested in research on
      <strong>buildings and urban environments in Southeast Asia</strong>,
      including climate-responsive design, natural ventilation,
      urban microclimate, and building energy performance in hot and humid climates.
      We welcome opportunities for international collaboration,
      comparative studies, and joint field investigations in the region.
    </p>
  </div>

  <div class="collaboration-methods">
    <span>CFD Simulation</span>
    <span>Wind Tunnel Experiments</span>
    <span>Field Measurements</span>
    <span>Environmental Sensing</span>
    <span>Data-driven Modeling</span>
  </div>

  <p class="collaboration-examples">
    Natural Ventilation & Building Airflow / Urban Microclimate /
    Building Energy / Environmental Sensing & Prediction /
    Wind & Environmental Engineering
  </p>

  <div class="collaboration-links">
    <a href="/research/" class="btn btn--primary">Explore Our Research</a>
    <a href="/profile/#contact" class="btn">Contact</a>
  </div>

</div>
