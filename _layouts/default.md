<html>
  <head>
  	<link rel="stylesheet" type="text/css" href={{ "/css/template.css" | absolute_url }}>
  </head>
  
 <body>
 <div class="navigation">
	{% for stranka in site.pages %}
	<a href="{{stranka.url}}">{{stranka.title}}</a>
	{% endfor %}
 </div>

 <h1> Uz sa prejavila zmena piata zmena</h1>
 
{{ content }}




 <div class="footer" markdown="1">

	Pocet slov na stranke: {{ page.content | number_of_words }}
	
</div>
 </body>
</html>


