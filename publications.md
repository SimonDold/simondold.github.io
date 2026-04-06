---
layout: default
title: Publications
---

{% include menu.md %}

# Publications

{% assign papers = site.posts | where: "type", "paper" | sort: "date" | reverse %}

{% for post in papers %}

{{ post.content }}

{% endfor %}

[← Back to Home](/)
