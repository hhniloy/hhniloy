---
layout: default
title: Blog
---

## All Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})  
  Category: {{ post.categories }}
{% endfor %}
