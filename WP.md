---
layout: page
permalink: /wp/
title: "WP"
poradie: 2
---

# Moje projekty:

{% for post in site.posts %}
{% if post.categories contains "projekt" %}
## [ {{ post.title }} ]( {{ post.url }} )  
{% endif %}
{% endfor %}

## Projekt 2
## Projekt 3