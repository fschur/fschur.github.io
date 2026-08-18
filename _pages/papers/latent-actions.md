---
layout: paper
title: "Identifying Latent Actions and Dynamics from Offline Data via Demonstrator Diversity"
description: "An ICML workshop paper showing when unobserved actions and shared dynamics are identifiable from action-free trajectories labeled by demonstrator."
permalink: /papers/latent-actions/
keywords: "offline reinforcement learning, latent actions, system identification, demonstrator diversity, nonnegative matrix factorization, identifiability"
paper:
  short_venue: ICML Workshop
  venue: ICML Workshop on Demos (DEMO)
  year: 2026
  date: "2026-03-18"
  publication_type: conference
  arxiv: "2603.17577"
  pdf_url: https://arxiv.org/pdf/2603.17577
  authors:
    - name: Felix Schur
      orcid: https://orcid.org/0009-0006-6407-0923
summary: >-
  This work studies offline trajectories in which actions were never recorded, but the identity of each demonstrator is known. It shows that differences between demonstrator policies can supply enough variation to recover both latent actions and shared transition dynamics.
contributions:
  - Expresses the observable next-state distribution as a column-stochastic nonnegative matrix factorization.
  - Gives rank and policy-diversity conditions for identifying latent transitions and demonstrator policies up to action-label permutation.
  - Extends the result to continuous observation spaces and shows when local label ambiguities collapse to one global permutation.
abstract: >-
  Can latent actions and environment dynamics be recovered from offline trajectories when actions are never observed? We study this question in a setting where trajectories are action-free but tagged with demonstrator identity. We assume that each demonstrator follows a distinct policy, while the environment dynamics are shared across demonstrators and identity affects the next observation only through the chosen action. Under these assumptions, the conditional next-observation distribution is a mixture of latent action-conditioned transition kernels with demonstrator-specific mixing weights. We show that this induces, for each state, a column-stochastic nonnegative matrix factorization of the observable conditional distribution. Using sufficiently scattered policy diversity and rank conditions, we prove that the latent transitions and demonstrator policies are identifiable up to permutation of the latent action labels. We extend the result to continuous observation spaces via a Gram-determinant minimum-volume criterion, and show that continuity of the transition map over a connected state space upgrades local permutation ambiguities to a single global permutation. A small amount of labeled action data then suffices to fix this final ambiguity. These results establish demonstrator diversity as a principled source of identifiability for learning latent actions and dynamics from offline reinforcement-learning data.
bibtex: |
  @inproceedings{schur2026latentactions,
    title     = {Identifying Latent Actions and Dynamics from Offline Data via Demonstrator Diversity},
    author    = {Schur, Felix},
    booktitle = {ICML Workshop on Demos},
    year      = {2026},
    eprint    = {2603.17577},
    archivePrefix = {arXiv}
  }
---
