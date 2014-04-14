---
layout: page
title: Archive
---

# Blog Posts

{% for post in site.posts %}
  * {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ](/Blog{{ post.url }})
{% endfor %}
