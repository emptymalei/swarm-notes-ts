---
# CSL-compatible fields
title: "Time Series Gaussian Chain Graph Models"
author:
  - literal: "Qin Fang"
  - literal: "Xinghao Qiao"
  - literal: "Zihan Wang"
issued:
  date-parts:
    - [2026, 4, 8]
url: "https://arxiv.org/abs/2604.07018"

# Custom fields
paper_id: "2604.07018"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "time-series-gaussian-chain-graph-models"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-09T04:54:50Z"
created_at: "2026-04-09T04:54:50Z"
---

# Time Series Gaussian Chain Graph Models

**Authors**: Qin Fang, Xinghao Qiao, Zihan Wang
**Date**: 2026-04-08
**Paper ID**: [arxiv:2604.07018](https://arxiv.org/abs/2604.07018)

## Summary

This paper introduces time series Gaussian chain graph models designed to capture complex dependence in multivariate time series exhibiting blockwise structures. The framework accounts for both contemporaneous and lagged causal relations via directed edges across blocks, while utilizing undirected edges for within-block dependencies. By analyzing the inverse spectral density matrix in the frequency domain, the authors derive a structural decomposition that enables robust estimation through a three-stage regularized Whittle likelihood approach. The method demonstrates consistency in theoretical recovery and superior empirical results in macroeconomic applications.

## Key Contributions

- Introduces time series Gaussian chain graph models to characterize blockwise dependence structures in multivariate time series.
- Establishes structure identifiability by showing that the model induces a cross-frequency shared group sparse plus group low-rank decomposition of inverse spectral density matrices.
- Develops a three-stage learning procedure using regularized Whittle likelihood with group lasso and tensor-unfolding nuclear norm penalties for joint estimation of directed and undirected edges.

## Open Questions & Future Work

- [[time-series-chain-graph-non-linear-extension]]

## Key Concepts

- [[time-series-gaussian-chain-graph-models]]: A framework for multivariate time series modeling that uses directed edges for cross-block causal relations and undirected edges for within-block conditional dependencies.

## Archivist Review

I approved the core modeling framework as a standalone concept due to its novel combination of directed and undirected graphical structures for multivariate time series. The open question was refined to specifically address the limitations of the current stationarity/linearity assumptions, which is a critical research direction for this class of models. I rejected the original candidate name to improve consistency with the existing naming schema.

### Approved Concepts
- Time Series Gaussian Chain Graph Models: It provides a novel framework for capturing blockwise dependence structures in multivariate time series using a combination of directed and undirected graphs, which is a robust way to model complex causal relations in high-dimensional settings.

### Approved Open Questions
- Non-linear Chain Graph Extensions: The model's current reliance on stationary, linear-innovation assumptions limits its applicability to real-world financial data, where volatility clustering and non-linear dynamics are pervasive.

### Rejected Candidates
- [open_question] Extensions of Time Series Chain Graphs (`limitations-time-series-chain-graphs`) - other: Renamed for better alignment with the vault's naming conventions (using specific technical descriptors over generic 'extensions').

## Links

- [Abstract](https://arxiv.org/abs/2604.07018)
- [PDF](https://arxiv.org/pdf/2604.07018)

