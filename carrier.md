---
layout: page
permalink: carrier
title: "Kariera"
---
<div style="font-size: 24px">
{% for job in site.data.profesie %}
	<b>Typ:</b> {{job.typ}} <br>
	<b>Nazov:</b> {{job.nazov}}  <br>
	<b>Datum:</b> {{job.datum}} <br>
	<b>Napln:</b> {{job.napln}} <br><br>
{% endfor %}
</div>

# **Tu je moj najnovsi projekt** [ Webove publikovanie ]( {{ "/wp/" | relative_url }} )

### Co ma bavi na informatike ...

Najviac ma bavi vytvaranie a navrhovanie vlastnych programov. Tiez ma bavi programovanie a matematika. Toto je moj oblubeny kod: 

{% highlight java %}
public class HelloWorld {

    public static void main(String[] args) {
        System.out.println("Hello, World");
    }

}
{% endhighlight %}