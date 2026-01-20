---
layout: page
permalink: /publications/
title: publications
description: Filter by language or key terms.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography -f papers %}

</div>

<div class="Books and Edited volumes">

{% bibliography -f bookseditedvols %}

</div>

<div class="Corpora and Datasets">

{% bibliography -f datasets %}

</div>