---
layout: archive
permalink: /
title: ""
---

<style type="text/css">
.bgimg {
    background-image: url('{{ site.baseurl }}/images/heart_wood2.jpg');
}
</style>

<b>HUOM! Sivusto muuttaa osoitteeseen julmat.haukilintu.fi </b>

<div class="page-lead bgimg">
	<div class="wrap page-lead-content ">
		<h1>JulMat menee naimisiin</h1>
		<h2>22.2.2020<br>
		No olihan se jo aikakin!</h2>
	</div>
</div>

Matti Ojala ja Julia Gustafsson ovat aloittaneet häävalmistelunsa. Tervetuloa seuraamaan matkaamme alttarille!

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->


<!-- https://mmistakes.github.io/skinny-bones-jekyll/ -->
