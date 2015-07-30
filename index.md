---
layout: page
title: Spine Model
tagline: a sensemaking framework for human work systems
---
{% include JB/setup %}

## What need does the model satify?
The invisible structure of a human organisational system can be either implicit or explicit. By making the structure explicit, starting at the reason the system exists in the first place, [Needs](/Needs.html), your chances of having a well functioning system are greatly enhanced.

Based on a chain of levels, the model can be thought of as vertebrae of a spine. You always measure against the highest level. The higher levels should set the frame for what is acceptable lower down (e.g. does this [Practice](/Practices.html) *satisfy* our choices at higher levels?).

By collaboratively mapping a [System](/FAQ/WhatIsASystem), you create an opportunity for useful conversations to occur and actions to be chosen that are ecologically appropriate.

## First time here?
If you're new to the Spine Model, start [here](/explanation/introduction).

## Most recent updates...
<ul class="posts">
  {% for post in site.posts limit:15 %}
    
    <!-- Add a dash if there is a tagline -->
    {% assign spacer = "-" %}
    {% if post.tagline == "" %}
        {% assign spacer = "" %}
    {% endif %}
    
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }} {{ spacer }} <i>{{post.tagline}}</i></a> ({{post.category}} by {{post.author}})</li>
  
  {% endfor %}
</ul>





