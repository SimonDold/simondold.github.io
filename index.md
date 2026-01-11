---
layout: default
title: Simon Dold
---

![Profile Photo](/img/simondold.jpeg){: style="float: right; width: 180px; margin-left: 20px; border-radius: 50%;"}
# Simon Dold
**PhD Student**  
Artificial Intelligence Group  
University of Basel, Switzerland  
Spiegelgasse 1, 4051 Basel, Switzerland  


## Short Bio
I am a PhD student in the [Artificial Intelligence research group](https://ai.dmi.unibas.ch/) at the University of Basel, where I have been working since 2022 under the supervision of [Prof. Dr. Malte Helmert](https://dmi.unibas.ch/en/person/malte-helmert/).
I completed my Master's in Computer Science here in 2021.
My research interests center on **potential heuristics** and **proof logging** in automated planning.

## Contact  
Email: simon.dold@unibas.ch  
[Google Scholar](https://scholar.google.com/citations?user=...)  
[GitHub](https://github.com/simondold)



## Latest News
[See all news →](/news)

{% for post in site.posts limit: 5 %}
<h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
<p><small>{{ post.date | date: "%b %d, %Y" }}</small></p>
{% endfor %}

