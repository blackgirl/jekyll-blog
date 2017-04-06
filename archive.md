---
layout: page
title: Кладовая
---

{% for post in site.posts %}
	<!-- {% unless post.url contains 'personal' %} -->
	  * {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ post.url }})
    <!-- {% endunless %} -->
{% endfor %}