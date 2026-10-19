---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Closely spaced change-point detection with an application to geopolitical shocks in oil and gas markets"
description: "This paper addresses the challenge of detecting change points that occur in rapid succession or near the edges of a sample, where traditional global procedures often fail due to Type-II errors. The authors introduce a new test statistic, I1, and a corresponding two-phase algorithm called DCI that integrates global scanning with adaptive local testing. Theoretical contributions include deriving the limiting null distribution for I1 under various noise conditions and proving its consistency. The method's utility is demonstrated by analyzing the impact of geopolitical shocks on energy markets, introducing new metrics for event sensitivity and attribution."
resource: "https://arxiv.org/abs/2610.23476"
tags:
  - "changepoint-detection"
  - "time-series-analysis"
  - "financial-time-series"
  - "energy-systems"
  - "robustness"
  - "statistical-modeling"
  - "non-stationary"
timestamp: "2026-10-19T04:28:02Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Nachiketas Waychal"
  - literal: "Arnab Kumar Laha"
  - literal: "Ankur Sinha"
issued:
  date-parts:
    - [2026, 10, 16]

# Domain-specific custom fields
paper_id: "2610.23476"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "dci-algorithm-changepoint"
    description: "A two-phase change-point detection algorithm that integrates global scanning with adaptive-width local tests to identify closely spaced structural breaks."
  - name: "i1-test-statistic"
    description: "A statistical test designed for high-resolution change-point detection in sequences with closely spaced breaks or boundary-adjacent shifts."
datasets:
  []
open_questions:
  - name: "event-based-time-series-tokenization-embedding"
    description: "Transforming high-dimensional time series into low-dimensional tokens based on sensitivity and attribution metrics relative to exogenous disruption events provides a portable representation for analysis. This tokenization involves mapping series onto a coordinate space defined by the proportion of events triggering a structural break (event sensitivity) and the proportion of detected breaks attributable to those events (event attribution)."
skill: "TimeSeriesSkill"
processed_at: "2026-10-19T04:28:02Z"
created_at: "2026-10-19T04:28:02Z"
---

# Closely spaced change-point detection with an application to geopolitical shocks in oil and gas markets

**Authors**: Nachiketas Waychal, Arnab Kumar Laha, Ankur Sinha
**Date**: 2026-10-16
**Paper ID**: [arxiv:2610.23476](https://arxiv.org/abs/2610.23476)

## Summary

This paper addresses the challenge of detecting change points that occur in rapid succession or near the edges of a sample, where traditional global procedures often fail due to Type-II errors. The authors introduce a new test statistic, I1, and a corresponding two-phase algorithm called DCI that integrates global scanning with adaptive local testing. Theoretical contributions include deriving the limiting null distribution for I1 under various noise conditions and proving its consistency. The method's utility is demonstrated by analyzing the impact of geopolitical shocks on energy markets, introducing new metrics for event sensitivity and attribution.

## Key Contributions

- Developed the I1 test statistic with proven limiting null distributions for Gaussian and weakly dependent sequences.
- Proposed the DCI algorithm, a two-phase framework that combines global scans with adaptive-width local tests to minimize Type-II errors in dense changepoint scenarios.
- Introduced 'event sensitivity' and 'event attribution' metrics for quantifying the impact of external shocks (e.g., geopolitical events) on financial time series.
- Demonstrated Pareto-optimal performance across true positive rate, localization error, and segmentation covering compared to existing global procedures.

## Limitations

The theoretical consistency is primarily proven under mean-shift alternatives, potentially requiring further extension for variance or trend-based changes.

## Open Questions & Future Work

- [[event-based-time-series-tokenization-embedding]]

## Key Concepts

- [[dci-algorithm-changepoint]]: A two-phase change-point detection algorithm that integrates global scanning with adaptive-width local tests to identify closely spaced structural breaks.
- [[i1-test-statistic]]: A statistical test designed for high-resolution change-point detection in sequences with closely spaced breaks or boundary-adjacent shifts.

## Archivist Review

I approved the DCI algorithm and I1 test statistic as they represent the core methodological and theoretical contributions for the specific 'closely-spaced' changepoint detection problem, which addresses a known failure mode in global procedures. I approved the open question regarding event-based tokenization as it introduces a novel embedding space (ES-EA) that relates exogenous shocks to series dynamics, providing a distinct alternative to standard feature extraction. I rejected the question about extending detection to higher moments as it is a generic research direction common to almost all changepoint detection literature.

### Approved Concepts
- DCI Algorithm: It provides a specific framework for overcoming Type-II errors in dense changepoint scenarios, which is a significant bottleneck for traditional global segmentation methods.
- I1 Test Statistic: It establishes the theoretical foundation for detecting changes in very short intervals (closely spaced) where standard statistics like CUSUM or MOSUM lose statistical power.

### Approved Open Questions
- Event-based Time Series Tokenization: Standard dimensionality reduction techniques often fail to capture the specific influence of exogenous shocks, which is critical for risk assessment and event-driven forecasting in volatile markets.

### Rejected Candidates
- [open_question] Multi-moment Structural Break Detection (`multi-moment-structural-break-detection`) - generic: Extending mean-shift detection to variance or trend shifts is a standard, routine progression in statistical literature and lacks the specific novelty required for a standalone open question note.

## Links

- [Abstract](https://arxiv.org/abs/2610.23476)
- [PDF](https://arxiv.org/pdf/2610.23476)

