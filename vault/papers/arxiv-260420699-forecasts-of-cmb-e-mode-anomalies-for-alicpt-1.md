---
# CSL-compatible fields
title: "Forecasts of CMB E-mode anomalies for AliCPT-1"
author:
  - literal: "Jiazheng Dou"
  - literal: "Wen Zhao"
issued:
  date-parts:
    - [2026, 4, 22]
url: "https://arxiv.org/abs/2604.20699"

# Custom fields
paper_id: "2604.20699"
paper_source: "arxiv"
domain: "cosmology"
tags:
  []
architectures:
  []
datasets:
  - "alicpt"
  - "simons-observatory-lat"
concept_slugs:
  []
dataset_slugs:
  - "alicpt"
  - "simons-observatory-lat"
skill: "GeneralMLSkill"
processed_at: "2026-04-25T04:55:57Z"
created_at: "2026-04-25T04:55:57Z"
---

# Forecasts of CMB E-mode anomalies for AliCPT-1

**Authors**: Jiazheng Dou, Wen Zhao
**Date**: 2026-04-22
**Paper ID**: [arxiv:2604.20699](https://arxiv.org/abs/2604.20699)

## Summary

This paper investigates the feasibility of detecting large-scale statistical anomalies in the CMB E-mode polarization using the upcoming AliCPT-1 telescope. By analyzing 1000 simulations, the authors assess the instrument's capability to recover signals like dipole modulation, lack of large-angle correlations, quadrupole-octopole alignment, and point-parity asymmetry. The results indicate that while AliCPT-1 alone faces limitations due to sky coverage, joining forces with the Simons Observatory (SO) provides a robust platform capable of reaching near-cosmic-variance sensitivity for these cosmological tests.

## Key Contributions

- Evaluated the sensitivity of AliCPT-1 to large-scale CMB E-mode anomalies using 1000 NILC-processed simulations.
- Demonstrated that a combined AliCPT+SO dataset can detect dipole modulation at a 99% confidence level for an input amplitude of Ad = 0.07.
- Identified that AliCPT's limited sky coverage induces systematic biases in quadrupole-octopole alignment and point-parity asymmetry, which are mitigated by integration with SO observations.

## Open Questions & Future Work

- [[constrained-vs-unconstrained-cmb-anomaly-testing]]
- [[complex-foreground-residual-bias]]

## Archivist Review

The paper provides a forecast for CMB anomaly detection. I have approved two datasets that are central to the study's claims regarding future experimental sensitivity. The two open questions were also approved as they articulate significant methodological hurdles in cosmological anomaly testing, with one renamed slightly to match existing vault nomenclature. No new concepts were approved as the methods described (e.g., NILC, anomaly estimators) are standard in the field.

### Approved Open Questions
- Constrained vs Unconstrained CMB Anomaly Testing: Determining the appropriate ensemble for comparison is essential to distinguish between a rare statistical fluctuation within the ΛCDM model and genuine new physics, as it impacts the validity of statistical significance claims.
- Complex Foreground Residual Bias: As instrumental sensitivity increases, foreground contamination and the accuracy of foreground cleaning methods become dominant sources of systematic error in testing CMB anomalies.

### Rejected Candidates
- [open_question] Constrained vs Unconstrained Anomalies (`constrained-vs-unconstrained-cmbanomalies`) - duplicate_existing: Renamed to align with existing vault naming conventions.

## Datasets

- [[alicpt]]
- [[simons-observatory-lat]]

## Links

- [Abstract](https://arxiv.org/abs/2604.20699)
- [PDF](https://arxiv.org/pdf/2604.20699)

