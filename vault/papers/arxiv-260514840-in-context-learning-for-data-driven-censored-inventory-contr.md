---
# CSL-compatible fields
title: "In-Context Learning for Data-Driven Censored Inventory Control"
author:
  - literal: "Sohom Mukherjee"
  - literal: "Anh-Duy Pham"
  - literal: "Richard Pibernik"
  - literal: "Yunbei Xu"
issued:
  date-parts:
    - [2026, 5, 14]
url: "https://arxiv.org/abs/2605.14840"

# Custom fields
paper_id: "2605.14840"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "meta-learning"
  - "decision-making"
  - "inventory-control"
architectures:
  []
datasets:
  []
concept_slugs:
  - "in-context-generative-posterior-sampling-icgps"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-16T05:11:45Z"
created_at: "2026-05-16T05:11:45Z"
---

# In-Context Learning for Data-Driven Censored Inventory Control

**Authors**: Sohom Mukherjee, Anh-Duy Pham, Richard Pibernik, Yunbei Xu
**Date**: 2026-05-14
**Paper ID**: [arxiv:2605.14840](https://arxiv.org/abs/2605.14840)

## Summary

This paper addresses decision-dependent censored inventory control by proposing In-context Generative Posterior Sampling (ICGPS), a framework that leverages meta-trained generative models to perform online decision-making through autoregressive completion of latent demand. By combining offline learning with in-context inference, ICGPS avoids the brittleness of traditional parametric Thompson sampling under prior mismatch. Experiments using the SuperStore dataset demonstrate that the proposed ChronosFlow-ICGPS instantiation is robust to distribution shifts and achieves superior performance under heavy censoring compared to myopic and UCB-based baselines.

## Key Contributions

- Introduces ICGPS, a meta-trained in-context generative framework for censored decision-making that bridges the gap between offline imputation and online Thompson sampling.
- Proves that the Bayesian regret of ICGPS is bounded by the regret of an ideal TS benchmark plus a deployment penalty related to the online completion mismatch.
- Demonstrates that ChronosFlow-ICGPS achieves sublinear Bayesian regret in the repeated newsvendor setting and outperforms UCB-style baselines, particularly under heavy censoring and distribution shifts.

## Open Questions & Future Work

- [[identifiability-in-censored-demand]]

## Key Concepts

- [[in-context-generative-posterior-sampling-icgps]]: A meta-learning framework that performs online decision-making by using in-context autoregressive generation to sample from learned completions of latent demand.

## Archivist Review

I have approved the ICGPS framework as a foundational concept for decision-dependent censored learning and the open question regarding identifiability barriers in censored demand. I rejected the contextual/non-stationary extension as it is a standard, open-ended research direction rather than a specific unresolved problem. No datasets were approved as 'SuperStore' is a routine industry dataset.

### Approved Concepts
- In-context Generative Posterior Sampling (ICGPS): ICGPS provides a meta-learning-based, in-context approach to decision-dependent censored inventory control, addressing brittleness in traditional parametric Thompson sampling.

### Approved Open Questions
- Identifiability in Censored Demand: Understanding these identifiability barriers is essential for developing theoretically sound algorithms that can handle real-world inventory settings with extreme stockout rates where traditional estimation techniques fail.

### Rejected Candidates
- [open_question] Contextual and Non-stationary Control (`contextual-non-stationary-inventory-control`) - low_impact: The proposal is a broad request for extensions rather than a specific unresolved research bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2605.14840)
- [PDF](https://arxiv.org/pdf/2605.14840)

