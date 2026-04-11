---
# CSL-compatible fields
title: "Zero-shot Multivariate Time Series Forecasting Using Tabular Prior Fitted Networks"
author:
  - literal: "Mayuka Jayawardhana"
  - literal: "Nihal Sharma"
  - literal: "Kazem Meidani"
  - literal: "Bayan Bruss"
  - literal: "Tom Goldstein"
  - literal: "Doron Bergman"
issued:
  date-parts:
    - [2026, 4, 9]
url: "https://arxiv.org/abs/2604.08400"

# Custom fields
paper_id: "2604.08400"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-11T04:43:58Z"
created_at: "2026-04-11T04:43:58Z"
---

# Zero-shot Multivariate Time Series Forecasting Using Tabular Prior Fitted Networks

**Authors**: Mayuka Jayawardhana, Nihal Sharma, Kazem Meidani, Bayan Bruss, Tom Goldstein, Doron Bergman
**Date**: 2026-04-09
**Paper ID**: [arxiv:2604.08400](https://arxiv.org/abs/2604.08400)

## Summary

This paper presents a novel framework for zero-shot multivariate time series forecasting that leverages the reasoning capabilities of tabular foundation models, specifically TabPFN. By recasting multivariate time series data into a sequence of scalar regression tasks, the method avoids the limitations of independent univariate forecasting approaches that fail to model cross-channel dependencies. The authors validate their approach using the TabPFN-TS backbone, demonstrating improved performance in zero-shot multivariate settings compared to established tabular baselines.

## Key Contributions

- Introduces a framework that recasts multivariate time series forecasting as a series of scalar regression problems to leverage tabular foundation models zero-shot.
- Demonstrates that the proposed method captures inter-channel interactions that are typically lost when treating multivariate problems as independent univariate forecasting tasks.
- Evaluates performance using the TabPFN-TS backbone against existing tabular and state-of-the-art forecasting baselines.

## Open Questions & Future Work

- [[ci-vs-cd-forecasting-superiority]]
- [[probabilistic-forecast-calibration-improvement]]

## Archivist Review

The paper explores adapting TabPFN to multivariate time series by recasting the problem as scalar regression. I have approved two open questions that capture the fundamental trade-offs and calibration challenges identified in the paper's discussion, while rejecting the concept candidates as they represent application-specific framing rather than novel, reusable theoretical mechanisms.

### Approved Open Questions
- CI vs CD Forecasting Superiority: This is a fundamental trade-off in multivariate time series forecasting that impacts model selection and performance; understanding the underlying factors would guide future architecture design.
- Probabilistic Forecast Calibration Improvement: Uncertainty quantification is vital for real-world deployment of time series models, and existing tabular PFN adaptations currently struggle to produce well-calibrated probabilistic outputs for multivariate data.

### Rejected Candidates
- [open_question] Probabilistic Forecast Calibration Improvement (`probabilistic-forecast-calibration`) - other: Renamed for consistency and clarity.

## Links

- [Abstract](https://arxiv.org/abs/2604.08400)
- [PDF](https://arxiv.org/pdf/2604.08400)

