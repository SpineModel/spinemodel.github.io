---
title: Spine Model Uses
keywords: documentation, model
summary: "These are some of the ways in which the Spine Model can been useful..."
sidebar: documentation_sidebar
permalink: uses.html
folder: documentation
tags: [uses]
---

<div class="home">
    {% for post in site.posts %}
        {% if post.category == "Uses" %}
        <ul>
            <li>
                <a class="post-link" href="{{ post.url | remove: "/" }}">{{ post.title }}</a>
                <p>{% if post.summary %} {{ post.summary | strip_html | strip_newlines | truncate: 160 }} {% else %} {{ post.content | truncatewords: 50 | strip_html }} {% endif %}</p>
            </li>
        </ul>
        {% endif %}
    {% endfor %}
</div>

{% include links.html %}
