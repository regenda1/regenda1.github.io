<html>
  <head>
  	<link rel="stylesheet" type="text/css" href={{ "/css/template.css" | absolute_url }}>
  </head>
  
 <body>
 <div class="navigation">
     {% assign menu = site.pages | sort: 'poradie' %}
	 {% for stranka in menu %}
	<a href="{{stranka.url}}">{{stranka.title}}</a>
	{% endfor %}
 </div>

 
{{ content }}




 <div class="footer" markdown="1">

 <ul>
	<li> Pocet slov na stranke: {{ page.content | number_of_words }} </li>
	<li>  Kontakt </li>
</ul>
	
	
</div>
 </body>
</html>


