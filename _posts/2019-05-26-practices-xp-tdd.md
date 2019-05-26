---
title: Test Driven Development
sidebar: catalogue_sidebar
keywords: catalogue, practices
category : XP-Practices
permalink: practices-xp-tdd.html
tags: [Practices, XP]
folder: catalogue
last_updated: 25 May 2019
---

{% include note.html content="For more information, review the [eXtreme Programming archetype](/archetype/XP)." %}

Extreme Programming is obsessed with feedback, and in software development, good feedback requires good testing. Top XP teams practice “test-driven development”, working in very short cycles of adding a test, then making it work. Almost effortlessly, teams produce code with nearly 100 percent test coverage, which is a great step forward in most shops. (If your programmers are already doing even more sophisticated testing, more power to you. Keep it up, it can only help!)

It isn’t enough to write tests: you have to run them. Here, too, Extreme Programming is extreme. These “programmer tests”, or “unit tests” are all collected together, and every time any programmer releases any code to the repository (and pairs typically release twice a day or more), every single one of the programmer tests must run correctly. One hundred percent, all the time! This means that programmers get immediate feedback on how they’re doing. Additionally, these tests provide invaluable support as the software design is improved.

*(Source: [Ron Jeffries](http://ronjeffries.com/xprog/what-is-extreme-programming))*

{% include links.html %}
