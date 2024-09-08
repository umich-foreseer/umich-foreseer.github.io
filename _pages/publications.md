---
layout: page
permalink: /publications/
title: Publications
description: '<a href="https://scholar.google.com/citations?hl=en&user=zr22WkQAAAAJ&view_op=list_works&sortby=pubdate">Publications on Google Scholar</a>'
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

{% if site.search_enabled %}
<input type="text" id="bibsearch" spellcheck="false" autocomplete="off" class="search bibsearch-form-input" placeholder="Type to filter">
{% endif %}

<div class="publications">

{% bibliography %}

</div>
