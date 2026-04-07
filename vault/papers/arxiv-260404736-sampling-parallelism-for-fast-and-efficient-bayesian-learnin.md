---
# CSL-compatible fields
title: "Sampling Parallelism for Fast and Efficient Bayesian Learning"
author:
  - literal: "Asena Karolin Özdemir"
  - literal: "Lars H. Heyen"
  - literal: "Arvid Weyrauch"
  - literal: "Achim Streit"
  - literal: "Markus Götz"
  - literal: "Charlotte Debus"
issued:
  date-parts:
    - [2026, 4, 6]
url: "https://arxiv.org/abs/2604.04736"

# Custom fields
paper_id: "2604.04736"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-07T04:52:59Z"
created_at: "2026-04-07T04:52:59Z"
---

# Sampling Parallelism for Fast and Efficient Bayesian Learning

**Authors**: Asena Karolin Özdemir, Lars H. Heyen, Arvid Weyrauch, Achim Streit, Markus Götz, Charlotte Debus
**Date**: 2026-04-06
**Paper ID**: [arxiv:2604.04736](https://arxiv.org/abs/2604.04736)

## Summary

The paper addresses the computational intensity of Bayesian neural network training by proposing sampling parallelism, a method that distributes the evaluation of individual parameter samples across multiple GPUs. This approach mitigates memory bottlenecks associated with Bayesian sampling while remaining compatible with existing distributed data parallelism strategies. Experiments demonstrate near-linear scaling and improved convergence rates due to increased stochastic augmentation diversity, making Bayesian uncertainty quantification more accessible for large-scale applications.

## Key Contributions

- Introduces sampling parallelism, a parallelization strategy that distributes Bayesian sample evaluations across multiple GPUs to reduce memory and compute bottlenecks.
- Demonstrates that sampling parallelism can be combined with distributed data parallelism (DDP) as a hybrid approach for efficient BNN training.
- Shows that sampling parallelism increases effective augmentation diversity by applying independent stochastic augmentations across GPUs, leading to faster convergence in terms of training epochs.

## Links

- [Abstract](https://arxiv.org/abs/2604.04736)
- [PDF](https://arxiv.org/pdf/2604.04736)

