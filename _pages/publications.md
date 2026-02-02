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

<h2 id="refereed-publications">Refereed Publications</h2>
{% bibliography --query @*[keywords~=yes-refereed] %}

<h2 id="non-refereed-publications">Non-Refereed Publications</h2>
{% bibliography --query @*[keywords~=non-refereed] %}

</div>
