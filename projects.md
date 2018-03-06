---
layout: page
permalink: /projects/
title: Projects
---


{% for post in site.categories.projects %}
 <a href="{{ post.url }}">{{ post.title }}</a>
{% endfor %}
