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
domain: "computer-vision"
tags:
  - "machine-learning-for-science"
  - "probabilistic-modeling"
  - "inference"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-04-10T15:30:18Z"
created_at: "2026-04-10T15:30:18Z"
---

# LSST Strong Lensing Systems Dark Matter Sensitivity Analysis with Neural Ratio Estimators

**Authors**: Andreas Filipp, Yashar Hezaveh, Laurence Perreault-Levasseur, Daniel Gilman, LSST Dark Energy Science Collaboration
**Date**: 2026-04-08
**Paper ID**: [arxiv:2604.07438](https://arxiv.org/abs/2604.07438)

## Summary

This paper evaluates the potential of the Vera C. Rubin Observatory (LSST) to constrain dark matter properties using strong gravitational lensing systems. The researchers employ neural ratio estimators (NREs) to perform inference on simulated lens populations, accounting for both subhalos and line-of-sight structures down to $10^7 M_\odot$. The study demonstrates that large samples of ~2500 lenses significantly outperform current constraints, providing a path to exclude non-ΛCDM models at high statistical significance. The findings emphasize the importance of accounting for low-mass halos and line-of-sight contributions in future survey analyses.

## Key Contributions

- Forecasted LSST sensitivity to dark matter substructure by utilizing neural ratio estimators (NREs) on galaxy-galaxy strong lensing systems.
- Demonstrated that scaling the sample size to 2500 lenses enables 3σ and 5σ exclusion of significant portions of non-ΛCDM prior volumes.
- Quantified the relative contribution of line-of-sight (LOS) halos versus deflector-intrinsic subhalos, showing that LOS halos are increasingly critical at higher redshifts.

## Open Questions & Future Work

- [[robust-inference-for-real-data]]
- [[degeneracy-in-hmf-parameters]]

## Archivist Review

The paper focuses on simulation-based inference for astrophysical dark matter detection. No new concepts were approved because the core methodology, 'Neural Ratio Estimators,' is already widely recognized and represented in literature. The open questions regarding robust inference for real-world data and parameter degeneracies in mass function modeling are well-defined, critical bottlenecks for this research domain and qualify for tracking as standalone challenges.

### Approved Open Questions
- Robust Inference for Real Data: This is a fundamental challenge for the field of simulation-based inference in astrophysics, particularly when moving from idealized forecasts to real-world data analysis.
- Degeneracies in HMF Parameters: This degeneracy directly impacts the ability to constrain dark matter physics, as it affects the interpretation of the mass function parameters across diverse subhalo configurations.

## Links

- [Abstract](https://arxiv.org/abs/2604.07438)
- [PDF](https://arxiv.org/pdf/2604.07438)

