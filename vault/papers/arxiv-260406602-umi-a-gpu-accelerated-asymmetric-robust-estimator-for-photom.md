---
# CSL-compatible fields
title: "UMI: A GPU-Accelerated Asymmetric Robust Estimator for Photometric Detrending in Exoplanet Transit Searches"
author:
  - literal: "Omar Khan"
issued:
  date-parts:
    - [2026, 4, 8]
url: "https://arxiv.org/abs/2604.06602"

# Custom fields
paper_id: "2604.06602"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "time-series"
architectures:
  []
datasets:
  []
concept_slugs:
  - "asymmetric-robust-m-estimation"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-09T04:55:36Z"
created_at: "2026-04-09T04:55:36Z"
---

# UMI: A GPU-Accelerated Asymmetric Robust Estimator for Photometric Detrending in Exoplanet Transit Searches

**Authors**: Omar Khan
**Date**: 2026-04-08
**Paper ID**: [arxiv:2604.06602](https://arxiv.org/abs/2604.06602)

## Summary

UMI (Unified Median Iterative) is a GPU-accelerated robust location estimator designed for photometric detrending in exoplanet transit surveys. By implementing an asymmetric weight function that penalizes downward deviations and an upper-RMS scale estimator, UMI prevents transit signal contamination during the detrending process. The method provides significant computational speedups through a fused HIP/CUDA kernel and demonstrates substantial improvements in transit depth recovery error compared to conventional robust estimators like the biweight.

## Key Contributions

- Introduced UMI, an asymmetric M-estimator for photometric detrending that preserves transit dip signals through selective weighting.
- Achieved 69x faster detrending and 37x overall pipeline throughput improvement via a fused GPU kernel implementation.
- Demonstrated a 23% to 71% reduction in transit depth recovery error compared to biweight estimators on TESS and Kepler datasets.

## Open Questions & Future Work

- [[asymmetric-estimator-bias-impact]]

## Key Concepts

- [[asymmetric-robust-m-estimation]]: A robust M-estimation technique that employs asymmetric weighting to protect specific directional outliers (e.g., transit events) from being suppressed during time-series detrending.

## Archivist Review

I approved the core methodology of Asymmetric Robust M-estimation as it provides a valuable template for signal-preserving preprocessing in time-series analysis. The open question regarding false-positive risks was approved because it addresses a fundamental trade-off between signal-preservation bias and the reliability of downstream detection pipelines. I rejected the specific tool name (UMI) in favor of the mechanism, and I rejected the hyperparameter tuning question as being too generic.

### Approved Concepts
- Asymmetric Robust M-estimation: The use of asymmetric weight functions to preserve specific signal structures (like dips or spikes) in robust estimation is a powerful, reusable strategy for time-series cleaning.

### Approved Open Questions
- Asymmetric Estimator False-Positive Risks: Quantifying the unintended bias-to-false-positive trade-off is critical for robust automated pipeline design.

### Rejected Candidates
- [concept] Unified Median Iterative (UMI) (`unified-median-iterative-umi`) - subcomponent_of_broader_mechanism: UMI is the specific implementation name for the broader, more reusable strategy of asymmetric M-estimation.
- [open_question] Adaptive Asymmetry Parameter Selection (`adaptive-asymmetry-selection`) - generic: Adaptive parameter tuning is a generic optimization problem and lacks sufficient conceptual novelty to justify a permanent tracker.

## Links

- [Abstract](https://arxiv.org/abs/2604.06602)
- [PDF](https://arxiv.org/pdf/2604.06602)

