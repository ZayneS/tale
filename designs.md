---
layout: default
title: Jekyll designs
permalink: /my-designs/
---

{% for design in site.collections.designs %}


<a href="{{ design.url | prepend: site.baseurl }}">
        <h2>{{ design.title }}</h2>
</a>

<p class="post-excerpt">{{ design.description | truncate: 160 }}</p>

{% endfor %}  