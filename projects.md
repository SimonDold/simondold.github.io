---
layout: default
title: Projects
---

{% include menu.md %}

# Projects

{% assign projects = site.posts | where: "type", "project" | sort: "date" | reverse %}

{% for post in projects %}

{{ post.content }}

{% endfor %}

[← Back to Home](/)
