---
layout: default
title: just fun
---

# 开心 舒服 自在

{% for post in site.posts %}
  {% if post.categories contains "just_fun" %}
  - [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%Y-%m-%d" }}
  {% endif %}
{% endfor %}
