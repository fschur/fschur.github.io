---
layout: paper
title: "The Price of Knowledge: Optimal Algorithms for Costly Bandits"
description: "A UAI 2026 paper on stochastic bandits where observing rewards is optional and incurs action-dependent costs."
permalink: /papers/price-of-knowledge/
keywords: "costly bandits, stochastic bandits, Gaussian processes, active learning, information gain, reinforcement learning"
paper:
  short_venue: UAI
  venue: 42nd Conference on Uncertainty in Artificial Intelligence (UAI)
  year: 2026
  date: "2026"
  publication_type: conference
  external_url: https://openreview.net/forum?id=PLY9BJ5uB0
  external_label: OpenReview
  authors:
    - name: Felix Schur
      orcid: https://orcid.org/0009-0006-6407-0923
    - name: Jesus Lago
    - name: Tanner Fiez
summary: >-
  This paper studies bandit learning when feedback itself has a price. The learner must decide not only which action to take, but also whether the information gained from observing its reward is worth an action-dependent cost.
contributions:
  - Establishes a structural reduction to two-phase policies that explore with paid observations and then commit without further observation.
  - Introduces cost-sensitive information-gain measures for minimax and instance-dependent analysis.
  - Develops C3-GP and GP-C-LUCB and proves regret guarantees for correlated actions with heterogeneous observation costs.
  - Gives matching lower and upper bounds, up to constants or logarithmic factors, for finite independent-action problems.
abstract: >-
  We study stochastic bandits in which observing a reward is optional but incurs an action-dependent cost. This setting captures applications where feedback acquisition, such as human evaluation or randomized testing, is expensive, and the learner must trade off exploration, exploitation, and observation cost. We formulate regret to include both reward loss and the cumulative cost of requested observations. Our first result is structural: for minimizing regret, it is without loss of generality to consider two-phase policies that first request observations during an exploration phase and then commit to a single action without further observations. Building on this reduction, we introduce two cost-sensitive complexity measures that extend maximum information gain: a cost-adjusted information gain for minimax analysis, and a cost- and gap-adjusted information gain for instance-dependent analysis. Using these quantities, we develop two Gaussian-process-based algorithms, C3-GP and GP-C-LUCB, and derive regret upper bounds for correlated-action settings with heterogeneous observation costs. In the finite independent-action setting, we further prove matching lower and upper bounds, up to constants or logarithmic factors, yielding a tight characterization of both minimax and instance-dependent regret in terms of the proposed cost-aware complexity measures.
bibtex: |
  @inproceedings{schur2026priceofknowledge,
    title     = {The Price of Knowledge: Optimal Algorithms for Costly Bandits},
    author    = {Schur, Felix and Lago, Jesus and Fiez, Tanner},
    booktitle = {42nd Conference on Uncertainty in Artificial Intelligence},
    year      = {2026}
  }
---
