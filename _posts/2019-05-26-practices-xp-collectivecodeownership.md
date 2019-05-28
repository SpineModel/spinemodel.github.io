---
title: Collective Code Ownership
sidebar: catalogue_sidebar
keywords: catalogue, practices
category : XP-Practices
permalink: practices-xp-collectivecodeownership.html
tags: [practices, xp]
folder: catalogue
last_updated: 25 May 2019
---

{% include note.html content="For more information, review the [eXtreme Programming archetype](xp-archetype)." %}

On an Extreme Programming project, any pair of programmers can improve any code at any time. This means that all code gets the benefit of many people’s attention, which increases code quality and reduces defects. There is another important benefit as well: when code is owned by individuals, required features are often put in the wrong place, as one programmer discovers that he needs a feature somewhere in code that he does not own. The owner is too busy to do it, so the programmer puts the feature in his own code, where it does not belong. This leads to ugly, hard-to-maintain code, full of duplication and with low (bad) cohesion.

Collective ownership could be a problem if people worked blindly on code they did not understand. XP avoids these problems through two key techniques: the [programmer tests](practices-xp-tdd) catch mistakes, and [pair programming](practices-xp-pairprogramming) means that the best way to work on unfamiliar code is to pair with the expert. In addition to ensuring good modifications when needed, this practice spreads knowledge throughout the team.

*(Source: [Ron Jeffries](http://ronjeffries.com/xprog/what-is-extreme-programming))*
{% include links.html %}
