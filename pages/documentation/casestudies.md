---
title: Spine Model Case Studies
keywords: documentation, model, case studies
summary: "These are some of the ways in which the Spine Model has been applied..."
sidebar: documentation_sidebar
permalink: casestudies.html
folder: documentation
tags: [case_study]
---

<img style="float: right; border: 30px solid white" src="images/InTheWild/jo_perold.png">

There hasn't been a great focus on publishing case studies. If you have one, please submit it and we will gladly add it to the list...

<div class="home">
    {% for post in site.posts %}
        {% if post.category == "CaseStudy" %}
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
