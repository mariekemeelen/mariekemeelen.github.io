---
layout: page
permalink: /publications/
title: publications
description: Filter by language or key terms.
nav: true
nav_order: 2
---

<style>
.bibliography {
  list-style: none !important;
  padding-left: 0 !important;
}

.bibliography li {
  list-style-type: none !important;
}

.bibliography .year {
  float: right;
  font-weight: bold;
}

.bibliography {
  margin-top: 2rem;
}

/*.bibliography .year {
  color: var(--global-theme-color);
  border-top: 1px solid var(--global-divider-color);
  padding-top: 1rem;
  margin-top: 2rem;
  margin-bottom: -2rem;
  text-align: right;
  font-weight: bold;
}*/

/* Hide the year in individual bibliography entries */
.bibliography .year {
  display: none;
}

/* Add spacing between bibliography entries */
.bibliography li {
  margin-bottom: 1.5rem;
}

/* Ensure year headers are still visible */
.bibliography h2.year {
  display: block;
  color: var(--global-theme-color);
  border-top: 1px solid var(--global-divider-color);
  padding-top: 1rem;
  margin-top: 2rem;
  margin-bottom: 1rem;
  text-align: right;
  font-weight: bold;
}

.bibliography .year + .bibliography > li {
  margin-top: 2rem;
}
</style>

<ul> 
	<li><a href="#booksvols"><b>Books & Edited volumes</b></a></li> 
	<li><a href="#articles"><b>Articles & Chapters</b></a></li>
	<li><a href="#datasets"><b>Annotated Corpora & Other Datasets</b></a></li> 
</ul>

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="Books and Edited volumes">

<h3 id="booksvols" style="margin-top: 4.5rem; margin-bottom: 2rem;"> Books & Edited volumes </h3>

{% bibliography -f bookseditedvols %}

</div>

<div class="articles">

<h3 id="articles" style="margin-top: 4.5rem; margin-bottom: 2rem;"> Articles & Chapters </h3>

{% bibliography -f papers %}

</div>

<div class="Corpora and Datasets">


<h3 id="datasets" style="margin-top: 4.5rem; margin-bottom: 2rem;"> Books & Edited volumes </h3>

{% bibliography -f datasets %}

</div>