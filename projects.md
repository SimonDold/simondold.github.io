---
layout: default
title: Projects
---

{% include menu.md %}

# Projects

{% assign projects = site.posts | where: "type", "project" | sort: "date" | reverse %}

{% for post in projects %}
### [{{ post.title }}]({{ post.url }})
<small>{{ post.date | date: "%B %d, %Y" }}</small>

{{ post.excerpt | markdownify | truncatewords: 80 }}

{% endfor %}

[← Back to Home](/)
