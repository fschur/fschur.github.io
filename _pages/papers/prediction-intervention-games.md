---
layout: paper
title: Prediction-Intervention Games and Invariant Sets
description: "A NeurIPS 2026 paper on robust prediction when another agent responds by intervening on covariates in an underlying causal model."
permalink: /papers/prediction-intervention-games/
keywords: "causal inference, invariant prediction, Stackelberg games, strategic prediction, distribution generalization, stable blanket"
paper:
  short_venue: NeurIPS
  venue: Advances in Neural Information Processing Systems (NeurIPS)
  year: 2026
  date: "2026"
  publication_type: conference
  external_url: https://openreview.net/forum?id=XRaoy63niz
  external_label: OpenReview
  arxiv: "2605.16828"
  pdf_url: https://arxiv.org/pdf/2605.16828
  code_url: https://github.com/LinusKuehne/prediction-intervention-games
  authors:
    - name: Linus Kühne
    - name: Felix Schur
      orcid: https://orcid.org/0009-0006-6407-0923
    - name: Jonas Peters
summary: >-
  The paper formalizes prediction as a leader–follower game: a predictor is chosen from observational data, then another agent intervenes on covariates to optimize a separate objective. It investigates invariant predictors that remain reliable after this strategic response.
contributions:
  - Introduces prediction–intervention games as a causal Stackelberg-game framework.
  - Proves that stable-blanket predictors weakly dominate causal-parent predictors in the game for two common classes of follower objectives.
  - Connects post-intervention performance to worst-case risk and gives conditions for worst-case optimality.
  - Provides practical strategies when the causal graph is unknown, tested on simulated and real data.
abstract: >-
  We consider the following two-player game: using observational data, the leader chooses a prediction function for a response variable Y from given covariates. The follower then reacts with an intervention on some covariates in the underlying structural causal model to maximize their own objective. The leader knows the intervention targets, but may have limited knowledge of the follower's objective. We call this setup a prediction-intervention game, a special case of a Stackelberg game. Finding an optimal strategy for the leader is generally difficult. To avoid severe performance loss, the leader may base their prediction on the causal parents of Y, or more generally on an invariant subset of covariates. We prove that predictors based on the stable blanket, a specific invariant subset, weakly dominate those based on the causal parents in the game for two common classes of follower objectives. We further upper bound the leader's post-intervention risk by a worst-case risk over allowed interventions and strengthen existing distribution generalization results to analyze this bound: we give sufficient conditions under which stable-blanket predictors are worst-case optimal, and show by examples that these conditions cannot in general be dropped. Finally, we discuss practical strategies when the causal graph is unknown and test them on simulated and real-world data.
bibtex: |
  @inproceedings{kuehne2026predictionintervention,
    title     = {Prediction-Intervention Games and Invariant Sets},
    author    = {Kühne, Linus and Schur, Felix and Peters, Jonas},
    booktitle = {Advances in Neural Information Processing Systems},
    year      = {2026},
    eprint    = {2605.16828},
    archivePrefix = {arXiv},
    primaryClass = {stat.ML},
    url       = {https://openreview.net/forum?id=XRaoy63niz}
  }
---
