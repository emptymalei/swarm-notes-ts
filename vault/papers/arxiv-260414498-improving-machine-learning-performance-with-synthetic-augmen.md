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
processed_at: "2026-04-17T05:06:03Z"
created_at: "2026-04-17T05:06:03Z"
---

# Improving Machine Learning Performance with Synthetic Augmentation

**Authors**: Mel Sohm, Charles Dezons, Sami Sellami, Oscar Ninou, Axel Pincon
**Date**: 2026-04-16
**Paper ID**: [arxiv:2604.14498](https://arxiv.org/abs/2604.14498)

## Summary

This paper provides a structural analysis of synthetic data augmentation in financial machine learning, characterizing it as a trade-off between reducing estimation error and introducing population-level distributional bias. The authors propose a methodological framework, featuring a size-matched null augmentation and block permutation test, to rigorously differentiate informational gains from simple sample-size effects. Their empirical evaluation across various generative models and financial datasets demonstrates that augmentation success is regime-dependent, favoring variance-reduction tasks while potentially distorting performance in bias-sensitive domains.

## Key Contributions

- Formalizes synthetic augmentation as an effective training distribution modification, revealing a structural bias-variance trade-off in financial ML models.
- Introduces a size-matched null augmentation and non-parametric block permutation test to isolate informational content from sample-size effects.
- Demonstrates that synthetic augmentation benefits variance-dominant regimes (e.g., volatility forecasting) but degrades performance in bias-dominant tasks (e.g., directional prediction).

## Open Questions & Future Work

- [[synthetic-augmentation-informational-value-vs-bias]]

## Key Concepts

- [[size-matched-null-augmentation]]: A framework to isolate information gains from mechanical sample-size effects in synthetic data augmentation.

## Archivist Review

The paper offers a valuable structural analysis of synthetic data augmentation in financial machine learning, shifting the focus from empirical performance to the inherent bias-variance trade-offs. The concept of 'Size-matched Null Augmentation' provides a much-needed methodological control for assessing if generative models truly add information or merely inflate sample size. The approved open question addresses the critical need to distinguish between genuine predictive insights and distributional distortion, which is essential for the long-term reliability of synthetic data approaches.

### Approved Concepts
- Size-matched Null Augmentation: Provides a rigorous baseline to separate information gain from pure sample-size scaling in synthetic data generation experiments.

### Approved Open Questions
- Defining synthetic informational gain: Financial datasets are characterized by weak signals, structural change, and rare critical events, making it technically critical to move beyond benchmark-specific performance claims toward a structural understanding of when synthetic augmentation is safe or harmful.

## Links

- [Abstract](https://arxiv.org/abs/2604.14498)
- [PDF](https://arxiv.org/pdf/2604.14498)

