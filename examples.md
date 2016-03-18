---
layout: page
title : Examples
header : xcvbn
group : navigation
tagline: These are canned example Spine Models...
---
{% include JB/setup %}

{% assign posts_collate = (site.posts | where: "category" , "Example") %}
{% include JB/posts_collate %}
