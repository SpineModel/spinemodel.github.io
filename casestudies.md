---
layout: page
title : Case Studies
header : xcvbn
group: navigation
tagline: Examples of when the Spine Model has been applied...
order: 7
---
{% include JB/setup %}

<img style="float: right; border: 30px solid white" src="/assets/images/InTheWild/jo_perold.png">

We haven't been very good at publishing case studies. This is something we are working on. Here are the ones we have published so far:

{% assign posts_collate = site.posts | where: "category" , "CaseStudy" %}
{% include JB/posts_collate %}