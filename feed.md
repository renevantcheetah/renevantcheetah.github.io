---
layout: page
title: Posts
---

{% for post in site.posts %}
  &raquo; [{{ post.title }} ]({{ post.url }})
{% endfor %}
