---
layout: default
title: News Archive
permalink: /news/
---

# All News

{% assign sorted_posts = site.posts | sort: 'date' | reverse %}

{% for post in sorted_posts %}
  <h3>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </h3>
  <p><small>{{ post.date | date: "%b %d, %Y" }}</small></p>
  <p>
<div class="excerpt">
  {{ post.excerpt }}   <!-- preserves HTML -->
</div>
  </p>
  <hr style="margin: 2em 0; border: 0; border-top: 1px solid #eee;">
{% endfor %}

<p style="text-align: center; margin-top: 3em;">
  ← <a href="/">Back to homepage</a>
</p>
