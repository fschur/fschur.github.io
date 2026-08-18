---
layout: paper
title: "Many Experiments, Few Repetitions, Unpaired Data, and Sparse Effects: Is Causal Inference Possible?"
description: "An ICML 2026 Spotlight paper on causal effect estimation from many environments when covariates and outcomes are observed in separate, unpaired samples."
permalink: /papers/many-experiments/
keywords: "causal inference, unpaired data, instrumental variables, sparse effects, GMM, many environments"
paper:
  short_venue: ICML Spotlight
  venue: International Conference on Machine Learning (ICML)
  year: 2026
  date: "2026-01-21"
  publication_type: conference
  status: Spotlight
  arxiv: "2601.15254"
  pdf_url: https://arxiv.org/pdf/2601.15254
  authors:
    - name: Felix Schur
      orcid: https://orcid.org/0009-0006-6407-0923
    - name: Niklas Pfister
    - name: Peng Ding
    - name: Sach Mukherjee
    - name: Jonas Peters
summary: >-
  This paper asks whether causal effects can be recovered when experiments are plentiful but each experiment is small, and when covariates and outcomes are never observed together. It recasts the environments as a high-dimensional instrument and introduces SplitUP, a sample-splitting estimator designed for this unusual many-environment regime.
contributions:
  - Shows why standard two-sample instrumental-variable estimators can fail when the number of environments grows but repetitions per environment stay fixed.
  - Introduces a cross-fold, GMM-type estimator that is consistent in this regime.
  - Extends the estimator to sparse causal effects using L1 regularization and post-selection refitting.
abstract: >-
  We study the problem of estimating causal effects under hidden confounding in the following unpaired data setting: we observe some covariates and an outcome under different experimental conditions (environments) but do not observe them jointly—we either observe the covariates or the outcome. Under appropriate regularity conditions, the problem can be cast as an instrumental variable (IV) regression with the environment acting as a (possibly high-dimensional) instrument. When there are many environments but only a few observations per environment, standard two-sample IV estimators fail to be consistent. We propose a GMM-type estimator (SplitUP) based on cross-fold sample splitting of the instrument–covariate sample and prove that it is consistent as the number of environments grows but the sample size per environment remains constant. We further extend the method to sparse causal effects via L1-regularized estimation and post-selection refitting.
bibtex: |
  @inproceedings{schur2026manyexperiments,
    title     = {Many Experiments, Few Repetitions, Unpaired Data, and Sparse Effects: Is Causal Inference Possible?},
    author    = {Schur, Felix and Pfister, Niklas and Ding, Peng and Mukherjee, Sach and Peters, Jonas},
    booktitle = {International Conference on Machine Learning},
    year      = {2026},
    note      = {Spotlight},
    eprint    = {2601.15254},
    archivePrefix = {arXiv}
  }
---
