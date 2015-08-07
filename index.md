---
layout: page
title: Spine Model
tagline: a sensemaking framework for human work systems
---
{% include JB/setup %}

## What need does the model satisfy?
The invisible structure of a human organisational system can be either implicit or explicit. By making the structure explicit, starting at the reason the system exists in the first place, [Needs](/Needs.html), your chances of having a well functioning system are greatly enhanced. This happens through enabling people to have more effective conversations, and able to make better decisions.

Based on a chain of levels, the model can be thought of as vertebrae of a spine. You always measure against the highest level. The higher levels should set the frame for what is acceptable lower down (e.g. does this [Practice](/Practices.html) *satisfy* our choices at higher levels?).

By collaboratively mapping a [System](/FAQ/WhatIsASystem), you create an opportunity for useful conversations to occur at the appropriate levels. Actions can be chosen that are ecologically appropriate for the specific context.

## First time here?
If you're new to the Spine Model, you could learn more by reading [this explanation](/explanation/introduction), or listen to [this podcast interview](http://driven2distraction.co.za/distraction/2015/07/27/D2D020.html).

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





