---
layout: page
title: Archive
---
<div class="home">
	<ul class="posts">
		{% for post in site.posts %}
		<li><span>{{ post.date | date_to_string }}</span> <span class="seperator">~</span> <a href="{{ post.url }}">{{ post.title }}</a></li>
		{% endfor %}
	</ul>
</div>

