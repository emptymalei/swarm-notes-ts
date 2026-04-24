---
# CSL-compatible fields
title: "Data-Driven Open-Loop Simulation for Digital-Twin Operator Decision Support in Wastewater Treatment"
author:
  - literal: "Gary Simethy"
  - literal: "Daniel Ortiz Arroyo"
  - literal: "Petar Durdevic"
issued:
  date-parts:
    - [2026, 4, 22]
url: "https://arxiv.org/abs/2604.20935"

# Custom fields
paper_id: "2604.20935"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "forecasting"
  - "simulation"
architectures:
  []
datasets:
  - "avedøre-full-scale-benchmark"
concept_slugs:
  - "ccss-rs"
dataset_slugs:
  - "avedøre-full-scale-benchmark"
skill: "GeneralMLSkill"
processed_at: "2026-04-24T05:10:10Z"
created_at: "2026-04-24T05:10:10Z"
---

# Data-Driven Open-Loop Simulation for Digital-Twin Operator Decision Support in Wastewater Treatment

**Authors**: Gary Simethy, Daniel Ortiz Arroyo, Petar Durdevic
**Date**: 2026-04-22
**Paper ID**: [arxiv:2604.20935](https://arxiv.org/abs/2604.20935)

## Summary

The paper introduces CCSS-RS, a controlled continuous-time state-space model designed to serve as a digital-twin simulator for wastewater treatment plants. The architecture effectively decouples historical state inference from future control rollouts, utilizing typed context encoding and Student-t/hurdle distributions to handle irregular sampling, missing data, and heavy-tailed sensor observations. Evaluated on the Avedøre full-scale benchmark, CCSS-RS significantly outperforms standard Neural CDE approaches, providing accurate multi-hour forecasting that aids operators in offline scenario screening and setpoint optimization.

## Key Contributions

- Introduces CCSS-RS, a controlled continuous-time state-space model that enables robust simulation under irregular sampling and high missingness (43%).
- Achieves significant performance gains on the Avedøre benchmark (RMSE 0.696, CRPS 0.349), outperforming Neural CDE baselines by 40-46%.
- Demonstrates operational utility for scenario screening, including robustness to sensor outages and accurate prediction of ammonium/nitrate/oxygen across 12-36 hour horizons.

## Open Questions & Future Work

- [[cross-facility-generalization-wastewater-simulation]]
- [[hybrid-mechanistic-data-modeling]]

## Key Concepts

- [[ccss-rs]]: A continuous-time state-space architecture that decouples historical state estimation from future control rollouts to manage irregular sampling and missing data in industrial environments.

## Archivist Review

I approved the CCSS-RS architecture as a reusable design pattern for decoupling state estimation from control in digital-twin simulators. I also approved two open questions concerning cross-facility generalization and hybrid modeling, as these are critical, non-boilerplate bottlenecks for industrial ML. The Avedøre dataset was initially considered but rejected as it is a highly localized, domain-specific benchmark with limited utility for general ML research.

### Approved Concepts
- Controlled Continuous-Time State-Space Model (CCSS-RS): It provides a specialized architectural pattern for industrial time-series forecasting where historical state inference must be decoupled from future control rollouts.

### Approved Open Questions
- Generalization Across Wastewater Facilities: Generalization is the primary barrier to the broad industrial adoption of data-driven digital twin simulators across diverse infrastructure sites.
- Hybrid Mechanistic-Data Modeling: Hybrid modeling is vital for increasing regulatory acceptance and long-term reliability in infrastructure monitoring systems.

### Rejected Candidates
- [dataset] Avedøre full-scale benchmark (`avedøre-full-scale-benchmark`) - low_impact: The dataset is a specific site-level benchmark that is likely too narrow and niche for broad, reusable archival importance outside of this specific domain.

## Datasets

- [[avedøre-full-scale-benchmark]]

## Links

- [Abstract](https://arxiv.org/abs/2604.20935)
- [PDF](https://arxiv.org/pdf/2604.20935)

