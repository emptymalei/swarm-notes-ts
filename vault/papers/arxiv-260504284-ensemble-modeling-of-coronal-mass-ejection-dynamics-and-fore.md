---
# CSL-compatible fields
title: "Ensemble modeling of Coronal Mass Ejection dynamics and forecasts at 1 AU with a semi-analytic flux-rope model"
author:
  - literal: "S. Stamkos"
  - literal: "S. Patsourakos"
  - literal: "A. Vourlidas"
  - literal: "E. Paouris"
issued:
  date-parts:
    - [2026, 5, 5]
url: "https://arxiv.org/abs/2605.04284"

# Custom fields
paper_id: "2605.04284"
paper_source: "arxiv"
domain: "physical-sciences"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "semi-analytic-efr-model-ensemble"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-05-07T05:16:13Z"
created_at: "2026-05-07T05:16:13Z"
---

# Ensemble modeling of Coronal Mass Ejection dynamics and forecasts at 1 AU with a semi-analytic flux-rope model

**Authors**: S. Stamkos, S. Patsourakos, A. Vourlidas, E. Paouris
**Date**: 2026-05-05
**Paper ID**: [arxiv:2605.04284](https://arxiv.org/abs/2605.04284)

## Summary

This paper presents a Monte Carlo-based ensemble framework for assessing how uncertainties in initial coronal mass ejection (CME) and solar-wind parameters propagate to 1 AU forecast metrics. By enhancing a semi-analytic erupting flux rope (EFR) model with refined sheath effects and drag coupling, the authors perform sensitivity analysis across six CME events. Their results reveal the distinct physical drivers—ranging from poloidal-flux history to background flow—that dominate the dispersion of arrival time, impact duration, and magnetic field diagnostics at 1 AU.

## Key Contributions

- Quantifies the propagation of uncertainty from CME eruption parameters and background solar-wind conditions to 1 AU forecast diagnostics using a Monte Carlo ensemble approach.
- Enhances the traditional EFR model by incorporating sheath/pile-up effects through effective mass and refined CME-solar-wind drag coupling.
- Identifies event-specific physical parameters (e.g., poloidal-flux injection, upstream wind speed, geometric size) that act as the primary sources of variance for arrival time, leading-edge speed, and magnetic field strength at 1 AU.

## Limitations

The model assumes specific semi-analytic physics (Lorentz, gravity, drag) which may miss complex 3D magnetohydrodynamic (MHD) interactions; results are currently limited to six specific CME events.

## Open Questions & Future Work

- [[cme-forecasting-uncertainty-reduction]]

## Key Concepts

- [[semi-analytic-efr-model-ensemble]]: A Monte Carlo-embedded semi-analytic flux-rope model framework for assessing the sensitivity of space weather diagnostics to input uncertainties.

## Archivist Review

I approved the semi-analytic flux-rope ensemble framework as a reusable pattern for uncertainty quantification in physics-informed solar modeling. The open question regarding CME forecast uncertainty was approved as a high-level research bottleneck that tracks well across space weather forecasting literature. No datasets were approved as they were not a primary contribution of this work.

### Approved Concepts
- Semi-Analytic Erupting Flux Rope Model Ensemble: Provides a computationally efficient framework for quantifying uncertainty propagation from solar eruption parameters to 1 AU diagnostics, which is critical for physical model validation.

### Approved Open Questions
- Reducing CME Forecast Uncertainty: Bridging the gap between semi-analytic model inputs and high-fidelity observational constraints is a prerequisite for improving the reliability of operational space weather forecasting.

## Links

- [Abstract](https://arxiv.org/abs/2605.04284)
- [PDF](https://arxiv.org/pdf/2605.04284)

