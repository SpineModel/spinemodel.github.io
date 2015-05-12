---
layout: page
title: Spine Model
tagline: a sensemaking framework for human work systems
---
{% include JB/setup %}

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }} - {{post.tagline}}</a> ({{post.category}} by {{post.author}})</li>
  {% endfor %}
</ul>