---
layout: post
title: Design Improvement (Refactoring)
category : Practice
subpage: 1
tagline: ""
author: Kevin Trethewey
tags: [XP]
---
{% include JB/setup %}

Extreme Programming focuses on delivering business value in every iteration. To accomplish this over the course of the whole project, the software must be well-designed. The alternative would be to slow down and ultimately get stuck. So XP uses a process of continuous design improvement called *Refactoring*, from the title of Martin Fowler’s book, “[Refactoring: Improving the Design of Existing Code](http://www.amazon.com/exec/obidos/ASIN/0201485672/armaties)”.

The refactoring process focuses on removal of duplication (a sure sign of poor design), and on increasing the “cohesion” of the code, while lowering the “coupling”. High cohesion and low coupling have been recognized as the hallmarks of well-designed code for at least thirty years. The result is that XP teams start with a good, simple design, and always have a good, simple design for the software. This lets them sustain their development speed, and in fact generally increase speed as the project goes forward.

Refactoring is, of course, strongly supported by comprehensive testing to be sure that as the design evolves, nothing is broken. Thus the [customer tests](/practice/CustomerTests) and [programmer tests](/practice/TDD) are a critical enabling factor. The XP practices support each other: they are stronger together than separately.

For more information, review the [XP archetype](/archetype/XP/).

*(Source: [Ron Jeffries](http://ronjeffries.com/xprog/what-is-extreme-programming))*
