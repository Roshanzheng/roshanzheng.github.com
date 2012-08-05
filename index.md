---
layout: page
title: 
tagline: 
---
{% include JB/setup %}

<ul class="posts">
  {% for post in site.posts %}
    <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>
  {% endfor %}
</ul>
