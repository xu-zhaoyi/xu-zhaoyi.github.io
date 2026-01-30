---
layout: page
permalink: /publications/
title: publications
description:
nav: true
nav_order: 2
---


<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h2>Journals</h2>
{% bibliography --query @*[pubtype=journal] %}

<h2>Conferences</h2>
{% bibliography --query @*[pubtype=conference] %}

</div>
