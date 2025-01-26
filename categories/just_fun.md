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
![Hello June (1)](https://github.com/user-attachments/assets/e1e0b833-d2cc-4f21-9182-1671ddbe70e0)
