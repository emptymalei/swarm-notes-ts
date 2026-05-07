---
# CSL-compatible fields
title: "A multivariate Birnbaum-Saunders autoregressive moving average model with application to air pollution concentration data"
author:
  - literal: "Helton Saulo"
issued:
  date-parts:
    - [2026, 5, 5]
url: "https://arxiv.org/abs/2605.04211"

# Custom fields
paper_id: "2605.04211"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "forecasting"
  - "multivariate-modeling"
  - "statistical-modeling"
  - "environmental-monitoring"
architectures:
  []
datasets:
  []
concept_slugs:
  - "multivariate-birnbaum-saunders-arma-mbsarma"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-07T05:16:55Z"
created_at: "2026-05-07T05:16:55Z"
---

# A multivariate Birnbaum-Saunders autoregressive moving average model with application to air pollution concentration data

**Authors**: Helton Saulo
**Date**: 2026-05-05
**Paper ID**: [arxiv:2605.04211](https://arxiv.org/abs/2605.04211)

## Summary

This paper introduces the multivariate Birnbaum-Saunders autoregressive moving average (MBSARMA) model, designed to capture the temporal and cross-series dependencies in positive, right-skewed time series data. The model embeds dynamic ARMA components within a multivariate log-linear BS framework, with parameters estimated via the Expectation-Maximisation (EM) algorithm. The effectiveness of the approach is validated through comprehensive Monte Carlo simulations and applied to real-world air pollution concentration data from Santiago, Chile.

## Key Contributions

- Proposed the multivariate Birnbaum-Saunders autoregressive moving average (MBSARMA) model for joint analysis of correlated, positive, and right-skewed time series.
- Developed an EM algorithm for estimating model parameters, ensuring robust performance across varying correlation levels and sample sizes in simulation studies.
- Demonstrated the practical utility of the MBSARMA approach through an application to weekly PM2.5 pollution concentration data across three monitoring stations.

## Open Questions & Future Work

- [[heavy-tailed-seasonal-mbsarma]]

## Key Concepts

- [[multivariate-birnbaum-saunders-arma-mbsarma]]: A multivariate extension of the Birnbaum-Saunders distribution integrated with autoregressive moving average components to model correlated, right-skewed time series.

## Archivist Review

The proposed multivariate Birnbaum-Saunders model provides a structured statistical approach for positive, skewed, and correlated time series, which is a common challenge in environmental and financial applications. I have approved the model concept and the associated research direction regarding heavy-tailed kernels and seasonal extensions. Other candidates were rejected to maintain the archival focus on central methodological innovations.

### Approved Concepts
- Multivariate Birnbaum-Saunders ARMA (MBSARMA): It provides a new statistical framework for modeling the dependence structure of multivariate positive-valued, asymmetric time series using the Birnbaum-Saunders distribution.

### Approved Open Questions
- Heavy-tailed and seasonal extensions: The current Gaussian kernel limits the model's ability to account for extreme values, which are critical in pollution episodes and financial risk management, and seasonal modeling is essential for time-varying data.

## Links

- [Abstract](https://arxiv.org/abs/2605.04211)
- [PDF](https://arxiv.org/pdf/2605.04211)

