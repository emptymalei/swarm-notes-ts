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
domain: "astrophysics"
tags:
  - "astrophysics"
  - "cosmology"
  - "supernovae"
  - "calibration"
  - "systematics-analysis"
  - "dark-energy"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-22T05:02:37Z"
created_at: "2026-04-22T05:02:37Z"
---

# Calibration-Induced Systematics in SALT3 Training and Their Impact on Dark Energy Constraints from Stage IV Supernova Surveys

**Authors**: Kene Anumba, David 0. Jones, Richard Kessler, Daniel Scolnic, W. D'Arcy Kenworthy, Rebecca C. Chen, Bastien Carreres, Maria Vincenzi, Erik R. Peterson, Maria Acevedo, Ben Rose, Dillon Brout, Jillian Paulin, Rujuta A. Purohit, Rebekah Hounsell, The Roman Supernova Cosmology Project Infrastructure Team
**Date**: 2026-04-21
**Paper ID**: [arxiv:2604.19746](https://arxiv.org/abs/2604.19746)

## Summary

This study investigates the impact of photometric calibration systematics on Type Ia supernova cosmology using simulated data from the Vera Rubin Observatory (LSST) and the Roman Space Telescope. By perturbing zero-points and filter wavelengths, the authors demonstrate that calibration errors in light-curve fitting are the dominant source of systematic uncertainty, leading to a ~50% degradation in the dark energy Figure of Merit. These biases are found to be degenerate with cosmological parameters, presenting a significant challenge for future precision supernova surveys.

## Key Contributions

- Quantifies the impact of photometric calibration uncertainties (zero-points and filter wavelengths) on the dark energy Figure of Merit (FoM) for Rubin-LSST and Roman HLTDS.
- Demonstrates that calibration-induced systematics during light-curve fitting significantly outweigh those incurred during model training, reducing the FoM by ~50%.
- Shows that calibration-induced biases in light-curve fitting are redshift-dependent and degenerate with cosmological parameters, limiting the efficacy of self-calibration techniques.

## Open Questions & Future Work

- [[saltshaker-training-artifact-mitigation]]

## Archivist Review

This paper provides a domain-specific analysis of calibration-induced systematic errors in supernova cosmology, which falls outside the primary scope of generic time-series forecasting. I have approved one open question concerning the mitigation of model-training artifacts, which represents a substantial, identified research bottleneck for high-precision astrophysical modeling. No concepts were approved as the primary findings are highly specific to the astrophysical calibration domain rather than general-purpose time-series mechanisms.

### Approved Open Questions
- SALTshaker training artifact mitigation: Establishing optimal training datasets is critical for the accuracy of next-generation SN Ia cosmological analyses, as these models are fundamental for standardizing supernovae across wide redshift ranges.

### Rejected Candidates
- [open_question] SALT3 training with prism spectra (`salt3-training-artifacts-prism-spectra`) - other: Renamed to be more descriptive of the mitigation goal rather than the specific observation.

## Links

- [Abstract](https://arxiv.org/abs/2604.19746)
- [PDF](https://arxiv.org/pdf/2604.19746)

