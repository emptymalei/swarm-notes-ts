---
# CSL-compatible fields
title: "Observation-Guided Neural Surrogate Learning for Scientific Simulation Emulation: A Single-Gauge Flood-Inundation Proof of Concept"
author:
  - literal: "Marzieh Alireza Mirhoseini"
issued:
  date-parts:
    - [2026, 4, 28]
url: "https://arxiv.org/abs/2604.25890"

# Custom fields
paper_id: "2604.25890"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "forecasting"
  - "machine-learning"
  - "simulation-emulation"
architectures:
  []
datasets:
  - "lisflood-fp"
concept_slugs:
  - "observation-guided-neural-surrogate-learning"
dataset_slugs:
  - "lisflood-fp"
skill: "TimeSeriesSkill"
processed_at: "2026-04-29T05:10:41Z"
created_at: "2026-04-29T05:10:41Z"
---

# Observation-Guided Neural Surrogate Learning for Scientific Simulation Emulation: A Single-Gauge Flood-Inundation Proof of Concept

**Authors**: Marzieh Alireza Mirhoseini
**Date**: 2026-04-28
**Paper ID**: [arxiv:2604.25890](https://arxiv.org/abs/2604.25890)

## Summary

The paper introduces a hybrid neural surrogate-learning framework for scientific simulation emulation, specifically applied to urban flood-inundation mapping. By combining an ensemble-based Gaussian process surrogate with a U-Net-ASPP neural corrector, the model refines spatial flood-depth maps using sparse gauge data as a pointwise training target. The methodology demonstrates high fidelity to hydrodynamic simulations while incorporating real-world observational constraints without requiring dense ground-truth data for supervision.

## Key Contributions

- Proposes a hybrid emulator using an ensemble-approximated Gaussian-process (EnsCGP) for initial estimation followed by a U-Net-ASPP neural corrector.
- Demonstrates that single-site gauge supervision can effectively refine spatial flood-inundation maps while maintaining high consistency with hydrodynamic simulation targets.
- Achieves an R^2 of ~0.99 and MAE < 0.01 m in reconstructing LISFLOOD-FP inundation patterns using only sparse, observation-guided training.

## Open Questions & Future Work

- [[independent-validation-of-scientific-surrogates]]

## Key Concepts

- [[observation-guided-neural-surrogate-learning]]: A hybrid framework that combines coarse ensemble-based surrogate modeling with neural refinement constrained by sparse point-gauge observations.

## Archivist Review

I approved the observation-guided neural surrogate concept as it provides a structured methodology for fusing sparse sensor data with abundant simulation output. I also approved a refined version of the validation open question focusing on the general bottleneck of spatial validation for surrogate models. I rejected the proposed standardizing validation question because standard practices for addressing evaluation optimism and data leakage should already be assumed in rigorous research.

### Approved Concepts
- Observation-Guided Neural Surrogate Learning: It provides a principled way to incorporate sparse ground-truth observations to correct and ground simulation-based emulators, which is a common challenge in scientific AI.

### Approved Open Questions
- Validating Spatial Accuracy of Surrogates: This is critical to distinguishing between a model that faithfully reproduces a simulator's potentially biased physics versus one that accurately models the real world.

### Rejected Candidates
- [open_question] Validating Observation-Guided Surrogates (`standardizing-observation-guided-validation`) - not_novel: The problem of optimism bias and temporal leakage in evaluation is a standard machine learning best-practice challenge, not a unique or fundamental open question.

## Datasets

- [[lisflood-fp]]

## Links

- [Abstract](https://arxiv.org/abs/2604.25890)
- [PDF](https://arxiv.org/pdf/2604.25890)

