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
  - "time-series"
  - "forecasting"
  - "tabular-data"
  - "foundation-models"
  - "multivariate-forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-10T15:27:01Z"
created_at: "2026-04-10T15:27:01Z"
---

# Zero-shot Multivariate Time Series Forecasting Using Tabular Prior Fitted Networks

**Authors**: Mayuka Jayawardhana, Nihal Sharma, Kazem Meidani, Bayan Bruss, Tom Goldstein, Doron Bergman
**Date**: 2026-04-09
**Paper ID**: [arxiv:2604.08400](https://arxiv.org/abs/2604.08400)

## Summary

This paper introduces a framework to enable zero-shot multivariate time series forecasting using tabular foundation models like TabPFN. By recasting multivariate sequences into structured scalar regression problems, the approach preserves inter-channel dependencies often neglected by univariate-based treatments. The authors demonstrate that their method, implemented with a TabPFN-TS backbone, effectively leverages tabular model capabilities for improved predictive performance on complex time series.

## Key Contributions

- Introduces a framework that recasts multivariate time series forecasting as a sequence of scalar regression problems to leverage tabular foundation models zero-shot.
- Enables inter-channel interaction modeling for tabular foundation models, surpassing previous univariate-only multivariate approaches.
- Demonstrates the efficacy of the TabPFN-TS backbone on multivariate forecasting benchmarks compared to existing state-of-the-art tabular methods.

## Open Questions & Future Work

- [[ci-vs-cd-forecasting-superiority]]
- [[probabilistic-forecasting-calibration-drivers]]

## Archivist Review

I have approved the two open questions as they represent significant, unresolved methodological bottlenecks in time series forecasting that transcend this specific paper's contribution. The proposed concept 'TabPFN-TS' was rejected as it is a specific implementation backbone rather than a reusable conceptual framework, adhering to the policy of prioritizing overarching mechanisms over local implementation details. No datasets were approved as none were presented as core scientific contributions.

### Approved Open Questions
- CI vs CD Forecasting Superiority: This is a fundamental methodological question in time series forecasting that informs whether models should explicitly account for inter-variable correlations or rely on simpler, more robust univariate assumptions.
- Probabilistic Forecasting Calibration Drivers: Reliable uncertainty quantification is critical for decision-making in real-world forecasting applications, making the gap in probabilistic accuracy a key barrier to practical deployment.

### Rejected Candidates
- [concept] TabPFN-TS (`tabpfn-ts`) - paper_local: This is a specific model architecture/backbone implementation rather than a generalizable conceptual framework.

## Links

- [Abstract](https://arxiv.org/abs/2604.08400)
- [PDF](https://arxiv.org/pdf/2604.08400)

