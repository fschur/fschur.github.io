---
layout: paper
title: "Lifelong Bandit Optimization: No Prior and No Regret"
description: "A UAI 2023 paper on meta-learning a shared kernel across sequential bandit-optimization tasks while retaining no-regret guarantees."
permalink: /papers/lifelong-bandit-optimization/
keywords: "bandit optimization, meta-learning, Bayesian optimization, kernel learning, lifelong learning, federated learning"
paper:
  short_venue: UAI
  venue: Proceedings of the 39th Conference on Uncertainty in Artificial Intelligence (UAI)
  year: 2023
  date: "2023"
  publication_type: conference
  external_url: https://proceedings.mlr.press/v216/schur23a.html
  external_label: Proceedings
  arxiv: "2210.15513"
  pdf_url: /assets/pdf/schur23a.pdf
  firstpage: 1847
  lastpage: 1857
  authors:
    - name: Felix Schur
      orcid: https://orcid.org/0009-0006-6407-0923
    - name: Parnian Kassraie
    - name: Jonas Rothfuss
    - name: Andreas Krause
summary: >-
  LIBO learns across a sequence of related bandit-optimization tasks. Rather than assuming a known prior or kernel, it estimates a shared kernel from past tasks and becomes progressively more sample-efficient while preserving no-regret behavior.
contributions:
  - Introduces lifelong bandit optimization with an unknown kernel shared across tasks.
  - Proves oracle-optimal performance as the learned kernel approaches the true shared kernel.
  - Provides a federated variant, F-LIBO, that achieves sublinear lifelong regret without direct access to each task's raw data.
abstract: >-
  Machine learning algorithms are often repeatedly applied to problems with similar structure over and over again. We focus on solving a sequence of bandit optimization tasks and develop LIBO, an algorithm which adapts to the environment by learning from past experience and becomes more sample-efficient in the process. We assume a kernelized structure where the kernel is unknown but shared across all tasks. LIBO sequentially meta-learns a kernel that approximates the true kernel and solves the incoming tasks with the latest kernel estimate. Our algorithm can be paired with any kernelized or linear bandit algorithm and guarantees oracle optimal performance, meaning that as more tasks are solved, the regret of LIBO on each task converges to the regret of the bandit algorithm with oracle knowledge of the true kernel. Naturally, if paired with a sublinear bandit algorithm, LIBO yields a sublinear lifelong regret. We also show that direct access to the data from each task is not necessary for attaining sublinear regret. We propose F-LIBO, which solves the lifelong problem in a federated manner.
bibtex: |
  @inproceedings{schur2023lifelong,
    title     = {Lifelong Bandit Optimization: No Prior and No Regret},
    author    = {Schur, Felix and Kassraie, Parnian and Rothfuss, Jonas and Krause, Andreas},
    booktitle = {Proceedings of the 39th Conference on Uncertainty in Artificial Intelligence},
    pages     = {1847--1857},
    year      = {2023},
    publisher = {PMLR}
  }
---
