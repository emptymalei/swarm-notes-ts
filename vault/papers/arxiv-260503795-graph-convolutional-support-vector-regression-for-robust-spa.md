---
# CSL-compatible fields
title: "Graph Convolutional Support Vector Regression for Robust Spatiotemporal Forecasting of Urban Air Pollution"
author:
  - literal: "Nourin Jahan"
  - literal: "Madhurima Panja"
  - literal: "Muhammed Navas T"
  - literal: "Tanujit Chakraborty"
issued:
  date-parts:
    - [2026, 5, 5]
url: "https://arxiv.org/abs/2605.03795"

# Custom fields
paper_id: "2605.03795"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "graph-convolutional-support-vector-regression-gcsvr"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-06T05:11:31Z"
created_at: "2026-05-06T05:11:31Z"
---

# Graph Convolutional Support Vector Regression for Robust Spatiotemporal Forecasting of Urban Air Pollution

**Authors**: Nourin Jahan, Madhurima Panja, Muhammed Navas T, Tanujit Chakraborty
**Date**: 2026-05-05
**Paper ID**: [arxiv:2605.03795](https://arxiv.org/abs/2605.03795)

## Summary

This paper introduces the Graph Convolutional Support Vector Regression (GCSVR) framework to address the complex nonlinear and nonstationary dynamics of urban air pollution forecasting. The method effectively captures inter-station spatial correlations through graph convolution while leveraging SVR to maintain robustness against anomalous observations. Evaluation across Delhi and Mumbai datasets confirms superior predictive accuracy and stability compared to traditional benchmarks, with the addition of conformal prediction providing essential uncertainty quantification for practical applications.

## Key Contributions

- Introduces GCSVR, which integrates graph convolutional networks and support vector regression for robust spatiotemporal modeling of urban air pollution.
- Demonstrates consistent performance improvements across multiple forecasting horizons and seasons compared to established benchmarks in both Delhi and Mumbai.
- Integrates conformal prediction to provide calibrated uncertainty intervals, enhancing the model's reliability for public health decision-making.

## Open Questions & Future Work

- [[integrating-exogenous-covariates-in-spatiotemporal-forecasting]]
- [[dynamic-graph-construction-for-spatiotemporal-modeling]]

## Key Concepts

- [[graph-convolutional-support-vector-regression-gcsvr]]: A hybrid forecasting framework integrating graph convolutional networks with support vector regression to manage nonlinear spatiotemporal dynamics and outlier sensitivity.

## Archivist Review

I approved the GCSVR concept for its hybrid approach to robust spatiotemporal forecasting and two open questions regarding exogenous variable integration and dynamic graph construction. I rejected the individual city datasets as they are too specific and lack the broader reusability required for standalone vault entries. The summary emphasizes methodological contributions to spatiotemporal robustness and the identification of clear structural bottlenecks in urban environmental modeling.

### Approved Concepts
- Graph Convolutional Support Vector Regression (GCSVR): It provides a hybrid architecture combining graph convolutions for spatial dependency and SVR for robust nonlinear temporal modeling, specifically addressing outlier sensitivity in pollution data.

### Approved Open Questions
- Integrating Exogenous Covariates: Accounting for exogenous physical drivers is a known bottleneck for improving accuracy and causal interpretability in spatiotemporal air quality models.
- Dynamic Graph Construction: Fixed proximity graphs often fail to capture the time-varying nature of atmospheric connectivity, representing a significant limitation in urban modeling.

## Links

- [Abstract](https://arxiv.org/abs/2605.03795)
- [PDF](https://arxiv.org/pdf/2605.03795)

