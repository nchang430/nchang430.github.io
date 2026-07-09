---
layout: page
permalink: /publications/
title: publications
heading: selected publications
description: selected publications, in reverse chronological order.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography --query @*[selected=true] %}

</div>
