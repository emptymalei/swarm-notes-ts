---
# CSL-compatible fields
title: "DySCo: Dynamic Semantic Compression for Effective Long-term Time Series Forecasting"
author:
  - literal: "Xiang Ao"
  - literal: "Yinyu Tan"
  - literal: "Mengru Chen"
issued:
  date-parts:
    - [2026, 4, 1]
url: "https://arxiv.org/abs/2604.01261"

# Custom fields
paper_id: "2604.01261"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "entropy-guided-dynamic-sampling"
  - "hierarchical-frequency-enhanced-decomposition"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-03T05:25:23Z"
created_at: "2026-04-03T05:25:23Z"
---

# DySCo: Dynamic Semantic Compression for Effective Long-term Time Series Forecasting

**Authors**: Xiang Ao, Yinyu Tan, Mengru Chen
**Date**: 2026-04-01
**Paper ID**: [arxiv:2604.01261](https://arxiv.org/abs/2604.01261)

## Summary

DySCo is a framework designed to improve long-term time series forecasting by compressing redundant historical data while retaining critical information. It employs Entropy-Guided Dynamic Sampling (EGDS) to selectively keep high-entropy segments and Hierarchical Frequency-Enhanced Decomposition (HFED) to preserve frequency-specific details. By dynamically fusing these representations, the framework acts as a plug-and-play module that reduces computational overhead and enhances long-term dependency modeling across various base architectures.

## Key Contributions

- Introduced Dynamic Semantic Compression (DySCo), a framework that optimizes long-term forecasting by balancing historical context retention with noise reduction.
- Developed Entropy-Guided Dynamic Sampling (EGDS) to autonomously preserve high-entropy segments, improving model efficiency in processing long lookback windows.
- Proposed Hierarchical Frequency-Enhanced Decomposition (HFED) and Cross-Scale Interaction Mixer (CSIM) to maintain signal fidelity and facilitate multi-scale feature integration in compressed representations.

## Open Questions & Future Work

- [[semantic-adaptive-time-series-compression]]

## Key Concepts

- [[entropy-guided-dynamic-sampling]]: An automated sampling technique that retains high-entropy time series segments to reduce redundancy while preserving critical historical information.
- [[hierarchical-frequency-enhanced-decomposition]]: A decomposition strategy that separates frequency-based components to ensure anomaly preservation during aggressive sparse sampling.

## Archivist Review

The analysis identifies two core mechanisms for long-term time series compression (EGDS and HFED) that represent a shift from static heuristics to dynamic, content-aware sampling. These are approved as they address recurring challenges in long-context forecasting. The open question regarding semantic-adaptive compression is approved for its focus on the fundamental information-theoretic bottleneck of compressing historical temporal context. Other components like the interaction mixer were rejected as common architectural implementations.

### Approved Concepts
- Entropy-Guided Dynamic Sampling: It provides a learnable, mechanism-based approach to history compression in TSF, moving away from static heuristic downsampling.
- Hierarchical Frequency-Enhanced Decomposition: Provides a principled way to decompose time series for selective preservation during aggressive compression tasks.

### Approved Open Questions
- Semantic-Adaptive Time Series Compression: Distinguishing signal from noise in long-context time series is a primary bottleneck for scaling forecasting models to longer input windows.

### Rejected Candidates
- [concept] Cross-Scale Interaction Mixer (`cross-scale-interaction-mixer`) - subcomponent_of_broader_mechanism: This is a specific architectural module for feature fusion, which is standard in deep learning and lacks the broader methodological novelty of the core compression mechanisms.

## Links

- [Abstract](https://arxiv.org/abs/2604.01261)
- [PDF](https://arxiv.org/pdf/2604.01261)

