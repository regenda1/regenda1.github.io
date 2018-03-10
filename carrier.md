---
layout: page
permalink: carrier
title: "Kariéra"
poradie: 3
---
<div style="font-size: 24px">
{% for job in site.data.profesie %}
	<b>Typ:</b> {{job.typ}} <br>
	<b>Nazov:</b> {{job.nazov}}  <br>
	<b>Datum:</b> {{job.datum}} <br>
	<b>Napln:</b> {{job.napln}} <br><br>
{% endfor %}
</div>

# **Tu je môj najnovší projekt** [ Webove publikovanie ]({{ "/wp/" | relative_url }})

### Čo ma baví na informatike

Najviac ma baví vytváranie a navrhovanie vlastných programov. Tiež ma baví programovanie a matematika. Toto je ukážka programovacieho
jazyka java: 

{% highlight java %}
public class HelloWorld {

    public static void main(String[] args) {
        System.out.println("Hello, World");
    }

}
{% endhighlight %}