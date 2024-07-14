---
layout: page
permalink: /presentations/
title: Presentations
description:
nav: true
nav_order: 2
---

<!-- _pages/presentations.md -->

{% if site.search_enabled %}
<input type="text" id="bibsearch" spellcheck="false" autocomplete="off" class="search bibsearch-form-input" placeholder="Type to filter">
{% endif %}

<div class="publications">

{% bibliography --file presentations.bib %}

</div>
