---
layout: paper
title: "Who Caused Y? Learning Causal Parents Using Independent Risk Minimization"
description: "A NeurIPS 2026 paper on identifying and estimating the direct causes of a target variable from observational data using Independent Risk Minimization."
permalink: /papers/who-caused-y/
keywords: "causal discovery, causal parents, identifiability, additive-noise models, independent risk minimization, observational data"
paper:
  short_venue: NeurIPS
  venue: Advances in Neural Information Processing Systems (NeurIPS)
  year: 2026
  date: "2026"
  publication_type: conference
  external_url: https://openreview.net/forum?id=kvVc2NQe9H
  external_label: OpenReview
  authors:
    - name: Felix Schur
      orcid: https://orcid.org/0009-0006-6407-0923
    - name: Sorawit Saengkyongam
    - name: Jonas Peters
summary: >-
  Independent Risk Minimization (IndRM) estimates the direct causes of a target variable from observational data. The paper assumes an additive-noise model for the target while allowing general functional relationships and hidden confounding among the other variables. Under an additional no-backward additive-noise condition, the paper identifies the target's parents using residual independence, minimum residual variance, and a smallest-set tie-break.
contributions:
  - Proves identifiability of the target's parent set under target-specific additive-noise and no-backward conditions.
  - Uses identifiability witnesses to show that residual independence for sets containing descendants holds only on Lebesgue-null exceptional parameter sets in finite-dimensional analytic model classes with a witness.
  - Introduces IndRM for estimating the target's parents without a full-graph search.
abstract: >-
  We study identifiability and estimation of the direct causes, that is, the parents, of a designated target Y in a structural causal model using only observational data. Our main assumption is an additive-noise model for Y: the value of Y equals some function of its parents plus noise that is independent of those parents. We allow for general functional relationships and hidden confounding among all other variables. We prove that under a "no-backward" additive-noise condition the true parent set, PA(Y), is identified from the observational distribution by a simple population principle: among all candidate variable sets that make the regression residual of Y independent of the regressors, choose the one with the smallest residual variance, and—if several tie—the smallest set. To justify the "no-backward" condition, we propose a novel identifiability scheme based on identifiability witnesses: we prove that in finite-dimensional analytic model classes, for which we have an identifiability witness (that is, a single identifiable model), residual independence for sets containing descendants of Y holds only on Lebesgue-null exceptional parameter sets. This scheme is strong enough to recover known identifiability results. For finite data, we propose Independent Risk Minimization (IndRM), which offers a simple, local, and non-interventional route to isolating the direct causes of Y in multivariate systems, avoiding global model assumptions and full-graph search.
bibtex: |
  @inproceedings{schur2026whocausedy,
    title     = {Who Caused {Y}? Learning Causal Parents Using Independent Risk Minimization},
    author    = {Schur, Felix and Saengkyongam, Sorawit and Peters, Jonas},
    booktitle = {Advances in Neural Information Processing Systems},
    year      = {2026},
    url       = {https://openreview.net/forum?id=kvVc2NQe9H}
  }
---
