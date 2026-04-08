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
processed_at: "2026-04-08T04:58:30Z"
created_at: "2026-04-08T04:58:30Z"
---

# Sampling Parallelism for Fast and Efficient Bayesian Learning

**Authors**: Asena Karolin Özdemir, Lars H. Heyen, Arvid Weyrauch, Achim Streit, Markus Götz, Charlotte Debus
**Date**: 2026-04-06
**Paper ID**: [arxiv:2604.04736](https://arxiv.org/abs/2604.04736)

## Summary

This paper addresses the computational overhead of sampling-based Bayesian learning by introducing sampling parallelism, a strategy that distributes independent parameter sample evaluations across multiple GPUs. This approach reduces memory pressure and training time without necessitating architectural modifications. The authors further show that sampling parallelism can be integrated with existing data parallelism, providing an effective hybrid framework that improves augmentation diversity and training convergence.

## Key Contributions

- Introduces 'sampling parallelism', a strategy for Bayesian learning that distributes independent parameter sample evaluations across multiple GPUs to reduce memory and compute bottlenecks.
- Demonstrates that sampling parallelism can be combined with data parallelism (DDP) to create a hybrid training approach that maintains scalability.
- Shows that applying independent stochastic augmentations across sample-parallel GPUs increases augmentation diversity, potentially reducing total epochs to convergence compared to standard DDP.

## Links

- [Abstract](https://arxiv.org/abs/2604.04736)
- [PDF](https://arxiv.org/pdf/2604.04736)

