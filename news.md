---
layout: page
title : News
header : xcvbn
group : navigation
tagline: Presentations, podcasts and publications of the model
---
{% include JB/setup %}

{% assign posts_collate = (site.posts | where: "category" , "News") %}
{% include JB/posts_collate %}
