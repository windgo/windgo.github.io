---
layout: page
title: qihuifeng的博客!
tagline: Supporting tagline
---
{% include JB/setup %}

Hello everyone! 你好,世界

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
