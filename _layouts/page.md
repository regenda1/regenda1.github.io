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

