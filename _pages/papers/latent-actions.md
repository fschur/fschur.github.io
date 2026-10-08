---
layout: paper
title: "Action-Free Offline RL via Demonstrator Diversity"
description: "An ICML workshop paper showing when unobserved actions and shared dynamics are identifiable from action-free trajectories labeled by demonstrator."
permalink: /papers/latent-actions/
keywords: "offline reinforcement learning, latent actions, system identification, demonstrator diversity, nonnegative matrix factorization, identifiability"
paper:
  short_venue: ICML Workshop
  venue: ICML Workshop on Demos (DEMO)
  year: 2026
  date: "2026"
  publication_type: conference
  external_url: https://icml.cc/virtual/2026/83703
  external_label: Workshop
  arxiv: "2603.17577"
  pdf_url: https://openreview.net/pdf?id=ntiSNot21h
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
  A central bottleneck in transitioning from offline representation learning to online decision-making is the "action gap": passive datasets (e.g., online videos) often lack the action labels required to ground latent representations in environment dynamics. We propose to bridge this gap by exploiting demonstrator diversity. Even when actions are unobserved, systematic variation in transitions across demonstrators can help disentangle latent action choice from environment stochasticity. We formalize this as a statewise column-stochastic non-negative matrix factorization (NMF) problem, where demonstrator-specific policies act as mixtures over shared latent transition kernels. Under "sufficiently scattered" policy diversity and rank conditions, we prove that latent actions and dynamics are identifiable up to a permutation. We extend these results to continuous observation spaces via a Gram-determinant minimum-volume criterion and prove that spatial continuity ensures a globally consistent action labeling. Our framework shows how heterogeneity in passive data can substitute for missing action labels, leaving limited interaction to resolve only the final action-label alignment.
availability_note: 'The arXiv version uses the earlier title "Identifying Latent Actions and Dynamics from Offline Data via Demonstrator Diversity".'
bibtex: |
  @inproceedings{schur2026latentactions,
    title     = {Action-Free Offline {RL} via Demonstrator Diversity},
    author    = {Schur, Felix},
    booktitle = {ICML Workshop on Demos},
    year      = {2026},
    eprint    = {2603.17577},
    archivePrefix = {arXiv},
    url       = {https://icml.cc/virtual/2026/83703}
  }
---
