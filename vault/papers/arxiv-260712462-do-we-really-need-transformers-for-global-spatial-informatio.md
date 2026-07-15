---
# CSL-compatible fields
title: "Do We Really Need Transformers for Global Spatial Information Extraction in Traffic Forecasting?"
author:
  - literal: "Qihang Zhang"
  - literal: "Siyao Zhang"
  - literal: "Letao Kang"
  - literal: "Wenzhe Liang"
  - literal: "Miao Zhang"
  - literal: "Zhao Zhang"
issued:
  date-parts:
    - [2026, 7, 14]
url: "https://arxiv.org/abs/2607.12462"

# Custom fields
paper_id: "2607.12462"
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
processed_at: "2026-07-15T19:40:00Z"
created_at: "2026-07-15T19:40:00Z"
---

# Do We Really Need Transformers for Global Spatial Information Extraction in Traffic Forecasting?

**Authors**: Qihang Zhang, Siyao Zhang, Letao Kang, Wenzhe Liang, Miao Zhang, Zhao Zhang
**Date**: 2026-07-14
**Paper ID**: [arxiv:2607.12462](https://arxiv.org/abs/2607.12462)

## Summary

This paper investigates whether high-degree-of-freedom spatial attention is necessary for modeling global dependencies in traffic forecasting networks. By replacing spatial attention modules with a simple uniform aggregation operator within a controlled ablation framework, the authors demonstrate that simple uniform mixing often matches the performance of complex attention mechanisms. Analysis of the residual components in spatial attention suggests that current architectures may be over-parameterized, as much of the predictive gain is derived from a uniform global background rather than node-specific residuals.

## Key Contributions

- Introduces a controlled ablation framework to isolate and evaluate the necessity of attention-based spatial mixing mechanisms in traffic forecasting.
- Demonstrates that simple uniform full-range mixing achieves competitive performance to standard spatial attention while reducing spatial mixing complexity from O(N²) to O(N).
- Performs a mechanism analysis showing that spatial attention gains are marginal over a uniform global background, highlighting the need for performance-justified complexity in traffic modeling.

## Links

- [Abstract](https://arxiv.org/abs/2607.12462)
- [PDF](https://arxiv.org/pdf/2607.12462)

