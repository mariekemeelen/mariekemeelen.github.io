---
layout: page
permalink: /presentations/
title: presentations
description: Filter by key term or location.
nav: true
nav_order: 3
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

<!-- _pages/presentations.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}


<ul> 
	<li><a href="#InvitedTalks"><b>Invited Talks</b></a></li> 
	<li><a href="#ConferenceTalks"><b>Peer-Reviewed Conference Presentations</b></a></li>
</ul>

<div class="Invited Talks">

<h3 id="InvitedTalks" style="margin-top: 4.5rem; margin-bottom: 2rem;"> Invited Talks</h3>

{% bibliography -f invitedtalks %}

</div>

<div class="Peer-Reviewed Conference Presentations">

<h3 id="ConferenceTalks" style="margin-top: 4.5rem; margin-bottom: 2rem;"> Peer-Reviewed Conference Presentations</h3>

{% bibliography -f presentations %}

</div>
