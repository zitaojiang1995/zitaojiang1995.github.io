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

  <div class="lab-hero-label">SETSUNAN UNIVERSITY · DEPARTMENT OF Living Environment Design</div>

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

# Zitao Jiang

I am an **Senior Lecturer at Setsunan University**, specializing in **Building Environmental Engineering**.

My research focuses on understanding and improving the **airflow, thermal environment, and energy performance of buildings and cities**. I combine **computational fluid dynamics (CFD), wind-tunnel and field experiments, building performance simulation, and data-driven modeling** to address environmental challenges in the built environment.

[**Research →**](/research/) &nbsp;&nbsp; [**Publications →**](/publications/) &nbsp;&nbsp; [**CV →**](/cv/)

---

## Research

### 🌬️ Building Airflow & Natural Ventilation
Natural ventilation, cross-ventilation, indoor airflow, contaminant transport, and ventilation effectiveness.

[Learn more →](/research/#building-airflow-and-natural-ventilation)

### 🌇 Urban Microclimate & Climate-responsive Design
Urban thermal environments, waterfront cooling, pedestrian environments, solar exposure, and interactions between microclimate and buildings.

[Learn more →](/research/#urban-microclimate-and-outdoor-thermal-environment)

### 💻 Data-driven Building Physics
Reduced-order modeling, POD, DeepONet, physics-informed machine learning, sparse sensing, and real-time environmental prediction.

[Learn more →](/research/#data-driven-building-physics)

### ⚡ Building Energy & Environmental Performance
Natural ventilation potential, climate-responsive operation, and integration of airflow prediction with building energy simulation.

[Learn more →](/research/#building-energy-and-climate-responsive-design)

---

## Selected Research Projects

### Fast Prediction of Indoor Airflow

Development of reduced-order and operator-learning approaches for rapid prediction of indoor airflow and ventilation, with the long-term goal of supporting real-time building environmental control.

### Natural Ventilation

Experimental and computational investigation of natural ventilation under complex wind and building conditions, from fundamental ventilation mechanisms to practical applications.

### Urban Environmental Measurement

Field and mobile measurements of urban thermal environments combined with spatial analysis and numerical modeling to understand the effects of urban form, solar exposure, vegetation, and water bodies.

[**Explore all research →**](/research/)

## Selected Publications

For a complete list of publications, please visit the [**Publications page →**](/publications/).

---

## Research Group

Our group works on building and urban environmental engineering through a combination of **simulation, experiments, measurements, and data-driven approaches**.

Students interested in CFD, building airflow, urban climate, environmental measurement, or machine learning for building physics are welcome to explore our research.

[**Visit the Lab →**](/lab/)
