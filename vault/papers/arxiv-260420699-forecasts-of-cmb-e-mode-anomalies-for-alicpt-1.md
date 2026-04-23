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
processed_at: "2026-04-23T05:05:42Z"
created_at: "2026-04-23T05:05:42Z"
---

# Forecasts of CMB $E$-mode anomalies for AliCPT-1

**Authors**: Jiazheng Dou, Wen Zhao
**Date**: 2026-04-22
**Paper ID**: [arxiv:2604.20699](https://arxiv.org/abs/2604.20699)

## Summary

This paper evaluates the potential of the AliCPT ground-based CMB experiment to detect large-scale statistical anomalies in $E$-mode polarization, addressing the limitations of temperature-only analyses. Using 1000 NILC-processed simulations, the authors test four anomaly estimators across two noise levels and a joint configuration with the Simons Observatory (SO). The results indicate that while AliCPT has limitations due to sky coverage, the combination with SO significantly improves detection robustness, approaching the performance of full-sky experiments for anomaly investigation.

## Key Contributions

- Forecasts the capability of the AliCPT experiment to detect large-scale CMB E-mode statistical anomalies using 1000 simulated datasets.
- Evaluates four specific anomaly estimators: dipole modulation, lack of large-angle correlations, quadrupole-octopole alignment, and point-parity asymmetry.
- Demonstrates that while AliCPT alone suffers from sky coverage limitations, the joint AliCPT+SO LAT configuration achieves a near-cosmic-variance benchmark for detecting injected E-mode dipole modulation (Ad=0.07) at 99% confidence.

## Open Questions & Future Work

- [[constrained-vs-unconstrained-cmb-anomaly-testing]]

## Archivist Review

I have reviewed the candidate open question regarding constrained vs. unconstrained simulations for CMB anomaly testing, which addresses a significant bottleneck in validating findings against the 'fluke' hypothesis in cosmology. I have rejected all concept candidates as they refer to standard, well-established statistical tests within the domain of cosmology rather than reusable machine learning architectures or methodologies. No datasets were proposed or deemed critical for standalone archival.

### Approved Open Questions
- Constrained vs. Unconstrained CMB Anomaly Testing: Determining whether E-mode polarization inherits the temperature anomalies is critical for rejecting or supporting the 'fluke' hypothesis, as unconstrained simulations may not accurately capture the statistical expectations if the underlying physics is connected across temperature and polarization channels.

### Rejected Candidates
- [concept] Dipole modulation estimator (`dipole-modulation-estimator`) - not_novel: This is a standard statistical test in CMB physics rather than a novel, reusable ML method.
- [concept] Lack of large-angle correlations (`lack-of-large-angle-correlations`) - not_novel: This is a well-known CMB statistical anomaly, not a reusable ML concept or architecture.
- [concept] Quadrupole-octopole alignment (`quadrupole-octopole-alignment`) - not_novel: This is a well-known CMB anomaly metric.
- [concept] Point-parity asymmetry (`point-parity-asymmetry`) - not_novel: This is a well-known CMB anomaly metric.

## Links

- [Abstract](https://arxiv.org/abs/2604.20699)
- [PDF](https://arxiv.org/pdf/2604.20699)

