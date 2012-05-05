---
layout: default
---

# a header

I an index.md

<p><br/><b>My Blog:</b></p>

<ul class="post">
	{% for post in site.posts %}
		<li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{}"
	{% endfor %}
</ul>
