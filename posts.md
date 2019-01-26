---
layout: page
title: Posts
permalink: /
---

{% for post in site.posts %}
<div class="row">
	<div class="small-12 columns">

		<sub>{{ post.date | date: '%B %d, %Y' }}</sub>
		<a href="{{ post.url }}"><h3>{{ post.title }}</h3></a>

	  	{{ post.excerpt }}

	</div>
</div>
{% endfor %}
