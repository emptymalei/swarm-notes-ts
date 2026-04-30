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
  []
architectures:
  []
datasets:
  - "lisflood-fp"
concept_slugs:
  - "observation-guided-neural-surrogate-learning"
dataset_slugs:
  - "lisflood-fp"
skill: "TimeSeriesSkill"
processed_at: "2026-04-30T05:15:14Z"
created_at: "2026-04-30T05:15:14Z"
---

# Observation-Guided Neural Surrogate Learning for Scientific Simulation Emulation: A Single-Gauge Flood-Inundation Proof of Concept

**Authors**: Marzieh Alireza Mirhoseini
**Date**: 2026-04-28
**Paper ID**: [arxiv:2604.25890](https://arxiv.org/abs/2604.25890)

## Summary

This paper introduces an observation-guided neural surrogate framework designed to emulate hydrodynamic flood-inundation simulations. By integrating a coarse ensemble Gaussian-process surrogate with a U-Net-ASPP neural corrector, the model refines spatial inundation maps using sparse, single-gauge observational data as a pointwise supervision target. The approach achieves high accuracy in reproducing simulation targets while maintaining strong consistency with local water-depth observations.

## Key Contributions

- Introduces an observation-guided neural surrogate framework that leverages sparse gauge data as pointwise supervision to correct hydrodynamic simulation emulators.
- Demonstrates that the EnsCGP surrogate coupled with a U-Net-ASPP corrector achieves high reconstruction accuracy (R^2 ≈ 0.99) on flood-inundation mapping against simulation ground truths.
- Establishes a hybrid training paradigm where pointwise gauge supervision is combined with simulation-based spatial losses to ensure consistency across the inundation grid.

## Open Questions & Future Work

- [[generalization-and-validation-of-observation-guided-surrogates]]

## Key Concepts

- [[observation-guided-neural-surrogate-learning]]: A framework for emulating scientific simulations by utilizing sparse observational data as pointwise supervision alongside simulation-based spatial losses.

## Archivist Review

The approval is limited to the core framework contribution and the primary simulation dataset used for evaluation. The open question was refined to emphasize the critical need for spatial validation and robustness testing, as these are the main bottlenecks preventing transition from proof-of-concept to operational utility. I rejected specific architectural components (e.g., U-Net-ASPP) as they represent standard practice rather than distinct, reusable scientific contributions.

### Approved Concepts
- Observation-Guided Neural Surrogate Learning: The framework addresses the integration of sparse, real-world observational data into complex physical simulation emulators to enforce consistency through a hybrid training paradigm.

### Approved Open Questions
- Generalization and validation of observation-guided surrogates: These steps are essential to move beyond local proof-of-concept demonstrations and to establish the framework as a reliable, generalizable, and operationally viable tool for scientific simulation emulation.

## Datasets

- [[lisflood-fp]]

## Links

- [Abstract](https://arxiv.org/abs/2604.25890)
- [PDF](https://arxiv.org/pdf/2604.25890)

