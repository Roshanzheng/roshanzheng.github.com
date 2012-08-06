---
layout: default
title: 
tagline: 
---
{% include JB/setup %}

  {% for post in site.posts %}
  <div>
    <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>
    <div>
    	{{ post.content }}
    </div>
  </div>
  {% endfor %}