---
layout: default
title: Talks
---

{% include menu.md %}

# Talks

{% assign talks = site.posts | where: "type", "talk" | sort: "date" | reverse %}

{% for post in talks %}

{{ post.content }}

{% endfor %}

[← Back to Home](/)
