---
layout: default
title: 
tagline: 
---
{% include JB/setup %}

  {% for post in site.posts %}
  <div class="post_block">
    <a class="post_title_index" href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>
    <div class="post_content">
    	{{ post.content }}
    </div>
    <a class="post_detail" href="{{ BASE_PATH }}{{ post.url }}">阅读全文   评论</a>
  </div>
  {% endfor %}