---
title: "News"
permalink: /news/
author_profile: true
---

# News

{% assign english_posts = site.posts | where: "lang", "en" %}

{% for post in english_posts %}

### {{ post.date | date: "%Y.%m" }} | {{ post.category | capitalize }}

[**{{ post.title }}**]({{ post.url }})

{{ post.excerpt }}

[Read more →]({{ post.url }})

---

{% endfor %}
