---
title: Practices Catalogue
keywords: documentation, model, practices, catalogue
summary: "Needs > Values > Principles > <b>PRACTICES</b> > Tools"
sidebar: catalogue_sidebar
permalink: practices-catalogue.html
folder: documentation
---

{% include tip.html content="Practices resolve this statement: <i>We do {X} to apply the Principles that matter in this context.</i>" %}

{% assign sorted-posts = site.posts | where: "category","Practices" | sort %}
{% include_relative list-posts.md %}

{% include links.html %}
