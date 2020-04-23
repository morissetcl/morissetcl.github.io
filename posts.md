---
layout: page
title: Posts
permalink: /posts
---
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-90123342-2"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'UA-90123342-2');
</script>

<h4 class='title-sub'>Medium articles I have written.</h4>

{% for post in site.posts %}
<div class="row">
	<div class="small-12 columns">

		<sub>{{ post.date | date: '%B %d, %Y' }}</sub>
		<a href="{{ post.medium_url }}" target="_blank"><h3>{{ post.title }} <img class="flag" src="/static/img/{{post.lang}}.svg" /> </h3></a>

	  	{{ post.excerpt }}

	</div>
</div>

{% endfor %}
