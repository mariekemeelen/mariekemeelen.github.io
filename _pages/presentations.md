---
layout: page
permalink: /presentations/
title: presentations
description: 
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
/* Force all bibliography sections and entries to be visible */
.bibliography,
.bibliography li,
div[class*="Invited"],
div[class*="Conference"],
div[class*="Workshop"] {
  display: block !important;
  visibility: visible !important;
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
