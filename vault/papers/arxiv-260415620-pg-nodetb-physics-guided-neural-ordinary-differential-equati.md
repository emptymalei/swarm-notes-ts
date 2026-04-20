---
# CSL-compatible fields
title: "$PG-NODE^{TB}$: Physics-Guided Neural Ordinary Differential Equations for Tuberculosis Transmission Dynamics"
author:
  - literal: "Selain K. Kasereka"
  - literal: "Eric M. Mafuta"
  - literal: "Fadi Al Machot"
  - literal: "Emmanuel M. Kabengele"
  - literal: "Jean Chamberlain Chedjou"
  - literal: "Kyandoghere Kyamakya"
issued:
  date-parts:
    - [2026, 4, 17]
url: "https://arxiv.org/abs/2604.15620"

# Custom fields
paper_id: "2604.15620"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "epidemiological-modeling"
  - "physics-informed-machine-learning"
architectures:
  []
datasets:
  []
concept_slugs:
  - "pg-node"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-20T05:10:49Z"
created_at: "2026-04-20T05:10:49Z"
---

# $PG-NODE^{TB}$: Physics-Guided Neural Ordinary Differential Equations for Tuberculosis Transmission Dynamics

**Authors**: Selain K. Kasereka, Eric M. Mafuta, Fadi Al Machot, Emmanuel M. Kabengele, Jean Chamberlain Chedjou, Kyandoghere Kyamakya
**Date**: 2026-04-17
**Paper ID**: [arxiv:2604.15620](https://arxiv.org/abs/2604.15620)

## Summary

This paper introduces Physics-Guided Neural Ordinary Differential Equations (PG-NODE) to improve tuberculosis transmission modeling. By embedding neural network components into a traditional SLIR compartmental framework, the model captures time-varying transmission dynamics and unmodeled effects that fixed-parameter ODEs fail to represent. Experiments show significant improvements in predictive accuracy over classical models, maintaining epidemiological interpretability while enabling 20-year intervention forecasting.

## Key Contributions

- Introduces a PG-NODE framework that reformulates classical SLIR models to capture unmodeled dynamics and time-varying rate functions.
- Demonstrates 27% reduction in RMSE compared to classical SLIR models in correcting for treatment and relapse dynamics.
- Provides a rigorous mathematical foundation for TB epidemiology, including R0 derivation and sensitivity analysis, within a neural-ODE structure.

## Open Questions & Future Work

- [[parameter-identifiability-in-pg-node]]

## Key Concepts

- [[pg-node]]: A hybrid modeling framework that integrates neural networks into ODE-based compartmental models to capture complex, time-varying dynamics while preserving conservation laws.

## Archivist Review

The paper presents a clear, reusable framework for combining mechanistic models with data-driven neural ODEs, which is a significant topic in time-series modeling. I approved the PG-NODE concept due to its broad applicability beyond epidemiology and the specific open question regarding identifiability under partial observability, as it represents a core bottleneck for physics-informed neural systems in real-world settings. No other candidates were provided or warranted.

### Approved Concepts
- Physics-Guided Neural Ordinary Differential Equations (PG-NODE): Provides a bridge between mechanistic epidemiological compartmental models and data-driven neural networks while maintaining biological constraints.

### Approved Open Questions
- Parameter Identifiability Under Partial Observability: Ensuring parameter identifiability is fundamental for the reliability of machine learning models in public health, preventing the neural components from overfitting noise or producing biologically nonsensical results when applied to real-world, sparse data.

## Links

- [Abstract](https://arxiv.org/abs/2604.15620)
- [PDF](https://arxiv.org/pdf/2604.15620)

