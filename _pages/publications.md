---
layout: page
permalink: /publications/
title: publications
description: 
nav: true
nav_order: 2
---

<style>
/* Add spacing between bibliography entries */
.bibliography li {
  margin-bottom: 1.5rem;
}

/* Style for DOI and other link buttons */
.links .btn {
  border: 1px solid var(--global-text-color);
  padding: 0.25rem 0.5rem;
  margin-right: 0.5rem;
  text-decoration: none;
  color: var(--global-text-color);
  background-color: transparent;
  border-radius: 0.25rem;
  font-size: 0.875rem;
}

.links .btn:hover {
  background-color: var(--global-theme-color);
  color: white;
  border-color: var(--global-theme-color);
}

/* Hide abstract and bibtex by default */
.abstract.hidden,
.bibtex.hidden {
  display: none;
}

/* Show when JavaScript adds 'open' class */
.abstract.hidden.open,
.bibtex.hidden.open {
  display: block;
}
</style>

<!-- <style>

.hidden {
  display: none !important;
}

/* Style for DOI and other link buttons */
.links .btn {
  border: 1px solid var(--global-text-color);
  padding: 0.25rem 0.5rem;
  margin-right: 0.5rem;
  text-decoration: none;
  color: var(--global-text-color);
  background-color: transparent;
  border-radius: 0.25rem;
  font-size: 0.875rem;
}

.links .btn:hover {
  background-color: var(--global-theme-color);
  color: white;
  border-color: var(--global-theme-color);
}

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
 -->
<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<ul> 
	<li><a href="#booksvols"><b>Books & Edited volumes</b></a></li> 
	<li><a href="#articles"><b>Peer-Reviewed Articles & Chapters</b></a></li>
	<li><a href="#datasets"><b>Annotated Corpora & Other Datasets</b></a></li> 
</ul>

<div class="Books and Edited volumes">

<h3 id="booksvols" style="margin-top: 4.5rem; margin-bottom: 2rem;"> Books & Edited volumes </h3>

{% bibliography -f bookseditedvols %}

</div>

<div class="articles">

<h3 id="articles" style="margin-top: 4.5rem; margin-bottom: 2rem;"> Peer-Reviewed Articles & Chapters </h3>

{% bibliography -f papers %}

</div>

<div class="Corpora and Datasets">


<h3 id="datasets" style="margin-top: 4.5rem; margin-bottom: 2rem;"> Annotated Corpora & Other Datasets </h3>

{% bibliography -f datasets %}

</div>