---
layout: default
title: Jekyll designs
permalink: /portfolio/
---


{% for design in site.designs %}


<a href="{{ design.url | prepend: site.baseurl }}">
	<h2>{{ design.title }}</h2>
</a>


<p class="post-excerpt">{{ design.description | truncate: 160 }}</p>

{% endfor %}  