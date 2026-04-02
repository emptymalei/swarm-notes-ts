---
# CSL-compatible fields
title: "Deep-Learned Observation Operators for Artificial Intelligence Weather Forecasting Models"
author:
  - literal: "Kelsey Lieberman"
  - literal: "Laura Slivinski"
  - literal: "Matt Bender"
  - literal: "Chris Miller"
  - literal: "Josh DaRosa"
  - literal: "Nick Krall"
  - literal: "Mohammad Ridhwaan Alam"
  - literal: "Nick Silverman"
  - literal: "Sergey Frolov"
issued:
  date-parts:
    - [2026, 3, 31]
url: "https://arxiv.org/abs/2604.00082"

# Custom fields
paper_id: "2604.00082"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "continual-training-weather-emulation"
architectures:
  []
datasets:
  - "UFS replay dataset"
concept_slugs:
  - "deep-learned-observation-operators"
dataset_slugs:
  - "ufs-replay-dataset"
skill: "TimeSeriesSkill"
processed_at: "2026-04-02T05:39:25Z"
created_at: "2026-04-02T05:39:25Z"
---

# Deep-Learned Observation Operators for Artificial Intelligence Weather Forecasting Models

**Authors**: Kelsey Lieberman, Laura Slivinski, Matt Bender, Chris Miller, Josh DaRosa, Nick Krall, Mohammad Ridhwaan Alam, Nick Silverman, Sergey Frolov
**Date**: 2026-03-31
**Paper ID**: [arxiv:2604.00082](https://arxiv.org/abs/2604.00082)

## Summary

This paper explores the integration of deep-learned observation operators into AI-driven weather forecasting models, focusing on the mapping of atmospheric state variables to satellite observation space. By predicting innovations for data assimilation, the proposed deep-learned emulators offer significant speed advantages over traditional physics-based models like the Community Radiative Transfer Model (CRTM). The study demonstrates that these emulators maintain high fidelity even under the reduced vertical resolution constraints common in modern AI weather forecasting architectures. Experiments conducted using the UFS replay dataset and ATMS sensor data confirm the viability of this approach for operational assimilation pipelines.

## Key Contributions

- Demonstrates that deep-learned emulators can effectively predict innovations (differences between simulated and observed radiances) for data assimilation.
- Validates that observation emulators retain performance even when using the reduced vertical levels typical of AI weather forecasting models.
- Provides empirical evidence using the UFS replay dataset and ATMS sensor data for integrating observational models directly into AI-driven forecasting workflows.

## Key Concepts

- [[deep-learned-observation-operators]]: Neural network emulators designed to replace traditional physics-based radiative transfer models by mapping atmospheric state variables directly to observation space.

## Archivist Review

I have approved 'Deep-learned observation operators' as a significant paradigm shift in meteorological data assimilation. The UFS replay dataset is also included as a crucial, domain-specific resource. Other candidates were rejected to maintain the sparsity and quality of the vault, focusing only on the primary methodological advancement.

### Approved Concepts
- Deep-learned observation operators: This represents a fundamental shift from classical, computationally expensive physics-based radiative transfer models to neural emulators, which is critical for enabling data assimilation in AI-based weather models.

### Rejected Candidates
- [dataset] UFS replay dataset (`ufs-replay-dataset`) - low_impact: While mentioned as the evaluation source, this is a standard operational dataset rather than a novel research benchmark central to the field.

## Datasets

- [[ufs-replay-dataset]]

## Links

- [Abstract](https://arxiv.org/abs/2604.00082)
- [PDF](https://arxiv.org/pdf/2604.00082)

