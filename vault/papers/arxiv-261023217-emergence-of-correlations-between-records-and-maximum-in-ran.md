---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Emergence of Correlations Between Records and Maximum in Random Time Series"
description: "This paper investigates the statistical relationship between the number of records and the maximum value in a time series of $n$ observations. The authors prove that these two variables are perfectly uncorrelated for any continuous IID distribution, but show that this independence is broken by the introduction of a discrete 'zero' component (zero-inflation). They provide exact analytical solutions for the resulting covariance, identify a critical shape transition in its temporal evolution, and validate these theoretical findings using real-world precipitation data, bridging the gap between stochastic process theory and extreme weather analysis."
resource: "https://arxiv.org/abs/2610.23217"
tags:
  - "time-series"
  - "extreme-value-analysis"
  - "stochastic-processes"
  - "statistical-modeling"
  - "precipitation-forecasting"
  - "weather-prediction"
  - "data skew"
timestamp: "2026-10-19T04:31:50Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Satya N. Majumdar"
  - literal: "Sanjib Sabhapandit"
  - literal: "Gregory Schehr"
issued:
  date-parts:
    - [2026, 10, 16]

# Domain-specific custom fields
paper_id: "2610.23217"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "record-maximum-covariance"
    description: "A statistical metric quantifying the relationship between the frequency of record-breaking events and the overall global maximum in a stochastic process."
  - name: "zero-inflated-record-statistics"
    description: "A mathematical framework for analyzing record-breaking processes and extrema in time series characterized by a discrete probability mass at zero."
datasets:
  []
open_questions:
  - name: "records-maximum-covariance-correlated-series"
    description: "Existing analytical derivations for the covariance between records and maxima primarily cover IID sequences with zero-inflation (e.g., dry-day models). However, an exact mathematical characterization is missing for series that exhibit both temporal correlations (such as AR(1) or Markovian processes) and a non-zero probability of null observations. Future research must determine how these dual factors interact to influence the joint distribution of records and peaks, particularly regarding non-monotonic covariance behavior over time."
skill: "TimeSeriesSkill"
processed_at: "2026-10-19T04:31:50Z"
created_at: "2026-10-19T04:31:50Z"
---

# Emergence of Correlations Between Records and Maximum in Random Time Series

**Authors**: Satya N. Majumdar, Sanjib Sabhapandit, Gregory Schehr
**Date**: 2026-10-16
**Paper ID**: [arxiv:2610.23217](https://arxiv.org/abs/2610.23217)

## Summary

This paper investigates the statistical relationship between the number of records and the maximum value in a time series of $n$ observations. The authors prove that these two variables are perfectly uncorrelated for any continuous IID distribution, but show that this independence is broken by the introduction of a discrete 'zero' component (zero-inflation). They provide exact analytical solutions for the resulting covariance, identify a critical shape transition in its temporal evolution, and validate these theoretical findings using real-world precipitation data, bridging the gap between stochastic process theory and extreme weather analysis.

## Key Contributions

- Analytically proved that for any continuous IID distribution, the maximum value $M$ and the number of records $K$ are uncorrelated for any sample size $n$.
- Derived an exact expression for the covariance $C_q(n)$ between $M$ and $K$ in the presence of a delta-component at zero, representing zero-inflated data like rainfall.
- Identified a critical probability threshold $q_c$ that triggers a shape transition in the covariance function, moving from monotonic to non-monotonic behavior.
- Demonstrated that for large $n$, the covariance decays following a power law where the exponent is determined by the tail behavior of the underlying distribution.
- Validated theoretical predictions using historical precipitation records from German weather stations, showing high alignment with empirical covariance patterns.

## Limitations

The current analysis assumes IID behavior (aside from the zero-inflation) and may not directly account for strong temporal correlations or seasonality common in geophysical series.

## Open Questions & Future Work

- [[records-maximum-covariance-correlated-series]]

## Key Concepts

- [[record-maximum-covariance]]: A statistical metric quantifying the relationship between the frequency of record-breaking events and the overall global maximum in a stochastic process.
- [[zero-inflated-record-statistics]]: A mathematical framework for analyzing record-breaking processes and extrema in time series characterized by a discrete probability mass at zero.

## Archivist Review

The approved items focus on the fundamental statistical relationship between records and maxima, particularly how this relationship is modified by zero-inflation. This represents a significant refinement of extreme value theory applicable to sparse time series. The open question identifies the critical next step in modeling: combining these structural distribution effects with temporal correlations (non-IID data). Rejected items were either too generic (German weather data) or were paper-specific mathematical results rather than generalizable concepts.

### Approved Concepts
- Record-Maximum Covariance: Introduces a specific analytical probe to investigate the relationship between the cumulative count of 'new peaks' (records) and the absolute maximum, revealing a fundamental independence in continuous IID processes that is broken by specific data characteristics.
- Zero-Inflated Record Statistics: Provides a theoretical framework for adapting extreme value theory to datasets with a high probability of null observations, which commonly invalidate standard asymptotic results for record statistics.

### Approved Open Questions
- Covariance of Extrema in Correlated Series: Most real-world physical and financial systems exhibit both persistence (correlations) and intermittent activity (zeros), making IID-based extreme value models insufficient for risk assessment.

### Rejected Candidates
- [dataset] German Precipitation Data (`german-precipitation-data`) - generic: The paper uses data from various stations across Germany rather than a named, curated, and versioned dataset common for ML benchmarking.
- [concept] Shape Transition in Covariance (`shape-transition-in-covariance`) - paper_local: This is a specific mathematical observation resulting from the paper's specific derivations rather than a reusable method or framework.

## Links

- [Abstract](https://arxiv.org/abs/2610.23217)
- [PDF](https://arxiv.org/pdf/2610.23217)

