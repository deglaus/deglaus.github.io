---
layout: post
title:  "Welcome!"
date:   2023-01-15 09:54:16 +0100
permalink: /blog/
categories: nav
---
Hello! Welcome [to](https://deglaus.github.io/blog/first/) the blog.
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>