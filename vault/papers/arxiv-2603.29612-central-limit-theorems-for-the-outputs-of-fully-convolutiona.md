---
# CSL-compatible fields
title: "Central limit theorems for the outputs of fully convolutional neural networks with time series input"
author:
  - literal: "Annika Betken"
  - literal: "Giorgio Micali"
  - literal: "Johannes Schmidt-Hieber"
issued:
  date-parts:
    - [2026, 3, 31]
url: "https://arxiv.org/abs/2603.29612"

# Custom fields
paper_id: "2603.29612"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "global-weighted-pooling"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-02T05:40:27Z"
created_at: "2026-04-02T05:40:27Z"
---

# Central limit theorems for the outputs of fully convolutional neural networks with time series input

**Authors**: Annika Betken, Giorgio Micali, Johannes Schmidt-Hieber
**Date**: 2026-03-31
**Paper ID**: [arxiv:2603.29612](https://arxiv.org/abs/2603.29612)

## Summary

This paper establishes a theoretical foundation for the behavior of fully convolutional neural networks (FCNs) applied to time series data. The authors prove that, under the assumption of short-range dependent linear processes, FCN outputs with global average pooling converge to a Gaussian distribution as the input length increases. Furthermore, they introduce an extension to the standard global average pooling layer, replacing it with a global weighted pooling mechanism to enhance performance. The findings bridge the gap between empirical deep learning success and rigorous statistical time series theory.

## Key Contributions

- Proved that outputs of fully convolutional neural networks (FCNs) with global average pooling (GAP) are asymptotically Gaussian for short-range dependent linear process inputs.
- Demonstrated that the Gaussian limit is attained as the time series length approaches infinity.
- Proposed a generalization of the GAP layer using global weighted pooling with learnable, slowly varying coefficients to improve theoretical modeling capabilities.

## Open Questions & Future Work

- [[fcn-theoretical-limits-time-series]]

## Key Concepts

- [[global-weighted-pooling]]: A generalization of the Global Average Pooling (GAP) layer that incorporates global weighted pooling with learnable, slowly varying coefficients to improve theoretical and empirical modeling of time series.

## Archivist Review

I approved Global Weighted Pooling as a distinct and reusable architectural modification to standard pooling layers, and the open question regarding FCN theoretical limits as it addresses a fundamental gap in linking deep learning architectures with statistical time series properties. I rejected the implicit "FCN-Gaussian-Limit" concept as it is a theoretical result/theorem rather than a reusable architecture or method, focusing instead on the provided pooling generalization.

### Approved Concepts
- Global Weighted Pooling: Provides a theoretically grounded alternative to Global Average Pooling that captures more flexible temporal features through learnable, slowly varying coefficients.

### Approved Open Questions
- Theoretical limits of FCNs: Essential for robust time series forecasting where data often exhibits non-stationarity and long-range dependencies, bridging the gap between empirical success and formal statistical guarantees.

## Links

- [Abstract](https://arxiv.org/abs/2603.29612)
- [PDF](https://arxiv.org/pdf/2603.29612)

