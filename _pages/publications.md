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
  list-style: none;
}
/* Remove numbers from bibliography list */
.bibliography {
  list-style: none;
  padding-left: 0;
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

/* Style for BIB button specifically */
.links .bibtex.btn {
  color: var(--global-text-color) !important;
  background-color: transparent !important;
  border: 1px solid var(--global-text-color) !important;
}

.links .bibtex.btn:hover {
  background-color: var(--global-theme-color) !important;
  color: white !important;
  border-color: var(--global-theme-color) !important;
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
/* Force all bibliography sections and entries to be visible */
.bibliography,
.bibliography li,
div[class*="Books"],
div[class*="articles"],
div[class*="Corpora"] {
  display: block !important;
  visibility: visible !important;
}
</style>

<ul> 
  <li><a href="#booksvols"><b>Books & Edited volumes</b></a></li> 
  <li><a href="#articles"><b>Peer-Reviewed Articles & Chapters</b></a></li>
  <li><a href="#datasets"><b>Annotated Corpora & Other Datasets</b></a></li> 
</ul>

{% include bib_search.liquid %}

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