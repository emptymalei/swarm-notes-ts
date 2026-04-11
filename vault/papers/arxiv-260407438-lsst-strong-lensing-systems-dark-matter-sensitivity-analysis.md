---
# CSL-compatible fields
title: "LSST Strong Lensing Systems Dark Matter Sensitivity Analysis with Neural Ratio Estimators"
author:
  - literal: "Andreas Filipp"
  - literal: "Yashar Hezaveh"
  - literal: "Laurence Perreault-Levasseur"
  - literal: "Daniel Gilman"
  - literal: "LSST Dark Energy Science Collaboration"
issued:
  date-parts:
    - [2026, 4, 8]
url: "https://arxiv.org/abs/2604.07438"

# Custom fields
paper_id: "2604.07438"
paper_source: "arxiv"
domain: "astronomy-and-astrophysics"
tags:
  - "simulation-based-inference"
  - "astrophysics"
  - "strong-lensing"
architectures:
  []
datasets:
  []
concept_slugs:
  - "neural-ratio-estimators"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-04-11T04:47:20Z"
created_at: "2026-04-11T04:47:20Z"
---

# LSST Strong Lensing Systems Dark Matter Sensitivity Analysis with Neural Ratio Estimators

**Authors**: Andreas Filipp, Yashar Hezaveh, Laurence Perreault-Levasseur, Daniel Gilman, LSST Dark Energy Science Collaboration
**Date**: 2026-04-08
**Paper ID**: [arxiv:2604.07438](https://arxiv.org/abs/2604.07438)

## Summary

This paper utilizes neural ratio estimators (NREs) to forecast the sensitivity of the upcoming LSST survey to dark matter substructure via strong gravitational lensing. The study demonstrates that by analyzing 2500 galaxy-galaxy lenses, LSST can place stringent constraints on the halo mass function that effectively differentiate between non-ΛCDM scenarios. The findings underscore the critical role of both subhalos and line-of-sight halos, providing a framework for future robust inference methods in large-scale sky surveys.

## Key Contributions

- Forecasts LSST's sensitivity to dark matter substructure using neural ratio estimators (NREs) on simulated galaxy-galaxy strong lenses.
- Demonstrates that analyzing 2500 lenses allows for excluding 74% and 36% of the prior volume at 3σ and 5σ confidence levels, respectively.
- Establishes that both subhalos and line-of-sight (LOS) halos contribute significantly to constraining the halo mass function, with LOS halos gaining importance at higher redshifts.

## Limitations

The analysis assumes perfect knowledge of the data-generating process and does not account for potential systematic errors or real-world observational complexities in actual LSST data.

## Open Questions & Future Work

- [[robust-inference-for-real-survey-data]]
- [[parameter-degeneracies-in-hmf-inference]]

## Key Concepts

- [[neural-ratio-estimators]]: A simulation-based inference framework that utilizes neural networks to estimate likelihood ratios for direct parameter inference.

## Archivist Review

I have approved Neural Ratio Estimators as a fundamental methodology for simulation-based inference. I also approved two open questions that capture the primary bottlenecks for deploying these methods in high-stakes, real-world observational astronomy: bridging the simulation-to-reality gap and resolving inherent parameter degeneracies in lensing models. No datasets were approved as none provided novel, reusable benchmarks independent of the specific simulation setup.

### Approved Concepts
- Neural Ratio Estimators: NREs are the core methodology for likelihood-free inference in simulation-intensive domains, providing a scalable alternative to traditional likelihood-based methods.

### Approved Open Questions
- Robust Inference for Survey Data: Bridging the simulation-to-reality gap is the primary bottleneck for adopting advanced SBI techniques in large-scale observational astronomy.
- HMF Parameter Degeneracy Resolution: Parameter degeneracy is a fundamental limitation in astronomical inference that directly reduces the constraining power of large-scale surveys.

## Links

- [Abstract](https://arxiv.org/abs/2604.07438)
- [PDF](https://arxiv.org/pdf/2604.07438)

