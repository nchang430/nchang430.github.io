---
layout: page
permalink: /publications/
title: publications
heading: selected publications
description:
nav: true
nav_order: 2
_styles: >
  .publications h2.bibliography {
    color: var(--global-text-color);
  }
---

<!-- _pages/publications.md -->

<div class="publications">

{% bibliography --query @*[selected=true] %}

</div>
