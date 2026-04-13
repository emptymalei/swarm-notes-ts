---
# CSL-compatible fields
title: "Hierarchical Flow Decomposition for Turning Movement Prediction at Signalized Intersections"
author:
  - literal: "Md Atiqur Rahman Mallick"
  - literal: "Kamrul Hasan"
  - literal: "Pulock Das"
  - literal: "Liang Hong"
  - literal: "S M Shazzad Rassel"
issued:
  date-parts:
    - [2026, 4, 10]
url: "https://arxiv.org/abs/2604.09336"

# Custom fields
paper_id: "2604.09336"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "spatiotemporal-forecasting"
  - "traffic-prediction"
  - "physics-informed-ml"
architectures:
  - "transformer"
  - "gru"
  - "dcrnn"
datasets:
  []
concept_slugs:
  - "hierarchical-flow-decomposition"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-13T05:09:17Z"
created_at: "2026-04-13T05:09:17Z"
---

# Hierarchical Flow Decomposition for Turning Movement Prediction at Signalized Intersections

**Authors**: Md Atiqur Rahman Mallick, Kamrul Hasan, Pulock Das, Liang Hong, S M Shazzad Rassel
**Date**: 2026-04-10
**Paper ID**: [arxiv:2604.09336](https://arxiv.org/abs/2604.09336)

## Summary

The paper introduces HFD-TM, a hierarchical deep learning framework designed to predict vehicle turning movements at signalized intersections by exploiting the structural relationship between aggregate corridor flows and specific turning streams. By forecasting the more stable corridor through-movements first, the model reduces prediction volatility and maintains structural consistency through a physics-informed flow conservation loss. Evaluations using six months of LiDAR data show that HFD-TM outperforms standard Transformer and GRU architectures in accuracy while significantly reducing training overhead.

## Key Contributions

- Introduces HFD-TM, a hierarchical deep learning framework that reduces MAE by 5.7% over Transformers and 27.0% over GRUs in turning movement prediction.
- Demonstrates that predicting corridor through-movements as a precursor to turning streams significantly improves model performance and stability.
- Achieves a 12.8x reduction in training time compared to DCRNN, enhancing suitability for real-time traffic signal control.

## Open Questions & Future Work

- [[generalizability-hierarchical-flow-decomposition]]
- [[multi-step-traffic-prediction-horizon]]

## Key Concepts

- [[hierarchical-flow-decomposition]]: A hierarchical forecasting strategy that predicts aggregate corridor flow before disaggregating into specific turning movements to reduce volatility.

## Archivist Review

The paper introduces a hierarchical strategy that decomposes aggregate flow to improve granular movement prediction, which is a reusable forecasting paradigm. The approved open questions target key bottlenecks in scaling this approach to diverse environments and longer prediction horizons, which are essential for practical deployment in intelligent transportation systems. Standard evaluation datasets were excluded as they did not meet the requirement for standalone, named, and widely used datasets.

### Approved Concepts
- Hierarchical Flow Decomposition: Novel decomposition strategy that leverages the empirical traffic structural relationship between corridor-level and turn-level flows.

### Approved Open Questions
- Generalizability of Hierarchical Forecasting: The lack of validated generalizability across diverse topologies remains a significant barrier to the widespread adoption of specialized traffic forecasting models.
- Multi-step Traffic Prediction Horizons: Multi-step prediction is a critical requirement for proactive adaptive signal control, yet many hierarchical models are optimized for short-term, single-interval predictions.

## Links

- [Abstract](https://arxiv.org/abs/2604.09336)
- [PDF](https://arxiv.org/pdf/2604.09336)

