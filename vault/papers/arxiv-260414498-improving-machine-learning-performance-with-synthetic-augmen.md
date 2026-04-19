---
# CSL-compatible fields
title: "Improving Machine Learning Performance with Synthetic Augmentation"
author:
  - literal: "Mel Sohm"
  - literal: "Charles Dezons"
  - literal: "Sami Sellami"
  - literal: "Oscar Ninou"
  - literal: "Axel Pincon"
issued:
  date-parts:
    - [2026, 4, 16]
url: "https://arxiv.org/abs/2604.14498"

# Custom fields
paper_id: "2604.14498"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "size-matched-null-augmentation"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-19T05:06:27Z"
created_at: "2026-04-19T05:06:27Z"
---

# Improving Machine Learning Performance with Synthetic Augmentation

**Authors**: Mel Sohm, Charles Dezons, Sami Sellami, Oscar Ninou, Axel Pincon
**Date**: 2026-04-16
**Paper ID**: [arxiv:2604.14498](https://arxiv.org/abs/2604.14498)

## Summary

This paper provides a rigorous statistical framework for understanding the role of synthetic augmentation in financial machine learning. By formalizing augmentation as an modification of the training distribution, the authors show it creates a structural bias-variance trade-off that depends on the task and regime. Through a new size-matched null augmentation technique, they demonstrate that synthetic data is generally only beneficial in variance-dominant forecasting tasks, while potentially inducing harmful distributional distortions in bias-dominant tasks like near-efficient market prediction.

## Key Contributions

- Formalizes synthetic augmentation as a modification of the effective training distribution, identifying the resulting structural bias-variance trade-off.
- Introduces size-matched null augmentation to decouple true information gain from trivial sample-size effects in synthetic data training.
- Demonstrates that synthetic augmentation primarily benefits variance-dominant regimes (e.g., volatility forecasting) but degrades performance in bias-dominant settings (e.g., directional prediction).

## Open Questions & Future Work

- [[identifying-augmentation-bias-variance-regimes]]

## Key Concepts

- [[size-matched-null-augmentation]]: A controlled experimental protocol that isolates the informational gain of synthetic data by maintaining identical training set sizes between original and augmented models.

## Archivist Review

The paper introduces a rigorous framework for evaluating synthetic data by isolating its statistical properties. 'Size-Matched Null Augmentation' is approved as a reusable concept for experimental design, and the open question regarding augmentation-induced trade-offs is approved as it touches on a fundamental bottleneck in synthetic data utility. No datasets were approved as none were cited as primary benchmarks or named entities unique to this study.

### Approved Concepts
- Size-Matched Null Augmentation: Provides a rigorous methodology for evaluating the marginal contribution of synthetic data by controlling for sample size expansion, decoupling informational gains from simple sample-size increases.

### Approved Open Questions
- Predicting Augmentation Bias-Variance Trade-offs: Understanding when synthetic data is harmful is critical for the reliable deployment of generative models in high-stakes financial domains.

## Links

- [Abstract](https://arxiv.org/abs/2604.14498)
- [PDF](https://arxiv.org/pdf/2604.14498)

