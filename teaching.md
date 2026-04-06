---
layout: default
title: Teaching
---

{% include menu.md %}

# Teaching

{% assign teaching_items = site.posts | where: "type", "teaching" | sort: "date" | reverse %}

{% for post in teaching_items %}

{{ post.content }}

---

{% endfor %}

[← Back to Home](/)
