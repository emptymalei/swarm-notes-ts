---
# CSL-compatible fields
title: "Testing $Λ$CDM versus dynamical dark energy in one year: A DESI spectroscopic follow-up program for Rubin supernovae"
author:
  - literal: "Jannik Truong"
  - literal: "Greg Aldering"
  - literal: "Saul Perlmutter"
  - literal: "David Rubin"
  - literal: "David Schlegel"
issued:
  date-parts:
    - [2026, 4, 20]
url: "https://arxiv.org/abs/2604.18859"

# Custom fields
paper_id: "2604.18859"
paper_source: "arxiv"
domain: "computer-vision"
tags:
  - "causal-inference-derived-outcomes"
architectures:
  []
datasets:
  []
concept_slugs:
  - "spectroscopic-standardization"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-04-22T05:04:41Z"
created_at: "2026-04-22T05:04:41Z"
---

# Testing $Λ$CDM versus dynamical dark energy in one year: A DESI spectroscopic follow-up program for Rubin supernovae

**Authors**: Jannik Truong, Greg Aldering, Saul Perlmutter, David Rubin, David Schlegel
**Date**: 2026-04-20
**Paper ID**: [arxiv:2604.18859](https://arxiv.org/abs/2604.18859)

## Summary

This paper proposes a cross-survey observational program between the Vera C. Rubin Observatory and the Dark Energy Spectroscopic Instrument (DESI) to rigorously test the ΛCDM model against dynamical dark energy. By implementing an automated, alert-driven spectroscopic follow-up, the authors show they can obtain 7,500 Type Ia supernova spectra in one year, reaching >5σ tension with ΛCDM. Furthermore, the paper introduces a machine-learning-based spectroscopic standardization method to mitigate systemic errors associated with traditional light-curve techniques, ensuring higher precision in cosmological parameter estimation.

## Key Contributions

- Proposes an integrated survey strategy using Rubin SN alerts to trigger DESI spectroscopic follow-up, enabling the collection of 7,500 transient spectra in one year.
- Forecasts that a volume-limited sample of 2,300 SNe Ia at z<0.3 can elevate current w0-wa tension with ΛCDM to >5σ significance.
- Introduces a machine-learning framework for spectroscopic standardization of SNe Ia as a systematic-reduction technique for cosmological measurements.

## Limitations

The survey performance relies on the persistence of current w0-wa best-fit values and the successful integration of real-time scheduling between two distinct observatories.

## Open Questions & Future Work

- [[calibration-prior-dependency-cosmology]]

## Key Concepts

- [[spectroscopic-standardization]]: A methodology for standardizing Type Ia supernovae using spectroscopic data via machine learning, bypassing reliance on light-curve fitting.

## Archivist Review

The paper proposes a specific spectroscopic standardization approach that represents a significant methodological shift in cosmology, making it a strong candidate for a permanent note. I approved the question regarding prior dependency in cosmology as it touches on a fundamental limit of Bayesian inference in high-precision scientific modeling. I rejected the scheduling optimization question as it relates to specific telescope operational constraints rather than a universal machine learning research problem.

### Approved Concepts
- Spectroscopic Standardization: It introduces an ML-based alternative to traditional light-curve standardization, addressing a primary systematic bottleneck in cosmological supernova surveys.

### Approved Open Questions
- Prior dependency in supernova cosmology: This represents a fundamental bottleneck in achieving high-precision (e.g., 5-sigma) cosmology with Type Ia supernovae, challenging the robustness of hierarchical pipelines.

### Rejected Candidates
- [open_question] Scheduling optimization for transient surveys (`scheduling-pipeline-optimization-transients`) - paper_local: The optimization of observation schedules is specific to the hardware and constraints of individual multi-instrument survey designs, making it too paper-local to generalize effectively as a standalone research problem.

## Links

- [Abstract](https://arxiv.org/abs/2604.18859)
- [PDF](https://arxiv.org/pdf/2604.18859)

