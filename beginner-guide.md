---
layout: default
title: "Beginner Guide"
permalink: /beginner-guide/
---

## 📚 Beginner Guide Posts

<ul>
  {% for post in site.categories.beginner-guide %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
