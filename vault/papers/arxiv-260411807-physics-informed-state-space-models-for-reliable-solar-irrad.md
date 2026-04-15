---
# CSL-compatible fields
title: "Physics-Informed State Space Models for Reliable Solar Irradiance Forecasting in Off-Grid Systems"
author:
  - literal: "Mohammed Ezzaldin Babiker Abdullah"
issued:
  date-parts:
    - [2026, 4, 13]
url: "https://arxiv.org/abs/2604.11807"

# Custom fields
paper_id: "2604.11807"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "physics-informed-state-space-model"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-15T05:06:16Z"
created_at: "2026-04-15T05:06:16Z"
---

# Physics-Informed State Space Models for Reliable Solar Irradiance Forecasting in Off-Grid Systems

**Authors**: Mohammed Ezzaldin Babiker Abdullah
**Date**: 2026-04-13
**Paper ID**: [arxiv:2604.11807](https://arxiv.org/abs/2604.11807)

## Summary

This paper introduces the Physics-Informed State Space Model (PISSM) to address the dual challenges of computational overhead and physical inconsistency in off-grid solar irradiance forecasting. By replacing attention mechanisms with linear state space layers and incorporating a dynamic Hankel matrix embedding, PISSM effectively denoises input signals while maintaining parallelizable temporal modeling. A novel Physics-Informed Gating mechanism forces predictions to respect solar geometry, ensuring reliability for edge-based control applications. Experiments demonstrate that PISSM provides superior accuracy with under 40,000 parameters compared to traditional deep learning baselines.

## Key Contributions

- Introduces PISSM, a parameter-efficient state space model designed for edge-deployed microcontrollers.
- Implements a dynamic Hankel matrix embedding for robust stochastic noise filtration in meteorological data.
- Develops a Physics-Informed Gating mechanism that leverages solar zenith angles to enforce physical diurnal cycle constraints on model outputs.

## Key Concepts

- [[physics-informed-state-space-model]]: An ultra-lightweight state space model that incorporates solar geometry physics to bound predictions in off-grid solar forecasting.

## Archivist Review

I approved the PISSM concept as it provides a clear, reusable architectural template for combining linear state space modeling with hard-coded domain-specific physical constraints, which is highly relevant for edge-deployed time-series forecasting. Other potential concepts (like the specific gating or Hankel embedding) were deemed subcomponents of the primary PISSM architecture and thus rejected to keep the vault focused on overarching mechanisms.

### Approved Concepts
- Physics-Informed State Space Model (PISSM): Combines linear state space efficiency with domain-specific physics constraints for reliable, low-power forecasting.

## Links

- [Abstract](https://arxiv.org/abs/2604.11807)
- [PDF](https://arxiv.org/pdf/2604.11807)

