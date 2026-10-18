---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Disentangling geometry & growth in cosmic neutrino mass constraints: a more physical split and diagnostic"
description: "The paper introduces a diagnostic framework to address the 'negative neutrino mass' tension in cosmology by disentangling the effects of neutrinos on geometry and structure growth. By splitting the neutrino mass parameter into two components (\\sum m_ν^{geo} and \\sum m_ν^{growth}) at the Boltzmann-code level, the authors create a consistency test for the standard ΛCDM model. Their analysis of recent Planck and DESI data reveals that both channels independently prefer negative mass values but remain mutually consistent, suggesting the tension may be shared across different physical effects. Furthermore, they demonstrate that this split can distinguish between different sources of systematic error, such as dark energy mismodeling or reionization depth inaccuracies."
resource: "https://arxiv.org/abs/2610.20977"
tags:
  - "cosmology"
  - "astrophysics"
  - "bayesian-methods"
  - "fisher-forecast"
  - "uncertainty-quantification"
  - "physics-informed-learning"
  - "statistical-modeling"
timestamp: "2026-10-18T00:27:25Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Fei Ge"
  - literal: "Frank J. Qu"
  - literal: "Hanyue Wang"
  - literal: "Emmanuel Schaan"
  - literal: "W. L. Kimmy Wu"
  - literal: "Alexander Friedland"
issued:
  date-parts:
    - [2026, 10, 14]

# Domain-specific custom fields
paper_id: "2610.20977"
paper_source: "arxiv"
architectures:
  []
concepts:
  []
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-18T00:27:25Z"
created_at: "2026-10-18T00:27:25Z"
---

# Disentangling geometry & growth in cosmic neutrino mass constraints: a more physical split and diagnostic

**Authors**: Fei Ge, Frank J. Qu, Hanyue Wang, Emmanuel Schaan, W. L. Kimmy Wu, Alexander Friedland
**Date**: 2026-10-14
**Paper ID**: [arxiv:2610.20977](https://arxiv.org/abs/2610.20977)

## Summary

The paper introduces a diagnostic framework to address the 'negative neutrino mass' tension in cosmology by disentangling the effects of neutrinos on geometry and structure growth. By splitting the neutrino mass parameter into two components (\sum m_ν^{geo} and \sum m_ν^{growth}) at the Boltzmann-code level, the authors create a consistency test for the standard ΛCDM model. Their analysis of recent Planck and DESI data reveals that both channels independently prefer negative mass values but remain mutually consistent, suggesting the tension may be shared across different physical effects. Furthermore, they demonstrate that this split can distinguish between different sources of systematic error, such as dark energy mismodeling or reionization depth inaccuracies.

## Key Contributions

- Proposed a physical split of the neutrino mass parameter into geometry (expansion rate for distance) and growth (perturbation evolution) components at the Boltzmann-code level.
- Demonstrated that current cosmological data (Planck, ACT, SPT, and DESI) show a consistent preference for negative neutrino masses in both geometry and growth channels, while passing a null test for ΛCDM at the 0.4σ level.
- Developed a diagnostic framework using Fisher forecasts that can distinguish between dark energy mismodeling and reionization optical depth (τ) errors based on the differential shifts in the two split mass channels.

## Limitations

The analysis primarily focuses on ΛCDM extensions; the behavior of this split under more complex modified gravity models or non-standard neutrino interactions requires further study.

## Archivist Review

The candidates provided are highly specific to the field of cosmology and observational astrophysics. While the paper uses statistical techniques like Fisher forecasting, its core contributions—such as the parameter split in Boltzmann codes and the investigation of neutrino mass tensions—are physical diagnostics rather than reusable machine learning concepts or datasets. Consequently, no items were approved for the general ML knowledge vault.

### Rejected Candidates
- [concept] Neutrino Geo-Growth Split (`neutrino-geo-growth-split`) - other: The concept is a domain-specific physical diagnostic for cosmological Boltzmann codes and does not represent a reusable machine learning architecture or methodology.
- [dataset] DESI BAO (`desi-bao`) - other: This is an observational astronomy dataset used for physical parameter estimation, not a standard benchmark or dataset for general machine learning research.
- [dataset] Planck primary CMB (`planck-primary-cmb`) - other: This is an observational physics dataset used for cosmological inference, not for the development or evaluation of general ML models.
- [open_question] Origin of Negative Neutrino Mass Preference (`negative-neutrino-mass-origin`) - other: This is a fundamental research question in theoretical physics and cosmology, not a challenge for the machine learning community.
- [open_question] Neutrino Split in Modified Gravity (`modified-gravity-neutrino-diagnostic`) - other: The question concerns the behavior of physical parameters within modified gravity theories, which is outside the scope of general machine learning.

## Links

- [Abstract](https://arxiv.org/abs/2610.20977)
- [PDF](https://arxiv.org/pdf/2610.20977)

