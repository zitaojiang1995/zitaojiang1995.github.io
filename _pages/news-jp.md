---
title: "ニュース"
permalink: /jp/news/
author_profile: true
---

# News

{% assign english_posts = site.posts | where: "lang", "jp" %}

{% for post in japanese_posts %}

### {{ post.date | date: "%Y.%m" }} | {{ post.category | capitalize }}

[**{{ post.title }}**]({{ post.url }})

{{ post.excerpt }}

[続きを読む →]({{ post.url }})

---

{% endfor %}
