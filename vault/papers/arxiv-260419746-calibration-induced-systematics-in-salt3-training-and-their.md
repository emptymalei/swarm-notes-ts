---
# CSL-compatible fields
title: "Calibration-Induced Systematics in SALT3 Training and Their Impact on Dark Energy Constraints from Stage IV Supernova Surveys"
author:
  - literal: "Kene Anumba"
  - literal: "David 0. Jones"
  - literal: "Richard Kessler"
  - literal: "Daniel Scolnic"
  - literal: "W. D'Arcy Kenworthy"
  - literal: "Rebecca C. Chen"
  - literal: "Bastien Carreres"
  - literal: "Maria Vincenzi"
  - literal: "Erik R. Peterson"
  - literal: "Maria Acevedo"
  - literal: "Ben Rose"
  - literal: "Dillon Brout"
  - literal: "Jillian Paulin"
  - literal: "Rujuta A. Purohit"
  - literal: "Rebekah Hounsell"
  - literal: "The Roman Supernova Cosmology Project Infrastructure Team"
issued:
  date-parts:
    - [2026, 4, 21]
url: "https://arxiv.org/abs/2604.19746"

# Custom fields
paper_id: "2604.19746"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "probabilistic-forecasting"
  - "time-series"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-23T05:08:42Z"
created_at: "2026-04-23T05:08:42Z"
---

# Calibration-Induced Systematics in SALT3 Training and Their Impact on Dark Energy Constraints from Stage IV Supernova Surveys

**Authors**: Kene Anumba, David 0. Jones, Richard Kessler, Daniel Scolnic, W. D'Arcy Kenworthy, Rebecca C. Chen, Bastien Carreres, Maria Vincenzi, Erik R. Peterson, Maria Acevedo, Ben Rose, Dillon Brout, Jillian Paulin, Rujuta A. Purohit, Rebekah Hounsell, The Roman Supernova Cosmology Project Infrastructure Team
**Date**: 2026-04-21
**Paper ID**: [arxiv:2604.19746](https://arxiv.org/abs/2604.19746)

## Summary

This paper investigates how photometric calibration errors—specifically zero-point shifts and filter wavelength variations—impact Type Ia supernova cosmology for future high-precision surveys like Rubin-LSST and Roman. By simulating these systematics and propagating them through both model training and light-curve fitting, the authors show that fitting-stage uncertainties are the primary bottleneck for dark energy constraints. The findings suggest that these systematic effects are largely degenerate with cosmological parameters, necessitating more rigorous calibration strategies to meet Stage IV requirements.

## Key Contributions

- Quantifies the systematic impact of photometric calibration uncertainties on SN Ia cosmology for upcoming Rubin-LSST and Roman HLTDS surveys.
- Demonstrates that calibration uncertainties during light-curve fitting significantly outweigh those from model training, reducing the dark energy figure of merit by ~50%.
- Reveals that calibration-induced systematics evolve smoothly with redshift and exhibit strong degeneracy with cosmology, challenging conventional mitigation strategies.

## Open Questions & Future Work

- [[calibration-systematics-fitting-vs-training-discrepancies]]

## Archivist Review

I have rejected the SALT3-specific training artifact question as it is a narrow implementation issue. I have approved a rephrased version of the fitting vs. training systematic discrepancy as an open question, as this is a fundamental problem in understanding how observation-level errors propagate through different stages of complex scientific pipelines. I chose not to approve any concepts as no novel, reusable forecasting methodology was presented beyond standard systematic error propagation analysis.

### Approved Open Questions
- Supernova calibration systematic discrepancies: Understanding these calibration-induced systematics is vital for next-generation dark energy experiments that require sub-percent level control of systematic uncertainties.

### Rejected Candidates
- [open_question] SALT3 prism-only training artifacts (`salt3-prism-only-training-artifacts`) - paper_local: This is a specific, narrow implementation artifact related to the SALTShaker training tool rather than a foundational research question.

## Links

- [Abstract](https://arxiv.org/abs/2604.19746)
- [PDF](https://arxiv.org/pdf/2604.19746)

