---
layout: paper
title: "DecoR: Deconfounding Time Series with Robust Regression"
description: "A JRSSB paper that turns spectrally sparse hidden confounding in time series into a robust-regression problem in the frequency domain."
permalink: /papers/decor/
keywords: "causal inference, time series, hidden confounding, robust regression, spectral sparsity, Earth system science"
paper:
  short_venue: JRSSB
  venue: "Journal of the Royal Statistical Society Series B: Statistical Methodology"
  year: 2026
  date: "2026-07-15"
  publication_type: journal
  volume: 88
  issue: 3
  firstpage: 799
  lastpage: 818
  doi: 10.1093/jrsssb/qkaf067
  external_url: https://academic.oup.com/jrsssb/advance-article/doi/10.1093/jrsssb/qkaf067/8339940
  external_label: Journal
  preprint_url: https://arxiv.org/abs/2406.07005
  code_url: https://github.com/fschur/robust_deconfounding
  authors:
    - name: Felix Schur
      orcid: https://orcid.org/0009-0006-6407-0923
    - name: Pio Blieske
    - name: Jonas Peters
summary: >-
  DecoR estimates causal effects between time series despite an unobserved time-varying confounder. When the confounder is sparse in a suitable spectral basis, the transformed problem resembles linear regression with adversarial outliers, allowing robust-regression methods to recover the causal effect.
contributions:
  - Connects spectrally sparse time-series confounding to adversarial outlier regression in the frequency domain.
  - Introduces the DecoR estimator and proves consistency under suitable assumptions.
  - Improves estimation-error bounds for two robust-regression procedures used by DecoR.
  - Demonstrates the method on synthetic data and an Earth-system-science application.
abstract: >-
  Causal inference on time series data is a challenging problem, especially in the presence of unobserved confounders. In this work, we focus on estimating the causal effect of a multivariate time series on a univariate time series when a third, possibly multivariate, time series confounds the relationship but remains unobserved. By assuming spectral sparsity of the confounder, we show how this problem can be framed as an adversarial outlier problem in the frequency domain. We introduce Deconfounding by Robust regression (DecoR), a novel approach that estimates the causal effect using robust linear regression in the frequency domain. We consider two robust regression techniques and provide improved bounds on their estimation errors. Applying these results to DecoR, we prove, under suitable assumptions, upper bounds for the estimation error of DecoR that imply consistency. We demonstrate DecoR's effectiveness through experiments on both synthetic and real-world data from Earth system science. The simulation experiments furthermore suggest that DecoR is robust with respect to model misspecification.
availability_note: The arXiv link is an earlier two-author preprint. The journal version above has the final author list and should be used for citation.
bibtex: |
  @article{schur2026decor,
    title   = {DecoR: Deconfounding Time Series with Robust Regression},
    author  = {Schur, Felix and Blieske, Pio and Peters, Jonas},
    journal = {Journal of the Royal Statistical Society Series B: Statistical Methodology},
    volume  = {88},
    number  = {3},
    pages   = {799--818},
    year    = {2026},
    doi     = {10.1093/jrsssb/qkaf067}
  }
---
