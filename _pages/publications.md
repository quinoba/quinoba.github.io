---
layout: page
permalink: /publications/
title: research
description:
  working papers and publications in reversed chronological order.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

<div class="publications">

## Working Papers

{% bibliography --query @*[type=working-paper] --sort_by year --order descending %}

---

## Peer-Reviewed Publications

{% bibliography --query @*[type!=working-paper] --sort_by year --order descending %}

</div>
