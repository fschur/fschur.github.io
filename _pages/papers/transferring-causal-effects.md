---
layout: paper
title: Transferring Causal Effects using Proxies
description: "A NeurIPS 2025 paper on identifying and estimating target-domain causal effects using a proxy for an unobserved confounder."
permalink: /papers/transferring-causal-effects/
keywords: "causal inference, transportability, proxy variables, hidden confounding, multi-domain learning, causal effect estimation"
paper:
  short_venue: NeurIPS
  venue: Advances in Neural Information Processing Systems (NeurIPS)
  year: 2025
  date: "2025-10-29"
  publication_type: conference
  external_url: https://openreview.net/forum?id=8owMKkQIy0
  external_label: OpenReview
  arxiv: "2510.25924"
  pdf_url: https://arxiv.org/pdf/2510.25924
  authors:
    - name: Manuel Iglesias-Alonso
    - name: Felix Schur
      orcid: https://orcid.org/0009-0006-6407-0923
    - name: Julius von Kügelgen
    - name: Jonas Peters
summary: >-
  This paper considers causal-effect estimation across domains when the effect is hidden-confounded and may vary from one domain to another. The target domain contains only a proxy for the confounder; the paper shows how information from other domains can nevertheless identify and estimate the target effect.
contributions:
  - Proves identifiability using proxy observations in a multi-domain setting, including extensions with continuous treatment and response variables.
  - Introduces two consistent estimators and derives confidence intervals.
  - Evaluates the methods in simulations and in a study of how website rankings affect consumer choices.
abstract: >-
  We consider the problem of estimating a causal effect in a multi-domain setting. The causal effect of interest is confounded by an unobserved confounder and can change between the different domains. We assume that we have access to a proxy of the hidden confounder and that all variables are discrete or categorical. We propose methodology to estimate the causal effect in the target domain, where we assume to observe only the proxy variable. Under these conditions, we prove identifiability, even when treatment and response variables are continuous. We introduce two estimation techniques, prove consistency, and derive confidence intervals. The theoretical results are supported by simulation studies and a real-world example studying the causal effect of website rankings on consumer choices.
bibtex: |
  @inproceedings{iglesias2025transferring,
    title     = {Transferring Causal Effects using Proxies},
    author    = {Iglesias-Alonso, Manuel and Schur, Felix and von Kügelgen, Julius and Peters, Jonas},
    booktitle = {Advances in Neural Information Processing Systems},
    year      = {2025},
    eprint    = {2510.25924},
    archivePrefix = {arXiv}
  }
---
