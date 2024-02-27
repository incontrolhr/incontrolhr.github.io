---
layout: base.njk
title: Hello World
---

# {{ title }}

{% for post in collections.posts %}

- [{{ post.data.title }}]({{ post.url }})
  {% endfor %}
