---
layout: default
title: Academic Services
---

{% include menu.md %}

# Reviewing

{% assign reviews = site.posts | where: "type", "review" | sort: "date" | reverse %}

{% for post in reviews %}

{{ post.content }}

{% endfor %}

# Thesis Supervision

{% assign supervisions = site.posts | where: "type", "supervision" | sort: "date" | reverse %}

{% for post in supervisions %}

{{ post.content }}

{% endfor %}

[← Back to Home](/)
