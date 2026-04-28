---
# CSL-compatible fields
title: "DecompKAN: Decomposed Patch-KAN for Long-Term Time Series Forecasting"
author:
  - literal: "Naveen Mysore"
issued:
  date-parts:
    - [2026, 4, 27]
url: "https://arxiv.org/abs/2604.23968"

# Custom fields
paper_id: "2604.23968"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "interpretability"
  - "time-series-forecasting"
  - "neural-networks"
  - "long-term-forecasting"
architectures:
  []
datasets:
  - "PPG-DaLiA"
concept_slugs:
  - "decompkan"
dataset_slugs:
  - "ppg-dalia"
skill: "TimeSeriesSkill"
processed_at: "2026-04-28T05:15:53Z"
created_at: "2026-04-28T05:15:53Z"
---

# DecompKAN: Decomposed Patch-KAN for Long-Term Time Series Forecasting

**Authors**: Naveen Mysore
**Date**: 2026-04-27
**Paper ID**: [arxiv:2604.23968](https://arxiv.org/abs/2604.23968)

## Summary

DecompKAN is an attention-free time series forecasting architecture that integrates trend-residual decomposition, channel-wise patching, and learned Kolmogorov-Arnold Network (KAN) edge functions. By replacing standard MLPs with B-spline KAN edges, the model maintains high predictive accuracy while enabling explicit visualization of learned latent nonlinearities. Empirical results demonstrate strong performance across diverse benchmarks, particularly on physiological data and series with smooth temporal dynamics, outperforming several state-of-the-art transformer-based models.

## Key Contributions

- Introduces DecompKAN, an attention-free architecture leveraging trend-residual decomposition and KAN edge functions for interpretable long-term forecasting.
- Achieves best or tied-best MSE on 20 of 36 comparisons across 9 datasets, showing significant improvements on smooth dynamics (e.g., Solar -17%, ECL -10% vs. iTransformer).
- Demonstrates that while architectural components like decomposition and normalization dominate performance, KAN formulation successfully provides inspectable 1D latent transformations.

## Open Questions & Future Work

- [[basis-function-signal-interaction-forecasting]]

## Key Concepts

- [[decompkan]]: A decomposed, attention-free forecasting architecture using B-spline KAN edge functions to enable explicit visualization of learned latent nonlinearities.

## Archivist Review

I approved DecompKAN as it introduces a novel, interpretable architectural pattern that combines KANs with established temporal decomposition techniques. I approved the PPG-DaLiA dataset as a representative benchmark in the physiological forecasting domain. I consolidated the open questions to focus on the specific mechanical interaction between basis functions and signal structures, as this provides a clearer research agenda than a general domain applicability study.

### Approved Concepts
- DecompKAN: It provides a concrete architectural bridge between Kolmogorov-Arnold Networks (KANs) and classical time series decomposition methods, offering a transparent alternative to attention-based models.

### Approved Open Questions
- Basis Function Signal Interaction: Defining the relationship between basis functions and signal dynamics is crucial for advancing the design of functional, interpretable neural architectures for time series.

### Rejected Candidates
- [open_question] Applicability of KANs for Forecasting (`kan-forecasting-domain-applicability`) - duplicate_existing: This is largely captured by the 'Basis Function Signal Interaction' question, which focuses on the mechanics rather than the vague application-area investigation.

## Datasets

- [[ppg-dalia]]

## Links

- [Abstract](https://arxiv.org/abs/2604.23968)
- [PDF](https://arxiv.org/pdf/2604.23968)

