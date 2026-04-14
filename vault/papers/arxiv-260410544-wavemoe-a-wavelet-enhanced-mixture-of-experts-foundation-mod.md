---
# CSL-compatible fields
title: "WaveMoE: A Wavelet-Enhanced Mixture-of-Experts Foundation Model for Time Series Forecasting"
author:
  - literal: "Shunyu Wu"
  - literal: "Jiawei Huang"
  - literal: "Weibin Feng"
  - literal: "Boxin Li"
  - literal: "Xiao Zhang"
  - literal: "Erli Meng"
  - literal: "Dan Li"
  - literal: "Jian Lou"
  - literal: "See-Kiong Ng"
issued:
  date-parts:
    - [2026, 4, 12]
url: "https://arxiv.org/abs/2604.10544"

# Custom fields
paper_id: "2604.10544"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "foundation-models"
  - "mixture-of-experts"
  - "wavelet-transform"
  - "time-series-forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  - "wavelet-enhanced-mixture-of-experts"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-14T05:05:33Z"
created_at: "2026-04-14T05:05:33Z"
---

# WaveMoE: A Wavelet-Enhanced Mixture-of-Experts Foundation Model for Time Series Forecasting

**Authors**: Shunyu Wu, Jiawei Huang, Weibin Feng, Boxin Li, Xiao Zhang, Erli Meng, Dan Li, Jian Lou, See-Kiong Ng
**Date**: 2026-04-12
**Paper ID**: [arxiv:2604.10544](https://arxiv.org/abs/2604.10544)

## Summary

WaveMoE is a foundation model for time series forecasting that bridges time-domain and wavelet-domain representations to capture complex temporal dynamics like periodicity. The model uses a dual-path architecture to process synchronized time and wavelet tokens, which are then managed by a shared Mixture-of-Experts (MoE) routing mechanism. This design allows the model to efficiently scale capacity while maintaining consistent expert specialization across diverse datasets. Experiments across 16 benchmarks demonstrate that integrating wavelet-domain corpora significantly enhances forecasting performance.

## Key Contributions

- Introduces WaveMoE, a foundation model integrating explicit wavelet-domain frequency representations with time-domain tokens.
- Implements a dual-path architecture where time and wavelet tokens are synchronized along a unified temporal axis.
- Demonstrates consistent expert specialization and efficient scaling through a shared expert routing mechanism across 16 benchmark datasets.

## Open Questions & Future Work

- [[frequency-domain-scaling-tsfms]]
- [[adaptive-cross-domain-fusion-moe]]

## Key Concepts

- [[wavelet-enhanced-mixture-of-experts]]: A dual-path architecture that integrates synchronized time-domain and wavelet-domain tokens through a shared expert-routing mechanism.

## Archivist Review

I approved the core architectural paradigm (Wavelet-Enhanced MoE) as a reusable concept for integrating multi-domain signals in TSFMs. I also distilled the proposed open questions into two fundamental research axes: the scaling behavior of non-time-domain corpora and the mechanism for cross-domain expert routing. Generic model names and duplicative questions were rejected to maintain vault conciseness.

### Approved Concepts
- Wavelet-Enhanced Mixture-of-Experts (WaveMoE): It establishes a new architectural pattern for TSFMs by dual-path processing of time-domain and frequency-domain (wavelet) tokens within an MoE framework.

### Approved Open Questions
- Scaling Frequency-Domain TSFMs: Determining the optimal data domain for scaling is critical for the development of foundation models capable of capturing both long-range trends and localized oscillatory dynamics.
- Adaptive Cross-Domain MoE Fusion: Improving the fusion of heterogeneous representations is essential for handling multi-scale temporal data without information misalignment.

### Rejected Candidates
- [concept] WaveMoE (`wavemoe`) - duplicate_existing: The term WaveMoE is the specific model name; the underlying architectural concept of wavelet-enhanced MoE is already captured by the approved concept.
- [open_question] Frequency-domain scaling for TSFMs (`wavelet-domain-scaling-tsfm`) - duplicate_existing: This is effectively synonymous with the approved frequency-domain scaling question, which is phrased more broadly for the vault.
- [open_question] Adaptive time-frequency fusion strategies (`adaptive-time-frequency-fusion`) - duplicate_existing: This is effectively synonymous with the approved cross-domain fusion question, which is phrased more broadly for the vault.

## Links

- [Abstract](https://arxiv.org/abs/2604.10544)
- [PDF](https://arxiv.org/pdf/2604.10544)

