---
# CSL-compatible fields
title: "FoReco and FoRecoML: A Unified Toolbox for Forecast Reconciliation in R"
author:
  - literal: "Daniele Girolimetto"
  - literal: "Jeroen Rombouts"
  - literal: "Ines Wilms"
  - literal: "Yangzhuoran Fin Yang"
issued:
  date-parts:
    - [2026, 4, 30]
url: "https://arxiv.org/abs/2604.27696"

# Custom fields
paper_id: "2604.27696"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "forecast-reconciliation"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-02T05:08:11Z"
created_at: "2026-05-02T05:08:11Z"
---

# FoReco and FoRecoML: A Unified Toolbox for Forecast Reconciliation in R

**Authors**: Daniele Girolimetto, Jeroen Rombouts, Ines Wilms, Yangzhuoran Fin Yang
**Date**: 2026-04-30
**Paper ID**: [arxiv:2604.27696](https://arxiv.org/abs/2604.27696)

## Summary

The authors present FoReco and FoRecoML, a comprehensive suite of R packages designed for forecast reconciliation in hierarchical and grouped time-series data. The framework unifies classical linear methods with advanced non-linear machine learning approaches, supporting cross-sectional, temporal, and cross-temporal reconciliation tasks. By balancing ease-of-use with advanced customization, these tools provide a standardized ecosystem for researchers and practitioners to improve forecast coherence and accuracy under linear constraints.

## Key Contributions

- Introduces FoReco, an R package for classical and regression-based linear forecast reconciliation across cross-sectional, temporal, and cross-temporal hierarchies.
- Introduces FoRecoML, an R package providing non-linear, machine-learning-based forecast reconciliation methods for various hierarchical structures.
- Provides a unified and accessible software ecosystem to bridge the gap between traditional econometric reconciliation and contemporary machine learning approaches.

## Key Concepts

- [[forecast-reconciliation]]: A process for adjusting incoherent base forecasts of linearly constrained time series to satisfy aggregation constraints.

## Archivist Review

I approved the central concept of 'Forecast Reconciliation' as it is a fundamental research problem in time-series analysis that is well-defined and widely used. I rejected the package-specific candidates as they are essentially software implementations and not reusable methodological research concepts. No datasets or open questions were proposed, which aligns with the request to remain scarce.

### Approved Concepts
- Forecast Reconciliation: The paper explicitly introduces a unified software framework for this core time-series task, consolidating various reconciliation methods.

### Rejected Candidates
- [concept] FoReco and FoRecoML Toolbox (`foreco-forecoml-toolbox`) - paper_local: This is a specific software package/implementation detail rather than a reusable algorithmic concept or mechanism.

## Links

- [Abstract](https://arxiv.org/abs/2604.27696)
- [PDF](https://arxiv.org/pdf/2604.27696)

