---
layout: page
permalink: /publications/
title: publications
description: Peer-reviewed journal publications in reverse chronological order. Selected work is also featured on the home page.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

## Selected work

<div class="publications">
{% bibliography --group_by none --query @*[selected=true]* %}
</div>

## Additional publications

<div class="publications">
{% bibliography --query @*[selected!=true]* %}

</div>
