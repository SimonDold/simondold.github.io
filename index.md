---https://orcid.org/0009-0003-6265-9484
layout: default
title:
---

{% include menu.md %}


![Profile Photo](/img/simondold.jpeg){: style="float: right; width: 180px; margin-left: 20px; border-radius: 50%;"}
# Simon Dold
**PhD Student**  
Artificial Intelligence Group  
University of Basel, Switzerland  
Spiegelgasse 5, 4051 Basel, Switzerland  
---


## Short Bio
I am a PhD student in the [Artificial Intelligence research group](https://ai.dmi.unibas.ch/) at the University of Basel, where I have been working since 2022 under the supervision of [Prof. Dr. Malte Helmert](https://dmi.unibas.ch/en/persons/malte-helmert/).
I completed my Master's in Computer Science here in 2021.
My research interests center on **potential heuristics** and **proof logging** in automated planning.


## Contact  
Email: simon.dold@unibas.ch  

## Profiles  
[Google Scholar](https://scholar.google.com/citations?user=-pfh78YAAAAJ&hl=de&oi=ao), 
[GitHub](https://github.com/simondold), 
[dblp](https://dblp.org/pid/326/2080-1.html), 
[ORCID](https://orcid.org/0009-0003-6265-9484)


## Latest News
[See all news →](/news)

{% for post in site.posts limit: 5 %}
<h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
<p><small>{{ post.date | date: "%b %d, %Y" }}</small></p>
{% endfor %}

