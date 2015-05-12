---
layout: page
title: Spine Model
tagline: a sensemaking framework for human work systems
---
{% include JB/setup %}

#### First time here?
If you're new to the Spine Model, start [here](/explanation/introduction).

<br>

#### Most recent items...
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }} - {{post.tagline}}</a> ({{post.category}} by {{post.author}})</li>
  {% endfor %}
</ul>

