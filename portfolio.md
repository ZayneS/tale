---
layout: default
title: Jekyll designs
permalink: /portfolio/
---

<div class="portfolio">
    {% assign sorted = (site.designs | sort: 'date') | reverse %}
    {% for item in sorted %}
    	<a class="portfolio-item" href="{{ item.url | prepend: site.baseurl }}">
    		<div class="thumbnail img-wrapper"><img src="{{ item.img_url | prepend: site.baseurl }}" alt=""></img></div>
			<h2>{{ item.title }}</h2>
			<p class="post-excerpt">{{ item.description | truncate: 160 }}</p>
		</a>
    {% endfor %}
</div>




