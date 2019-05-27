---
title: Continuous Integration
sidebar: catalogue_sidebar
keywords: catalogue, practices
category : XP-Practices
permalink: practices-xp-continuousintegration.html
tags: [Practices, XP]
folder: catalogue
last_updated: 25 May 2019
---

{% include note.html content="For more information, review the [eXtreme Programming archetype](xp-archetype)." %}

Extreme Programming teams keep the system fully integrated at all times. We say that daily builds are for wimps: XP teams build multiple times per day. (One XP team of forty people builds at least eight or ten times per day!)

The benefit of this practice can be seen by thinking back on projects you may have heard about (or even been a part of) where the build process was weekly or less frequently, and usually led to “integration hell”, where everything broke and no one knew why.

Infrequent integration leads to serious problems on a software project. First of all, although integration is critical to shipping good working code, the team is not practiced at it, and often it is delegated to people who are not familiar with the whole system. Second, infrequently integrated code is often – I would say usually – buggy code. Problems creep in at integration time that are not detected by any of the testing that takes place on an unintegrated system. Third, weak integration process leads to long code freezes. Code freezes mean that you have long time periods when the programmers could be working on important shippable features, but that those features must be held back. This weakens your position in the market, or with your end users.

For more information, review the [XP archetype](xp-archetype).

*(Source: [Ron Jeffries](http://ronjeffries.com/xprog/what-is-extreme-programming))*

{% include links.html %}
