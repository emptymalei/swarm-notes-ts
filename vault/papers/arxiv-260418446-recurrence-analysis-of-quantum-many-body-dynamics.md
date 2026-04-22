---
# CSL-compatible fields
title: "Recurrence analysis of quantum many-body dynamics"
author:
  - literal: "Tomasz Szołdra"
  - literal: "Matheus S. Palmero"
  - literal: "Peter Schmelcher"
issued:
  date-parts:
    - [2026, 4, 20]
url: "https://arxiv.org/abs/2604.18446"

# Custom fields
paper_id: "2604.18446"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "physics-informed-ml"
architectures:
  []
datasets:
  []
concept_slugs:
  - "recurrence-quantification-analysis"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-22T05:06:18Z"
created_at: "2026-04-22T05:06:18Z"
---

# Recurrence analysis of quantum many-body dynamics

**Authors**: Tomasz Szołdra, Matheus S. Palmero, Peter Schmelcher
**Date**: 2026-04-20
**Paper ID**: [arxiv:2604.18446](https://arxiv.org/abs/2604.18446)

## Summary

This paper introduces recurrence quantification analysis (RQA) as a diagnostic tool for understanding the out-of-equilibrium dynamics of quantum many-body systems. By applying RQA to correlation time-series data from the transverse-field Ising model, the authors demonstrate that the method successfully captures phase-specific structural changes and identifies critical points. The approach provides a model-agnostic framework for characterizing complex quantum temporal behavior through qualitative plots and quantitative descriptors.

## Key Contributions

- Adapts nonlinear recurrence quantification analysis (RQA) from classical dynamical systems to characterize out-of-equilibrium quantum many-body observables.
- Demonstrates that recurrence quantifiers can detect quantum phase transitions in the 1D transverse-field Ising model without prior model knowledge.
- Shows that recurrence plots provide distinct qualitative signatures for quantum dynamics, transitioning from periodic patterns to multiscale structures at criticality.

## Open Questions & Future Work

- [[rqa-applicability-in-non-ergodic-systems]]

## Key Concepts

- [[recurrence-quantification-analysis]]: A nonlinear time-series analysis framework that uses recurrence plots and corresponding numerical quantifiers to detect structural patterns and transitions in dynamical systems.

## Archivist Review

I have approved 'Recurrence Quantification Analysis' as a foundational diagnostic framework for non-linear time series, and an open question regarding its applicability to non-ergodic systems. These items are highly reusable across physics-informed machine learning and complex temporal dynamics research. I rejected the prompt's specific phrasing of the open question to ensure it adheres to the requested objective, standalone format.

### Approved Concepts
- Recurrence Quantification Analysis (RQA): RQA provides a robust, model-agnostic, and nonlinear diagnostic framework for time-series analysis, which is highly applicable to complex physical systems beyond its original classical context.

### Approved Open Questions
- RQA for non-ergodic systems: Extending RQA to non-ergodic quantum systems provides a unified, unsupervised framework for investigating complex dynamical phase transitions, where established metrics often fail.

## Links

- [Abstract](https://arxiv.org/abs/2604.18446)
- [PDF](https://arxiv.org/pdf/2604.18446)

