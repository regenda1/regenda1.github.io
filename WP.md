---
layout: page
permalink: wp
title: "Moje projekty"
---

Mojim nultym projektom bolo naucit sa jekyll. Pomohli mi tieto tutorialy:

{% youtube youtube.com/watch?v=iNZBEki_x6o&list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB&index=16 width height %}

# Moje dalsie projekty:

{% for post in site.posts %}
{% if post.categories contains "projekt" %}
## [ {{ post.title }} ]( {{ post.url }} )  
{% endif %}
{% endfor %}

## Projekt 2
## Projekt 3