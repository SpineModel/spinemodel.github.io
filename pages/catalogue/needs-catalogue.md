---
title: Needs Catalogue
keywords: documentation, model, needs, catalogue
summary: "<b>NEEDS</b> > Values > Principles > Practices > Tools"
sidebar: catalogue_sidebar
permalink: needs-catalogue.html
folder: documentation
---

{% include tip.html content="Needs resolve this statement: <i>From the perspective of {X}, this part of the system exists in order that {Y} can be achieved.</i>" %}

{% assign sorted-posts = site.posts | where: "category","Needs" %}
{% include_relative list-posts.md %}

{% include links.html %}
