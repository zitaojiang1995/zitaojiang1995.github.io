---
permalink: /jp/
title: ""
excerpt: ""
author_profile: false
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

<div class="news-list">

{% assign japanese_posts = site.posts | where: "lang", "jp" %}
{% for post in japanese_posts limit:4 %}

<a class="news-item" href="{{ post.url }}">
  <span class="news-date">{{ post.date | date: "%Y.%m.%d" }}</span>
  <span class="news-category">
    {% if post.category == "publication" %}
      論文
    {% elsif post.category == "award" %}
      受賞
    {% elsif post.category == "conference" %}
      学会
    {% elsif post.category == "research" %}
      研究
    {% elsif post.category == "news" %}
      お知らせ
    {% else %}
      {{ post.category }}
    {% endif %}
  </span>
  <span class="news-title">{{ post.title }}</span>
  <span class="news-arrow">→</span>
</a>

{% endfor %}

</div>

<div class="section-more">
  <a href="/jp/news/">ニュース一覧 →</a>
</div>


<h2 class="section-title">研究分野</h2>

<div class="research-grid">

  <a class="research-card" href="/jp/research/#建築気流自然換気">
    <div class="research-number">01</div>
    <h3>建築気流・<br>自然換気</h3>
    <p>
      自然換気、通風、室内気流、換気効率、汚染物質輸送など、
      建築空間における空気の流れに関する研究を行っています。
    </p>
    <span>詳しく見る →</span>
  </a>

  <a class="research-card" href="/jp/research/#都市微気候屋外温熱環境">
    <div class="research-number">02</div>
    <h3>都市微気候・<br>屋外環境</h3>
    <p>
      都市気流、屋外温熱環境、水辺空間、日射・日陰、
      環境計測などを通して都市微気候を研究しています。
    </p>
    <span>詳しく見る →</span>
  </a>

  <a class="research-card" href="/jp/research/#データ駆動型建築環境予測">
    <div class="research-number">03</div>
    <h3>データ駆動型<br>建築環境予測</h3>
    <p>
      POD、DeepONet、Physics-Informed Machine Learning、
      少数センサーによる環境場推定などの研究に取り組んでいます。
    </p>
    <span>詳しく見る →</span>
  </a>

  <a class="research-card" href="/jp/research/#建築エネルギー環境制御">
    <div class="research-number">04</div>
    <h3>建築エネルギー・<br>環境制御</h3>
    <p>
      建築エネルギーシミュレーション、自然換気ポテンシャル、
      環境センシング、リアルタイム制御などを研究しています。
    </p>
    <span>詳しく見る →</span>
  </a>

</div>

<div class="section-more">
  <a href="/jp/research/">研究内容の詳細 →</a>
</div>

<h2 class="section-title">共同研究</h2>

<div class="collaboration-section">

  <div class="collaboration-main">
    <h3>建築・都市環境に関する共同研究を歓迎しています</h3>

    <p>
      本研究室では、企業、大学・研究機関、自治体等との共同研究を歓迎しています。
      建築・都市環境における実践的な課題に対して、
      数値解析、実験、現地計測、データ駆動型手法を組み合わせた研究に取り組んでいます。
    </p>
  </div>

  <div class="collaboration-methods">
    <span>CFD解析</span>
    <span>風洞実験</span>
    <span>現地計測</span>
    <span>環境センシング</span>
    <span>データ駆動型モデリング</span>
  </div>

  <p class="collaboration-examples">
    自然換気・建築気流 ／ 都市微気候・屋外環境 ／
    建築エネルギー ／ 環境センシング・予測 ／
    風工学・環境流体
  </p>

  <div class="collaboration-links">
    <a href="/jp/research/" class="btn btn--primary">研究内容を見る</a>
    <a href="/jp/profile/#連絡先" class="btn">お問い合わせ</a>
  </div>

</div>
