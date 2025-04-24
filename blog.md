--- 
title: Blog 
layout: default
--- 
# Latest Posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

[Home](https://badge-18.github.io/)
