---
# CSL-compatible fields
title: "Structural Gating and Effect-aligned Lag-resolved Temporal Causal Discovery Framework with Application to Heat-Pollution Extremes"
author:
  - literal: "Rui Chen"
  - literal: "Jinsong Wu"
issued:
  date-parts:
    - [2026, 4, 11]
url: "https://arxiv.org/abs/2604.10371"

# Custom fields
paper_id: "2604.10371"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "sged-causal-discovery"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-14T05:06:35Z"
created_at: "2026-04-14T05:06:35Z"
---

# Structural Gating and Effect-aligned Lag-resolved Temporal Causal Discovery Framework with Application to Heat-Pollution Extremes

**Authors**: Rui Chen, Jinsong Wu
**Date**: 2026-04-11
**Paper ID**: [arxiv:2604.10371](https://arxiv.org/abs/2604.10371)

## Summary

This paper introduces Structural Gating and Effect-aligned Discovery for Temporal Causal Discovery (SGED-TCD), a framework designed to identify lag-resolved causal relationships in complex multivariate time series. The methodology integrates explicit structural gating with perturbation-effect alignment to enhance the robustness and interpretability of inferred causal graphs. The authors validate the framework by analyzing the causal drivers of compound heatwave and air-pollution extremes in China, uncovering distinct regional and seasonal climate-environment dynamics. SGED-TCD provides a generalized approach for temporal causal discovery applicable to diverse complex systems.

## Key Contributions

- Proposes SGED-TCD, a framework for lag-resolved causal discovery in multivariate time series using structural gating and perturbation-effect alignment.
- Demonstrates the framework's capability to reconstruct physically interpretable causal networks for compound heatwave-air-pollution extremes.
- Identifies key regional and seasonal heterogeneity in climate-pollution causal drivers in China, linking warm-season extremes to low-latitude ocean variability and cold-season extremes to high-latitude circulation.

## Open Questions & Future Work

- [[modeling-nonstationary-temporal-causality]]

## Key Concepts

- [[sged-causal-discovery]]: A causal discovery framework that integrates structural gating mechanisms with perturbation-effect alignment to recover interpretable, lag-resolved causal pathways in complex time series.

## Archivist Review

The review focused on extracting the core methodological innovation, 'Structural Gating and Effect-aligned Discovery,' as a general-purpose causal discovery technique, while rejecting the framework's specific acronym to avoid paper-local baggage. The open question regarding nonstationary causality was approved for its high relevance to time-series forecasting in non-equilibrium complex systems.

### Approved Concepts
- Structural Gating and Effect-aligned Discovery (SGED): Provides a novel way to combine structural constraints with alignment-based causal discovery in high-dimensional, time-lagged multivariate systems.

### Approved Open Questions
- Modeling Nonstationary Temporal Causality: Stationary assumptions in causal inference lead to structural bias in systems subject to long-term change, making this a fundamental bottleneck for climate and socioeconomic modeling.

### Rejected Candidates
- [concept] SGED-TCD (`sged-tcd`) - duplicate_existing: This is the specific name of the proposed framework, which is better captured by the conceptual component SGED; using the framework acronym as a standalone note is redundant.

## Links

- [Abstract](https://arxiv.org/abs/2604.10371)
- [PDF](https://arxiv.org/pdf/2604.10371)

