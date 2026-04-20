---
# CSL-compatible fields
title: "Univariate Channel Fusion for Multivariate Time Series Classification"
author:
  - literal: "Fernando Moro"
  - literal: "Vinicius M. A. Souza"
issued:
  date-parts:
    - [2026, 4, 17]
url: "https://arxiv.org/abs/2604.16119"

# Custom fields
paper_id: "2604.16119"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series-classification"
  - "multivariate-time-series"
  - "computational-efficiency"
  - "iot-deployment"
architectures:
  []
datasets:
  []
concept_slugs:
  - "univariate-channel-fusion-ucf"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-20T05:09:15Z"
created_at: "2026-04-20T05:09:15Z"
---

# Univariate Channel Fusion for Multivariate Time Series Classification

**Authors**: Fernando Moro, Vinicius M. A. Souza
**Date**: 2026-04-17
**Paper ID**: [arxiv:2604.16119](https://arxiv.org/abs/2604.16119)

## Summary

The paper introduces Univariate Channel Fusion (UCF), a computationally lightweight approach for multivariate time series classification (MTSC) designed for deployment on resource-constrained hardware. UCF aggregates multiple input channels into a single univariate representation using fusion techniques such as the mean, median, or DTW barycenter, allowing the application of existing univariate classification models. Empirical evaluations across five case studies indicate that UCF achieves competitive accuracy compared to state-of-the-art MTSC algorithms while offering substantial gains in efficiency, particularly in datasets with strong inter-channel correlations.

## Key Contributions

- Introduces Univariate Channel Fusion (UCF), a framework that maps multivariate time series into univariate space to leverage efficient univariate classifiers.
- Demonstrates that UCF maintains or improves classification accuracy across five diverse application domains while providing significant computational savings compared to complex multivariate deep learning models.
- Shows that UCF is especially effective for high-dimensional multivariate time series exhibiting strong inter-channel correlation.

## Open Questions & Future Work

- [[selective-channel-fusion-strategies]]

## Key Concepts

- [[univariate-channel-fusion-ucf]]: A lightweight method for transforming multivariate time series into a univariate representation using fusion operators like mean, median, or DTW barycenter.

## Archivist Review

I have approved the core concept of Univariate Channel Fusion as a distinct, reusable architectural strategy for resource-constrained MTSC, alongside an open question addressing the limitations of naive information collapse. The criteria applied emphasize the practical utility of these methods for real-world edge deployment and their potential to inspire more nuanced, selective fusion techniques in future forecasting architectures.

### Approved Concepts
- Univariate Channel Fusion (UCF): It provides a methodology for dimensionality reduction specifically tailored for efficient MTSC on resource-constrained hardware by repurposing univariate classifiers.

### Approved Open Questions
- Selective channel fusion strategies: Naive fusion often discards discriminative information in complex datasets; selective aggregation is key to balancing computational efficiency with predictive performance.

## Links

- [Abstract](https://arxiv.org/abs/2604.16119)
- [PDF](https://arxiv.org/pdf/2604.16119)

