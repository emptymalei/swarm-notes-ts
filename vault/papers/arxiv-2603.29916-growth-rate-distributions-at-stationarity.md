---
# CSL-compatible fields
title: "Growth-rate distributions at stationarity"
author:
  - literal: "Edgardo Brigatti"
issued:
  date-parts:
    - [2026, 3, 31]
url: "https://arxiv.org/abs/2603.29916"

# Custom fields
paper_id: "2603.29916"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "generalized-logistic-growth-null-model"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-02T05:39:52Z"
created_at: "2026-04-02T05:39:52Z"
---

# Growth-rate distributions at stationarity

**Authors**: Edgardo Brigatti
**Date**: 2026-03-31
**Paper ID**: [arxiv:2603.29916](https://arxiv.org/abs/2603.29916)

## Summary

This paper presents a theoretical framework for analyzing growth-rate distributions in stationary time-series, challenging the conventional assumption of normality. The author demonstrates that non-normal, tent-shaped, or heavy-tailed distributions arise naturally from stationary Gamma or heavy-tailed abundance processes. By utilizing the generalized logistic distribution as a null model, the work provides a simplified analytical approach to understanding growth-rate behavior. The methodology is specifically designed to support robust macroecological modeling in scenarios with limited data quality.

## Key Contributions

- Demonstrates that deviations from normality in growth-rate distributions are a natural consequence of stationary underlying abundance distributions rather than pathological behavior.
- Establishes the generalized logistic distribution as a robust null model for stationary growth-rate distributions across tent-shaped and near-normal datasets.
- Provides a pragmatic heuristic workflow for model selection in data-constrained macroecological systems, bridging stationary statistics and stochastic differential equations.

## Open Questions & Future Work

- [[non-markovian-growth-rate-dynamics]]

## Key Concepts

- [[generalized-logistic-growth-null-model]]: A statistical null model for stationary time-series growth-rate distributions that accounts for heavy-tailed or tent-shaped deviations from normality.

## Archivist Review

The paper offers a valuable statistical perspective on non-normal growth-rate distributions, moving away from Gaussian defaults. I approved the generalized logistic null model concept for its utility in stationary time-series diagnostics and the open question regarding non-Markovian extensions, as the latter highlights a clear theoretical bottleneck for the proposed SDE-based selection framework. All other theoretical components were considered part of the broader framework and not requiring independent notes.

### Approved Concepts
- Generalized Logistic Growth Null Model: Provides a robust, non-normal baseline for growth-rate distributions that challenges standard Gaussian assumptions in stationary time-series analysis.

### Approved Open Questions
- Characterizing non-Markovian growth-rate dynamics: Addressing memory effects in growth-rate distributions is critical for moving beyond the Markovian limitations of existing stochastic modeling frameworks.

## Links

- [Abstract](https://arxiv.org/abs/2603.29916)
- [PDF](https://arxiv.org/pdf/2603.29916)

