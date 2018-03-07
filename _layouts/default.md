<html>
  <head>
  	<link rel="stylesheet" type="text/css" href={{ "/css/template.css" | absolute_url }}>
  </head>
  
 <body>
 <div class="navigation">
	<a href=" {{ ../index.md | relative_url }} ">Home</a>
	<a href=" {{ ../about.md | absolute_url_url }} ">Hobby</a>
	<a href="../carrier.md">Carrier</a>
	<a href="WP.md">WP</a>
 </div>

{{ content }}




 <div class="footer" markdown="1">

	Pocet slov na stranke: {{ page.content | number_of_words }}
	
</div>
 </body>
</html>


