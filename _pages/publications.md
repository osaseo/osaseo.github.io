---
layout: page
permalink: /publications/
title: publications & preprints
description: "Publications & preprints by categories in reversed chronological order. You can find my exhaustive [ADS library here](https://ui.adsabs.harvard.edu/public-libraries/qxzKmgEMRxaA2gqe0jcS2Q)."
nav: true
nav_order: 1
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography -f papers --group_by type %}

</div>
