---
layout: default
---

{{ content }}

<h2>Posts by {{ page.name }}:</h2>
<ul>
{% for post in site.posts %}
{% if post.author == page.name %}
<li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
{% endif %}
{% endfor %}
</ul>
