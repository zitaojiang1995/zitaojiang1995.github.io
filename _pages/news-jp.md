---
title: "ニュース"
permalink: /jp/news/
author_profile: true
---

# ニュース

{% assign japanese_posts = site.posts | where: "lang", "jp" %}

{% for post in japanese_posts %}

### {{ post.date | date: "%Y.%m" }} | {{ post.category }}

[**{{ post.title }}**]({{ post.url }})

{{ post.excerpt }}

[続きを読む →]({{ post.url }})

---

{% endfor %}
