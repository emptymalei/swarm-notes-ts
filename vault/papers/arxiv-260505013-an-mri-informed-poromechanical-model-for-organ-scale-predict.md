---
# CSL-compatible fields
title: "An MRI-informed poromechanical model for organ-scale prediction of glioma growth"
author:
  - literal: "Meryem Abbad Andaloussi"
  - literal: "Stephane Urcun"
  - literal: "David A. Hormuth"
  - literal: "Guillermo Lorenzo"
  - literal: "Giuseppe Sciume"
  - literal: "Cheguye Wu"
  - literal: "Thomas E. Yankeelov"
  - literal: "Stephane P. A. Bordas"
issued:
  date-parts:
    - [2026, 5, 6]
url: "https://arxiv.org/abs/2605.05013"

# Custom fields
paper_id: "2605.05013"
paper_source: "arxiv"
domain: "computational-biology"
tags:
  - "physics-informed-machine-learning"
  - "medical-imaging"
  - "time-series-forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-07T05:13:49Z"
created_at: "2026-05-07T05:13:49Z"
---

# An MRI-informed poromechanical model for organ-scale prediction of glioma growth

**Authors**: Meryem Abbad Andaloussi, Stephane Urcun, David A. Hormuth, Guillermo Lorenzo, Giuseppe Sciume, Cheguye Wu, Thomas E. Yankeelov, Stephane P. A. Bordas
**Date**: 2026-05-06
**Paper ID**: [arxiv:2605.05013](https://arxiv.org/abs/2605.05013)

## Summary

This paper presents an MRI-informed poroelastic model to simulate and forecast glioma growth by capturing mechanical tissue deformation and fluid transport dynamics beyond traditional reaction-diffusion approaches. By integrating longitudinal, multi-modal MRI data from animal models, the framework calibrates mechanical and physiological properties to predict tumor progression. Results demonstrate high fidelity in both volume estimation and spatial segmentation, suggesting the model's potential for patient-specific therapeutic planning.

## Key Contributions

- Introduces a patient-specific, MRI-informed poroelastic model for predicting C6 glioma growth in longitudinal rat models.
- Integrates multi-modal MRI data (T1-weighted, diffusion-weighted, and dynamic contrast-enhanced) to parameterize tissue mechanical properties, tumor fraction, and vascular permeability.
- Demonstrates predictive capability in glioma volume and spatial morphology, achieving Dice scores up to 0.93 in validation cohorts.

## Open Questions & Future Work

- [[refining-poromechanical-constitutive-relationships]]
- [[drivers-of-glioma-growth-directionality]]

## Archivist Review

I have approved two open questions that address specific physical modeling challenges—constitutive relationship accuracy and growth driver identification—which are central to the progress of computational oncology forecasting. I rejected the poroelastic model as a concept because it is a domain-specific application of well-established mechanics rather than a reusable machine learning or statistical forecasting primitive. No datasets were approved as the study uses a limited, specific rodent cohort rather than a broad, reusable benchmark.

### Approved Open Questions
- Refining poromechanical constitutive relationships: Solid pressure is a key factor in inhibiting tumor growth and predicting treatment response; ensuring this variable is accurately estimated is essential for model reliability.
- Drivers of glioma growth directionality: Correctly identifying the primary drivers of tumor spatial progression is necessary for reliable spatiotemporal forecasting and treatment planning.

### Rejected Candidates
- [concept] MRI-informed poroelastic model for glioma growth (`poroelastic-glioma-model`) - paper_local: The paper-specific model is a specialized application of existing poromechanical frameworks rather than a novel conceptual contribution.

## Links

- [Abstract](https://arxiv.org/abs/2605.05013)
- [PDF](https://arxiv.org/pdf/2605.05013)

