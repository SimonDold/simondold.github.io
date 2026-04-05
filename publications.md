---
layout: default
title: Publications
---

# Publications

{% assign papers = site.posts | where: "type", "paper" | sort: "date" | reverse %}

{% for post in papers %}
### [{{ post.title }}]({{ post.url }})
<small>{{ post.date | date: "%B %d, %Y" }}</small>

{{ post.excerpt | default: post.content | strip_html | truncate: 300 }}

{% endfor %}

[View all news →](/news)
