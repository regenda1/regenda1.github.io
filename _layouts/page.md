---
layout: default
title: "Toto je kusok o mne..."
---

<h2> {{ page.title | smartify }} </h2>

<h4> {{ site.time | date_to_long_string }} <br /> </h4>
<hr />

{{ content }}



{% capture sunny %}{% include peknyDen.md %}{% endcapture %}
{{ sunny | markdownify }}

<hr />
<h3> Vyborne tutorialy na jekyll: </h3>
{% youtube youtube.com/watch?v=iNZBEki_x6o&list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB&index=16 width height %}
