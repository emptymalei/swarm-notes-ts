---
# CSL-compatible fields
title: "Bias-Corrected Adaptive Conformal Inference for Multi-Horizon Time Series Forecasting"
author:
  - literal: "Ankit Lade"
  - literal: "Sai Krishna J."
  - literal: "Indar Kumar"
issued:
  date-parts:
    - [2026, 4, 14]
url: "https://arxiv.org/abs/2604.13253"

# Custom fields
paper_id: "2604.13253"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "bias-corrected-adaptive-conformal-inference-bc-aci"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-16T05:07:11Z"
created_at: "2026-04-16T05:07:11Z"
---

# Bias-Corrected Adaptive Conformal Inference for Multi-Horizon Time Series Forecasting

**Authors**: Ankit Lade, Sai Krishna J., Indar Kumar
**Date**: 2026-04-14
**Paper ID**: [arxiv:2604.13253](https://arxiv.org/abs/2604.13253)

## Summary

Standard Adaptive Conformal Inference (ACI) effectively manages coverage under distribution shift but produces over-conservative, widened intervals when the underlying model exhibits persistent bias. This paper introduces Bias-Corrected ACI (BC-ACI), which augments ACI with an online exponentially weighted moving average bias estimator to re-center prediction intervals. The proposed framework also includes an adaptive dead-zone mechanism that suppresses corrections when bias is indistinguishable from noise. Experimental results confirm that BC-ACI significantly improves interval tightness and scoring metrics under regime shifts while remaining robust on stationary data.

## Key Contributions

- Proposes BC-ACI, which re-centers prediction intervals by using an online EWM estimate of forecast bias, addressing the limitation of standard ACI in non-stationary environments.
- Implements an adaptive dead-zone threshold that prevents performance degradation when bias is within noise levels.
- Demonstrates a 13–17% reduction in Winkler interval scores across synthetic and real-world datasets compared to standard ACI under distribution shifts.

## Open Questions & Future Work

- [[bias-corrected-conformal-inference-robustness-and-testing]]

## Key Concepts

- [[bias-corrected-adaptive-conformal-inference-bc-aci]]: A conformal inference framework that integrates online bias estimation to dynamically re-center prediction intervals under regime shifts.

## Archivist Review

The paper proposes a robust improvement to Adaptive Conformal Inference by incorporating explicit online bias estimation and a dead-zone mechanism. The BC-ACI concept is approved for its generalizability to any time-series forecasting pipeline using conformal methods, and the open question is approved for identifying specific theoretical gaps in non-stationary adaptation and decision-making heuristics within this field.

### Approved Concepts
- Bias-Corrected Adaptive Conformal Inference (BC-ACI): It introduces a novel framework that corrects forecast bias in online settings to improve prediction interval quality beyond symmetric expansion, which is a common limitation in standard conformal inference for time series.

### Approved Open Questions
- Robustness and Testing in BC-ACI: Addressing these limitations is critical for deploying adaptive conformal inference in real-world environments with highly volatile data, as it ensures stability, robust performance, and statistical validity under diverse forms of non-stationarity.

## Links

- [Abstract](https://arxiv.org/abs/2604.13253)
- [PDF](https://arxiv.org/pdf/2604.13253)

