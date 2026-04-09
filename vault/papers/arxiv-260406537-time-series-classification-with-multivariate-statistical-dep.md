---
# CSL-compatible fields
title: "Time-Series Classification with Multivariate Statistical Dependence Features"
author:
  - literal: "Yao Sun"
  - literal: "Bo Hu"
  - literal: "Jose Principe"
issued:
  date-parts:
    - [2026, 4, 8]
url: "https://arxiv.org/abs/2604.06537"

# Custom fields
paper_id: "2604.06537"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series-classification"
  - "statistical-modeling"
  - "non-stationary-signals"
  - "feature-extraction"
  - "dimensionality-reduction"
architectures:
  []
datasets:
  []
concept_slugs:
  - "cross-density-ratio-cdr"
  - "functional-maximal-correlation-algorithm-fmca"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-09T04:55:46Z"
created_at: "2026-04-09T04:55:46Z"
---

# Time-Series Classification with Multivariate Statistical Dependence Features

**Authors**: Yao Sun, Bo Hu, Jose Principe
**Date**: 2026-04-08
**Paper ID**: [arxiv:2604.06537](https://arxiv.org/abs/2604.06537)

## Summary

This paper addresses non-stationary time-series analysis by replacing traditional correlation statistics with the Cross Density Ratio (CDR), a robust measure of statistical dependence. By decomposing the CDR eigenspectrum via the Functional Maximal Correlation Algorithm (FMCA), the authors create an informative feature projection space. This framework enables high-accuracy classification using minimal computational resources, as demonstrated on the TI-46 speech corpus against HMMs and spiking neural networks.

## Key Contributions

- Introduces the Cross Density Ratio (CDR) as a robust, order-independent alternative to windowed correlation for non-stationary time-series analysis.
- Develops the Functional Maximal Correlation Algorithm (FMCA) to project time-series into an eigenspace derived from the CDR.
- Achieves superior classification accuracy on the TI-46 speech corpus compared to HMMs and spiking neural networks with a footprint under 5 MB.

## Open Questions & Future Work

- [[complex-valued-fmca-extension]]

## Key Concepts

- [[cross-density-ratio-cdr]]: A statistical dependence measure derived from the normalized joint density of input and target signals that is robust to regime changes and sample order.
- [[functional-maximal-correlation-algorithm-fmca]]: An algorithm that constructs a projection space for time-series data by decomposing the eigenspectrum of the cross density ratio.

## Archivist Review

The paper introduces a robust statistical framework for non-stationary time-series analysis that relies on dependence measures rather than correlation. I have approved the CDR and FMCA as they provide a foundational, reusable approach to feature extraction that is explicitly designed to handle regime changes, which is a common challenge in time-series modeling. The open question regarding complex-valued extension is approved as it addresses a fundamental limitation in the current scope of the algorithm for broad signal processing applications.

### Approved Concepts
- Cross Density Ratio (CDR): Provides a non-parametric, order-independent alternative to traditional correlation-based feature extraction for non-stationary signals.
- Functional Maximal Correlation Algorithm (FMCA): Core framework for performing dimensionality reduction on non-stationary time series by projecting onto the eigenspace of dependence statistics.

### Approved Open Questions
- Complex-Valued FMCA Extension: Extending to the complex domain is critical for many signal processing tasks (e.g., radar, communication signals) where phase information is essential and currently neglected by purely real-valued methods.

## Links

- [Abstract](https://arxiv.org/abs/2604.06537)
- [PDF](https://arxiv.org/pdf/2604.06537)

