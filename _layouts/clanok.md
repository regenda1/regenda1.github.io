---
layout: default
author: "Ja"
title: "Zaujimavosti"
---

<h1> {{ page.title }} </h1>
<h3> autor: {{ page.author }} </h3>
<hr />

{{ content }}

{% capture sunny %}{% include kvetinka.md %}{% endcapture %}
{{ sunny | markdownify }}

<hr />

![Slniecko]( {{ "../img/slniecko.jpg" | relative_url }} )
<img src=" {{ "../img/slniecko.jpg" | relative_url }} ">
<img src={{ "../img/slniecko.jpg" | relative_url }}>

