---
title: Values Catalogue
keywords: documentation, model, values, catalogue
summary: "Needs > <b>VALUES</b> > Principles > Practices > Tools"
sidebar: catalogue_sidebar
permalink: values-catalogue.html
folder: documentation
---

{% include tip.html content="Values resolve this statement: <i>We optimise the system for {X}, so that meeting the Needs is more likely.</i>" %}

{% assign sorted-posts = site.posts | where: "category","Values" | sort %}
{% include_relative list-posts.md %}

{% include links.html %}
