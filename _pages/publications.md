---
layout: page
permalink: /research/
title: research
description:
nav: true
nav_order: 1
---

<!-- _pages/publications.md -->

<div class="publications">

<h2>Publications</h2>

{% bibliography --group_by none --query @article %}

<h2>Working Papers</h2>

{% bibliography --group_by none --query @unpublished %}

<h2>Work in Progress</h2>

{% bibliography --group_by none --query @misc %}

</div>
