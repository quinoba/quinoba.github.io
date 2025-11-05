---
layout: page
permalink: /publications/
title: Research
description:
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

<div class="publications">

<h3>Working Papers</h3>
{% bibliography --query @*[type=working-paper] --sort_by year --order descending %}

<!-- <h3>publications</h3> -->

</div>
