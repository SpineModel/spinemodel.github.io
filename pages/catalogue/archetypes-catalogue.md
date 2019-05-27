---
title: Archetypes Catalogue
keywords: documentation, model, archetypes, catalogue
summary: "Spine maps of popular organisational designs"
sidebar: catalogue_sidebar
permalink: archetypes-catalogue.html
folder: documentation
---

{% include tip.html content="The best way to get properly informed about any [Archetype](archetypes) is to find people who are actively using it and to ask them about their experiences. Sometimes the sales pitch and the reality of implementation of an archetype are two different stories." %}

{% assign sorted-posts = site.posts | where: "category","Archetypes" | sort %}
{% include_relative list-posts.md %}

{% include links.html %}
