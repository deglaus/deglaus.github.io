---
layout: post
title:  "Blog posts"
date:   2023-01-15 09:54:16 +0100
permalink: /blog/
categories: nav
---
<div class="menu" style="display:inline-block; border-style: solid; margin-right: 10px;">
	<p>
	<ul id="menu" style="margin-right: 15px">
	<li><a href="https://deglaus.github.io/">Main</a></li>
	<li><a href="https://deglaus.github.io/subpages/projects.html">Projects</a></li>
	<li><a href="https://deglaus.github.io/blog/">Blog</a></li>
	<li><a href="">Random</a></li>
	</ul>		
	</p>
</div>
<br>

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
