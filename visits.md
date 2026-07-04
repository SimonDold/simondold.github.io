---
layout: default
title: Visits
---

{% include menu.md %}

# Visits

{% assign visits = site.posts | where: "type", "visit" | sort: "date" | reverse %}

{% for post in visits %}

{{ post.content }}

---

{% endfor %}

[← Back to Home](/)

