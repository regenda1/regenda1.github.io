---
layout: page
permalink: wp
title: "WP"
---

Mojim nultym projektom bolo naucit sa jekyll. Pomohli mi tieto tutorialy:



# Moje dalsie projekty:

{% for post in site.posts %}
{% if post.categories contains "projekt" %}
## [ {{ post.title }} ]( {{ post.url }} )  
{% endif %}
{% endfor %}

## Projekt 2
## Projekt 3