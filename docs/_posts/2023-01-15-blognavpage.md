---
layout: post
title:  "Blog posts"
date:   2023-01-15 09:54:16 +0100
permalink: /blog/
categories: nav
---
Hello! Welcome to the blog.
Posts:
<ul>
  {% for post in site.posts %}
  {% if post.title != "Blog posts"%}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
	{% endif %}
  {% endfor %}
</ul>