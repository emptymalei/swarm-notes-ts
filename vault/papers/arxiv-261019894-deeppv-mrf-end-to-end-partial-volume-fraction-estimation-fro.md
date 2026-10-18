---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "DeepPV-MRF: End-to-End Partial-Volume Fraction Estimation from MR Fingerprinting Time Series"
description: "DeepPV-MRF is an end-to-end deep learning framework designed to estimate voxel-wise tissue fractions (CSF, gray matter, white matter) directly from raw Magnetic Resonance Fingerprinting (MRF) time series. By using a cascaded spatial-temporal network, the method bypasses the traditional step of creating intermediate T1/T2 parametric maps, which often introduces error propagation. The model demonstrates superior performance over traditional dictionary matching and pseudoinverse methods, achieving significantly lower mean absolute errors and higher structural similarity in both simulated and in vivo human brain data."
resource: "https://arxiv.org/abs/2610.19894"
tags:
  - "time-series"
  - "computer-vision"
  - "medical-ai"
  - "u-net"
  - "biomedical-signal-processing"
  - "spatiotemporal-modeling"
  - "signal-processing"
  - "healthcare"
timestamp: "2026-10-18T00:40:47Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Tianyi Ding"
  - literal: "Yang Gao"
  - literal: "Zhuang Xiong"
  - literal: "Feng Liu"
  - literal: "Martijn A. Cloos"
  - literal: "Jin Jin"
  - literal: "Hongfu Sun"
issued:
  date-parts:
    - [2026, 10, 14]

# Domain-specific custom fields
paper_id: "2610.19894"
paper_source: "arxiv"
architectures:
  - "u-net"
concepts:
  - name: "deeppv-mrf"
    description: "An end-to-end cascaded spatial-temporal network that estimates subvoxel tissue fractions directly from Magnetic Resonance Fingerprinting (MRF) time-series signals."
datasets:
  []
open_questions:
  - name: "mrf-hardware-generalization"
    description: "How do end-to-end models like DeepPV-MRF generalize across scanners from different manufacturers and varying field strengths (e.g., 1.5T vs 3.0T) without requiring extensive site-specific retraining or simulation data?"
  - name: "mrf-artifact-robustness"
    description: "Can end-to-end tissue fraction estimation frameworks incorporate integrated artifact compensation or uncertainty quantification to handle non-ideal physical acquisition conditions where traditional intermediate parametric map correction is bypassed?"
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T00:40:47Z"
created_at: "2026-10-18T00:40:47Z"
---

# DeepPV-MRF: End-to-End Partial-Volume Fraction Estimation from MR Fingerprinting Time Series

**Authors**: Tianyi Ding, Yang Gao, Zhuang Xiong, Feng Liu, Martijn A. Cloos, Jin Jin, Hongfu Sun
**Date**: 2026-10-14
**Paper ID**: [arxiv:2610.19894](https://arxiv.org/abs/2610.19894)

## Summary

DeepPV-MRF is an end-to-end deep learning framework designed to estimate voxel-wise tissue fractions (CSF, gray matter, white matter) directly from raw Magnetic Resonance Fingerprinting (MRF) time series. By using a cascaded spatial-temporal network, the method bypasses the traditional step of creating intermediate T1/T2 parametric maps, which often introduces error propagation. The model demonstrates superior performance over traditional dictionary matching and pseudoinverse methods, achieving significantly lower mean absolute errors and higher structural similarity in both simulated and in vivo human brain data.

## Key Contributions

- Developed DeepPV-MRF, the first end-to-end framework for direct tissue fraction estimation from raw magnetic resonance fingerprinting (MRF) signals, avoiding intermediate T1/T2 maps.
- Implemented a cascaded spatial-temporal network architecture that leverages temporal encoding for signal characteristics and a spatial U-Net for subvoxel refinement.
- Achieved significant error reduction in tissue fraction estimation, with CSF/WM/GM mean absolute errors dropping from ~0.12-0.29 in dictionary matching to ~0.04-0.07.
- Demonstrated improved anatomical sharpens and transition smoothness in in vivo brain imaging compared to pseudoinverse and dictionary matching baselines.

## Limitations

The framework requires further validation on larger cohorts and clinical settings before deployment.

## Open Questions & Future Work

- [[mrf-hardware-generalization]]
- [[mrf-artifact-robustness]]

## Key Concepts

- [[deeppv-mrf]]: An end-to-end cascaded spatial-temporal network that estimates subvoxel tissue fractions directly from Magnetic Resonance Fingerprinting (MRF) time-series signals.

## Archivist Review

Approved DeepPV-MRF as a distinct end-to-end spatiotemporal architecture for MRF. Approved two open questions regarding hardware generalization and artifact robustness, as these are the primary bottlenecks for the clinical deployment of such end-to-end signal-processing models. Rejected generic medical imaging tasks and established physics simulation techniques.

### Approved Concepts
- DeepPV-MRF: DeepPV-MRF represents a transition from traditional multi-stage pipelines (dictionary matching followed by segmentation) to an end-to-end spatiotemporal mapping, reducing error propagation from intermediate parametric maps.

### Approved Open Questions
- Cross-Scanner Model Generalization: Clinical adoption of quantitative MRI models depends on their ability to produce consistent tissue fractions across the diverse hardware found in diagnostic centers.
- Robustness to Field Inhomogeneities: Maintaining accuracy in the presence of physical artifacts is essential for moving from controlled research environments to real-world clinical diagnosis.

### Rejected Candidates
- [concept] Partial-Volume Fraction Estimation (`partial-volume-fraction-estimation`) - not_novel: This is a standard task in medical imaging and magnetic resonance imaging, not a novel methodology or concept introduced by the paper.
- [concept] Bloch Simulations (`bloch-simulations`) - not_novel: Bloch simulations are a foundational physics technique in MRI used for decades and do not warrant a new vault entry in this context.

## Links

- [Abstract](https://arxiv.org/abs/2610.19894)
- [PDF](https://arxiv.org/pdf/2610.19894)

