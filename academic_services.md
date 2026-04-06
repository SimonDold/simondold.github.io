---
layout: default
title: Academic Services
---

{% include menu.md %}

# Academic Services

{% assign papers = site.posts | where: "type", "service" | sort: "date" | reverse %}

{% for post in service %}
### [{{ post.title }}]({{ post.url }})
<small>{{ post.date | date: "%B %d, %Y" }}</small>

{{ post.excerpt | markdownify | truncatewords: 80 }}

{% endfor %}

[← Back to Home](/)
