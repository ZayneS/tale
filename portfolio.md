---
layout: default
title: Jekyll designs
permalink: /portfolio/
---

<div>
    {% assign sorted = (site.designs | sort: 'date') | reverse %}
    {% for item in sorted %}
    	<a href="{{ item.url | prepend: site.baseurl }}">
			<h2>{{ item.title }}</h2>
		</a>
		<p class="post-excerpt">{{ item.date }}</p>
		<p class="post-excerpt">{{ item.description | truncate: 160 }}</p>
    {% endfor %}
</div>




