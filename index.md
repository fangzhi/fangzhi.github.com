---
layout: page
title: 方志的Blog
tagline: Supporting tagline
---
{% include JB/setup %}

#方志的个人主页

##最新文章：

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

