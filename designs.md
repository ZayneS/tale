---
layout: default
title: Jekyll designs
permalink: /my-designs/
---

{% for design in site.collections.designs %}


<a href="{{ design.url | prepend: site.baseurl }}">
		<div class="thumbnail"><img src="pic_trulli.jpg" alt="Italian Trulli"></div>
        <h2>{{ design.title }}</h2>
        <p class="post-excerpt">{{ design.description | truncate: 160 }}</p>
</a>



{% endfor %}  