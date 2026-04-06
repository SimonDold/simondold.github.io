---
layout: default
title: Publications
---

[Home](/) &nbsp; • &nbsp;
[Publications](/publications) &nbsp; • &nbsp; 
[Teaching](/teaching) &nbsp; • &nbsp; 
[News](/news)

---

# Publications

{% assign papers = site.posts | where: "type", "paper" | sort: "date" | reverse %}

{% for post in papers %}
### [{{ post.title }}]({{ post.url }})
<small>{{ post.date | date: "%B %d, %Y" }}</small>

{{ post.excerpt | markdownify | truncatewords: 80 }}

{% endfor %}

[← Back to Home](/)
