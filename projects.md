---
layout: default
title: Projects
---

{% include menu.md %}

# Projects

{% assign papers = site.posts | where: "type", "project" | sort: "date" | reverse %}

{% for post in service %}
### [{{ post.title }}]({{ post.url }})
<small>{{ post.date | date: "%B %d, %Y" }}</small>

{{ post.excerpt | markdownify | truncatewords: 80 }}

{% endfor %}

[← Back to Home](/)
