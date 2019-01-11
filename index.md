---
layout: default
title: Xyz
---


	#{{ page.title }}
	<ul class="posts">

	  {% for post in site.posts %}
        {{ post.date | date_to_string }} » [{{ post.title }}]({{ post.url }} )
	  {% endfor %}
	</ul>
