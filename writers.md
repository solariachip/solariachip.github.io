---
layout: page
title: Authors
---
The Solaria Chip authors:

{% for s in site.sc %}

* <a href="{{ site.baseurl }}{{ s.url }}">{{ s.name }}</a>

{% endfor %}
