---
layout: page
title: "O mojich zaujmoch"
permalink: /about/
title: "Záujmy"
poradie: 4
---

# Clanky o zaujmoch: 

{% for post in site.posts %}
{% if post.categories contains "hobby" %}
  [ {{ post.title }} ]( {{ post.url }} )
{% endif %}
{% endfor %}