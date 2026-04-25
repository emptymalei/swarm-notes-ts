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
  - "digital-twin"
  - "industrial-ai"
  - "continuous-time-modeling"
architectures:
  []
datasets:
  - "avedøre-full-scale-benchmark"
concept_slugs:
  - "ccss-rs"
dataset_slugs:
  - "avedøre-full-scale-benchmark"
skill: "GeneralMLSkill"
processed_at: "2026-04-25T04:56:25Z"
created_at: "2026-04-25T04:56:25Z"
---

# Data-Driven Open-Loop Simulation for Digital-Twin Operator Decision Support in Wastewater Treatment

**Authors**: Gary Simethy, Daniel Ortiz Arroyo, Petar Durdevic
**Date**: 2026-04-22
**Paper ID**: [arxiv:2604.20935](https://arxiv.org/abs/2604.20935)

## Summary

This paper addresses the challenge of creating digital-twin decision support for wastewater treatment plants by introducing CCSS-RS, a controlled continuous-time state-space model. The framework handles irregular and missing sensor data through typed context encoding and semigroup-consistent rollouts, while using a Student-t plus hurdle output distribution to address heavy-tailed, zero-inflated sensor observations. Validated on the large-scale Avedøre dataset, CCSS-RS significantly outperforms neural CDE baselines in long-horizon forecasting and provides robust operational insights for offline scenario screening.

## Key Contributions

- Introduces CCSS-RS, a controlled continuous-time state-space model that effectively separates historical state inference from future control rollouts.
- Achieves superior performance on the Avedøre benchmark with high missingness (43%) and irregular sampling, reducing RMSE by 31–46% against strong baselines.
- Demonstrates practical utility in wastewater treatment scenario screening, maintaining accuracy under sensor outages and providing reliable predictions for multi-criterion operational decision support.

## Open Questions & Future Work

- [[cross-facility-generalization-wastewater-simulation]]
- [[hybrid-mechanistic-data-modeling]]

## Key Concepts

- [[ccss-rs]]: A controlled continuous-time state-space model for industrial process simulation that decouples state inference from future control rollouts.

## Archivist Review

I approved CCSS-RS as a reusable architectural pattern for industrial time-series and the Avedøre benchmark as a significant high-missingness industrial dataset. The open questions were refined to align with existing vault naming conventions and to focus on fundamental bottlenecks in industrial AI deployment.

### Approved Concepts
- CCSS-RS: The model provides a robust architecture for industrial time-series that decouples latent state estimation from future control trajectories.

### Approved Open Questions
- Cross-Facility Generalization Bottlenecks: The industrial scalability of digital twins hinges on the ability to deploy models across facilities with minimal overhead.
- Hybrid Mechanistic-Data Fusion: This fusion is essential for the regulatory acceptance and operational reliability of AI-based decision support in critical infrastructure.

### Rejected Candidates
- [open_question] Cross-Facility Generalization in WWTP (`cross-facility-generalization-wwtp`) - duplicate_existing: Renamed for better alignment with existing vault terminology (cross-facility-generalization-wastewater-simulation).
- [open_question] Hybrid Mechanistic Data-Driven Modeling (`hybrid-mechanistic-data-driven-modeling`) - duplicate_existing: Renamed for conciseness (hybrid-mechanistic-data-modeling).

## Datasets

- [[avedøre-full-scale-benchmark]]

## Links

- [Abstract](https://arxiv.org/abs/2604.20935)
- [PDF](https://arxiv.org/pdf/2604.20935)

