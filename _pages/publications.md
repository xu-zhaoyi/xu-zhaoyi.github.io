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

<div class="Publications">

##Journals
{% bibliography --query @*[pubtype=journal] %}

## Conferences
{% bibliography --query @*[pubtype=conference] %}


</div>


<!--  {% bibliography %}  -->
