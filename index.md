---
layout: default
title: 
tagline: 
---
{% include JB/setup %}

  {% for post in site.posts %}
  <div class="post_block">
    <h2><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></h2>
    <div class="post_content">
    	{{ post.content }}
    </div>
    <p class="post_detail"><a href="{{ BASE_PATH }}{{ post.url }}">阅读全文 | 评论</a></p>
  </div>
  {% endfor %}