---
layout: page
title: Архив
---

## Заметки

{% for post in site.posts %}
- {{ post.date | date: "%d.%m.%Y" }} &raquo; [ {{ post.title }} ]({{ post.url }})
{% endfor %}