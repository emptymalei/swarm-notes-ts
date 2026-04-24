---
# CSL-compatible fields
title: "Forecasts of CMB $E$-mode anomalies for AliCPT-1"
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
domain: "astrophysics"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-04-24T05:09:34Z"
created_at: "2026-04-24T05:09:34Z"
---

# Forecasts of CMB $E$-mode anomalies for AliCPT-1

**Authors**: Jiazheng Dou, Wen Zhao
**Date**: 2026-04-22
**Paper ID**: [arxiv:2604.20699](https://arxiv.org/abs/2604.20699)

## Summary

This paper evaluates the performance of the Ali CMB Polarization Telescope (AliCPT) in detecting large-scale cosmic microwave background (CMB) E-mode anomalies, which provide an independent cross-check to existing temperature-based findings. Using 1000 simulated datasets processed via the NILC method, the authors analyze four distinct anomaly estimators: dipole modulation, large-angle correlation deficits, quadrupole-octopole alignment, and point-parity asymmetry. The results indicate that while AliCPT alone suffers from sky-coverage limitations, integrating it with the Simons Observatory (SO) restores performance toward near-cosmic-variance benchmarks. This joint approach significantly enhances the detectability of injected modulation signals, suggesting a robust framework for future anomaly investigations in polarized CMB data.

## Key Contributions

- Forecasts AliCPT's ability to detect large-scale CMB E-mode anomalies using 1000 NILC-processed simulations.
- Validates that the combined AliCPT and Simons Observatory (SO) dataset can detect dipole modulation with amplitude Ad=0.07 at a 99% confidence level.
- Demonstrates that combining AliCPT with SO mitigates systematic biases and uncertainty inflation associated with AliCPT's limited sky coverage for quadrupole-octopole alignment and point-parity asymmetry statistics.

## Open Questions & Future Work

- [[constrained-vs-unconstrained-cmb-anomaly-testing]]
- [[residual-foreground-impact-on-cmb-anomalies]]

## Archivist Review

The paper provides a standard forecasting analysis for a specific telescope (AliCPT). The proposed concepts were rejected as they represent standard astrophysical methods for CMB analysis rather than generalizable ML concepts. The two open questions are approved as they address fundamental methodological bottlenecks in testing CMB anomalies that apply to future experiments beyond the one discussed here.

### Approved Open Questions
- Constrained vs. Unconstrained CMB Anomaly Testing: This is critical for distinguishing whether CMB anomalies represent genuine beyond-standard-model physics or are simply statistical outliers within the ΛCDM model; the choice of simulation ensemble fundamentally alters the statistical interpretation of future data.
- Foreground Residuals in Large-Scale Anomalies: Large-scale anomalies reside at the lowest multipoles where both cosmic variance and residual foregrounds are most significant; failing to model these residuals can lead to false claims of anomaly detection.

## Links

- [Abstract](https://arxiv.org/abs/2604.20699)
- [PDF](https://arxiv.org/pdf/2604.20699)

