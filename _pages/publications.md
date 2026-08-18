---
layout: page
permalink: /publications/
title: publications
description: Research papers and preprints by Felix Schur on causal inference, reinforcement learning, bandit algorithms, time series, and statistical machine learning.
nav: true
nav_order: 2
---

<style>
  .publications ol.bibliography > li > .row {
    display: grid;
    grid-template-columns: 7rem minmax(0, 1fr);
    gap: 1rem;
    margin-left: 0;
    margin-right: 0;
  }

  .publications ol.bibliography > li > .row > .abbr,
  .publications ol.bibliography > li > .row > [class*="col-sm-"] {
    min-width: 0;
    max-width: none;
    padding-left: 0;
    padding-right: 0;
    width: auto;
  }

  .publications ol.bibliography > li > .row > .abbr .badge {
    display: block;
    margin-bottom: 0.25rem;
    width: 100% !important;
  }

  .publications pre {
    max-width: 100%;
    overflow-x: auto;
  }

  @media (max-width: 575.98px) {
    .publications ol.bibliography > li > .row {
      grid-template-columns: minmax(0, 1fr);
      gap: 0.35rem;
    }

    .publications ol.bibliography > li > .row > .abbr {
      display: flex;
      flex-wrap: wrap;
      gap: 0.25rem;
    }

    .publications ol.bibliography > li > .row > .abbr .badge {
      margin-bottom: 0;
      width: auto !important;
    }
  }
</style>

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography %}

</div>
