---
layout: default
---

<h2> {{ page.title | smartify }} </h2>

<h4> {{ site.time | date_to_long_string }} <br /> </h4>
<hr />

{{ content }}



{% capture sunny %}{% include kvetinka.md %}{% endcapture %}
{{ sunny | markdownify }}

<hr />
<h3> Výborné tutoriály na jekyll: </h3>

{% raw %}
{% youtube youtube.com/watch?v=iNZBEki_x6o&list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB&index=16 width height %}
{% endraw %}



