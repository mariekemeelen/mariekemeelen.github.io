---
layout: page
permalink: /publications/
title: publications
description: Filter by language or key terms.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

* [**Books & Edited volumes**](#booksvols)
* [**Articles & Chapters**](#articles)
* [**Annotated Corpora & Other Datasets**](#datasets)

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="Books and Edited volumes">

<h3 id="booksvols" style="margin-top: 4.5rem; margin-bottom: -1rem;"> Books & Edited volumes </h3>

{% bibliography -f bookseditedvols %}

</div>

<div class="articles">

<h3 id="articles" style="margin-top: 4.5rem; margin-bottom: -1rem;"> Articles & Chapters </h3>

{% bibliography -f papers %}

</div>

<div class="Corpora and Datasets">


<h3 id="datasets" style="margin-top: 4.5rem; margin-bottom: -1rem;"> Books & Edited volumes </h3>

{% bibliography -f datasets %}

</div>