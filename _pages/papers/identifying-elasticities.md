---
layout: paper
title: Identifying Elasticities in Autocorrelated Time Series Using Causal Graphs
description: "A causal-graph approach to selecting valid instrumental-variable estimators for autocorrelated time series, applied to electricity demand."
permalink: /papers/identifying-elasticities/
keywords: "causal graphs, instrumental variables, autocorrelated time series, price elasticity, econometrics, electricity demand"
paper:
  short_venue: arXiv
  venue: arXiv preprint
  year: 2024
  date: "2024-09-23"
  publication_type: preprint
  arxiv: "2409.15530"
  pdf_url: /assets/pdf/tiedemann24.pdf
  authors:
    - name: Silvana Tiedemann
    - name: Jorge Sanchez Canales
    - name: Felix Schur
      orcid: https://orcid.org/0009-0006-6407-0923
    - name: Raffaele Sgarlato
    - name: Lion Hirth
    - name: Oliver Ruhnau
    - name: Jonas Peters
summary: >-
  Naive instrumental-variable estimators can become inconsistent when prices and quantities are autocorrelated. This paper uses causal time graphs to make the required assumptions explicit, derive valid estimators, and diagnose model misspecification through disagreement between estimators.
contributions:
  - Models simultaneous price–quantity determination with an unobserved confounder while retaining a directed acyclic graph representation.
  - Uses graphical identification results to derive instrumental-variable estimators that remain valid under autocorrelation.
  - Applies the framework to simulated data and German electricity-market data.
abstract: >-
  The price elasticity of demand can be estimated from observational data using instrumental variables (IV). However, naive IV estimators may be inconsistent in settings with autocorrelated time series. We argue that causal time graphs can simplify IV identification and help select consistent estimators. To do so, we propose to first model the equilibrium condition by an unobserved confounder, deriving a directed acyclic graph (DAG) while maintaining the assumption of a simultaneous determination of prices and quantities. We then exploit recent advances in graphical inference to derive valid IV estimators, including estimators that achieve consistency by simultaneously estimating nuisance effects. We further argue that observing significant differences between the estimates of presumably valid estimators can help to reject false model assumptions, thereby improving our understanding of underlying economic dynamics. We apply this approach to the German electricity market, estimating the price elasticity of demand on simulated and real-world data. The findings underscore the importance of accounting for structural autocorrelation in IV-based analysis.
bibtex: |
  @misc{tiedemann2024identifyingelasticities,
    title  = {Identifying Elasticities in Autocorrelated Time Series Using Causal Graphs},
    author = {Tiedemann, Silvana and Sanchez Canales, Jorge and Schur, Felix and Sgarlato, Raffaele and Hirth, Lion and Ruhnau, Oliver and Peters, Jonas},
    year   = {2024},
    eprint = {2409.15530},
    archivePrefix = {arXiv},
    primaryClass = {econ.EM}
  }
---
