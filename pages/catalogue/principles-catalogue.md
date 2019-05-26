---
title: Principles Catalogue
keywords: documentation, model, principle, catalogue
summary: "Needs > Values > <b>PRINCIPLES</b> > Practices > Tools"
sidebar: catalogue_sidebar
permalink: principles-catalogue.html
folder: documentation
---

{% include tip.html content="Principles resolve this statement: <i>We leverage {X} to get more of what we Value.</i>" %}

{% assign sorted-posts = site.posts | where: "category","Principles" %}
{% include_relative list-posts.md %}

{% include links.html %}
