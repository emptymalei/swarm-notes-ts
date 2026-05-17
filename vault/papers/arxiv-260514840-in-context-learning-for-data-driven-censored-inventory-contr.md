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
  - "time-series"
  - "forecasting"
  - "stochastic-optimization"
  - "in-context-learning"
architectures:
  []
datasets:
  - "superstore"
concept_slugs:
  - "in-context-generative-posterior-sampling-icgps"
dataset_slugs:
  - "superstore"
skill: "TimeSeriesSkill"
processed_at: "2026-05-17T05:23:25Z"
created_at: "2026-05-17T05:23:25Z"
---

# In-Context Learning for Data-Driven Censored Inventory Control

**Authors**: Sohom Mukherjee, Anh-Duy Pham, Richard Pibernik, Yunbei Xu
**Date**: 2026-05-14
**Paper ID**: [arxiv:2605.14840](https://arxiv.org/abs/2605.14840)

## Summary

This paper introduces In-context Generative Posterior Sampling (ICGPS), a novel framework for inventory control with decision-dependent censoring that avoids the brittleness of parametric Thompson sampling. ICGPS utilizes meta-trained generative models to perform online in-context autoregressive completions of latent demand, which are then used to select optimal actions. The authors establish theoretical bounds on Bayesian regret and demonstrate the method's robustness to prior mismatch and distribution shift compared to standard UCB and myopic baselines, particularly on the SuperStore benchmark.

## Key Contributions

- Introduces In-context Generative Posterior Sampling (ICGPS), a framework that leverages meta-trained generative models for online decision-making under censored feedback.
- Proves that the Bayesian regret of ICGPS is bounded by a TS-like term plus a deployment penalty scaling with the completion mismatch.
- Demonstrates through the SuperStore dataset that ChronosFlow-ICGPS outperforms traditional UCB and myopic baselines, particularly under heavy censoring conditions.

## Open Questions & Future Work

- [[offline-to-online-transfer-conditions]]

## Key Concepts

- [[in-context-generative-posterior-sampling-icgps]]: A decision-making framework that meta-trains generative models offline to perform online in-context autoregressive posterior sampling for censored demand completion.

## Archivist Review

I approved the ICGPS framework and the open question regarding offline-to-online transfer conditions as they represent a significant theoretical and algorithmic contribution to data-driven operational decision-making. The SuperStore dataset is approved as a recurring benchmark for these problems. Other candidates were either too specific to the paper's implementation (e.g., specific contextual extensions) or lacked the breadth required for a permanent vault note.

### Approved Concepts
- In-context Generative Posterior Sampling (ICGPS): It provides a novel plug-in template for operational decision-making problems by leveraging generative models for latent demand completion in online settings.

### Approved Open Questions
- Offline-to-online transfer conditions: Understanding the necessary and sufficient conditions for offline-to-online transfer is crucial for the reliability of data-driven decision-making in the presence of censored feedback, which is ubiquitous in inventory management and revenue management.

## Datasets

- [[superstore]]

## Links

- [Abstract](https://arxiv.org/abs/2605.14840)
- [PDF](https://arxiv.org/pdf/2605.14840)

