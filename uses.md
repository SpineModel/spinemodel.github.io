---
layout: page
title : Uses
header : xcvbn
group : navigation
tagline: These are ways in which Spine Model can be applied...
---
{% include JB/setup %}

{% assign posts_collate = (site.posts | where: "category" , "Usage") %}
{% include JB/posts_collate %}
