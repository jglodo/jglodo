---
layout: page
permalink: /publications/
title: publications
description: publications by categories in reversed chronological order.
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

<div>Number of articles {% bibliography_count -f {{ site.scholar.bibliography }} --query @article %}</div>
<div>Number of proceedings {% bibliography_count -f {{ site.scholar.bibliography }} --query @inproceedings %}</div>

{% bibliography -f {{ site.scholar.bibliography }} %}

</div>
