---
layout: default
title: Teaching
---

# Teaching & Supervision

{% assign teaching_items = site.posts | where: "type", "teaching" | sort: "date" | reverse %}

{% for post in teaching_items %}
### [{{ post.title }}]({{ post.url }})
<small>{{ post.date | date: "%B %d, %Y" }}</small>

{{ post.excerpt | markdownify | truncatewords: 80 }}

{% endfor %}

[← Back to Home](/)
