---
# CSL-compatible fields
title: "Primordial magnetic fields in the light of upcoming post-EoR Lyman-$α$ and 21-cm observations"
author:
  - literal: "Arko Bhaumik"
  - literal: "Sourav Pal"
  - literal: "Supratik Pal"
issued:
  date-parts:
    - [2026, 4, 8]
url: "https://arxiv.org/abs/2604.07327"

# Custom fields
paper_id: "2604.07327"
paper_source: "arxiv"
domain: "cosmology"
tags:
  - "cosmology"
  - "forecasting"
  - "signal-processing"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-04-10T15:30:43Z"
created_at: "2026-04-10T15:30:43Z"
---

# Primordial magnetic fields in the light of upcoming post-EoR Lyman-$α$ and 21-cm observations

**Authors**: Arko Bhaumik, Sourav Pal, Supratik Pal
**Date**: 2026-04-08
**Paper ID**: [arxiv:2604.07327](https://arxiv.org/abs/2604.07327)

## Summary

This paper investigates the constraining power of post-reionization era observables—specifically the Lyman-α power spectrum, the 21 cm power spectrum, and their cross-spectrum—on primordial magnetic fields (PMF). Using Fisher forecast and SNR estimation, the authors evaluate future survey combinations, including DESI-like spectroscopic surveys paired with SKA1-Mid and PUMA. The findings suggest that the Lyα-21 cm cross-correlation, being largely immune to foreground interference, offers a superior path for precisely constraining sub-nG PMF parameters (B₀, n_B) compared to individual auto-spectra.

## Key Contributions

- Provides a Fisher forecast analysis for constraining primordial magnetic field (PMF) parameters using post-reionization Lyα, 21-cm, and cross-correlation spectra.
- Identifies the Lyα-21 cm cross-correlation as a foreground-robust probe for detecting sub-nG PMFs with upcoming observational facilities.
- Quantifies potential constraints on PMF amplitude (B₀) and spectral index (n_B) for DESI-like surveys combined with SKA1-Mid and PUMA, showing ≤10% relative errors for the DESI-like+SKA1-Mid setup.

## Open Questions & Future Work

- [[mhd-based-hi-bias-modeling]]
- [[realistic-foreground-modeling-21cm]]

## Archivist Review

The paper is highly domain-specific, focusing on Fisher forecasts for primordial magnetic fields. I have rejected all concept candidates as they were either generic (e.g., Fisher forecasting) or specific to the cosmology domain without a broader ML methodology contribution. I approved two open questions that reflect significant bottlenecks in computational cosmology and signal processing for intensity mapping, as these are recurring challenges in modern observational ML.

### Approved Open Questions
- MHD-based HI bias modeling: This is a fundamental bottleneck for precision cosmology as we move beyond standard LCDM assumptions in interpreting non-linear tracers.
- Foregrounds in 21cm surveys: This remains the primary systematic bottleneck for the utilization of 21-cm data in cosmology.

## Links

- [Abstract](https://arxiv.org/abs/2604.07327)
- [PDF](https://arxiv.org/pdf/2604.07327)

