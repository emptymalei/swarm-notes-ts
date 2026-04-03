---
# CSL-compatible fields
title: "Application of parametric Shallow Recurrent Decoder Network to magnetohydrodynamic flows in liquid metal blankets of fusion reactors"
author:
  - literal: "M. Lo Verso"
  - literal: "C. Introini"
  - literal: "E. Cervi"
  - literal: "L. Savoldi"
  - literal: "J. N. Kutz"
  - literal: "A. Cammi"
issued:
  date-parts:
    - [2026, 4, 2]
url: "https://arxiv.org/abs/2604.02139"

# Custom fields
paper_id: "2604.02139"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "shred"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-03T05:19:03Z"
created_at: "2026-04-03T05:19:03Z"
---

# Application of parametric Shallow Recurrent Decoder Network to magnetohydrodynamic flows in liquid metal blankets of fusion reactors

**Authors**: M. Lo Verso, C. Introini, E. Cervi, L. Savoldi, J. N. Kutz, A. Cammi
**Date**: 2026-04-02
**Paper ID**: [arxiv:2604.02139](https://arxiv.org/abs/2604.02139)

## Summary

This paper presents a data-driven approach to reconstruct high-dimensional magnetohydrodynamic (MHD) flows in fusion reactor blankets using the SHallow REcurrent Decoder (SHRED) architecture. By combining Singular Value Decomposition (SVD) for dimensionality reduction with SHRED, the model achieves accurate spatio-temporal state reconstruction from sparse time-series measurements. The methodology demonstrates strong generalization across various parametric magnetic field scenarios and shows potential for real-time monitoring and diagnostics in fusion systems.

## Key Contributions

- Introduces the SHRED architecture for reconstructing full MHD flow fields in liquid metal reactor blankets from sparse sensor data.
- Demonstrates robust generalization of SHRED to unseen parametric magnetic field configurations, including intensity, orientation, and temporal variations.
- Validates the capability of SHRED to infer complex time-dependent magnetic field dynamics solely from localized temperature sensor measurements.

## Open Questions & Future Work

- [[state-estimator-closed-loop-integration]]

## Key Concepts

- [[shred]]: A neural network architecture combining dimensionality reduction and recurrent decoders to reconstruct high-dimensional spatiotemporal states from sparse time-series measurements.

## Archivist Review

Approved the SHRED architecture as it provides a distinct, reusable mechanism for sparse sensor-to-field reconstruction. I consolidated the open question on integration into a more general form applicable to broader state estimation literature, while rejecting the scaling question as a routine increase in problem size.

### Approved Concepts
- SHallow REcurrent Decoder (SHRED): SHRED is a specialized architecture for high-dimensional state reconstruction from sparse temporal sensors, offering a reusable approach for spatiotemporal modeling in physics-informed contexts.

### Approved Open Questions
- State Estimator Closed-Loop Integration: This represents the critical gap between passive diagnostic monitoring and active physical system control.

### Rejected Candidates
- [open_question] Scalability to full blanket geometries (`shred-scalability-to-full-blanket-geometries`) - low_impact: This is a standard scaling challenge (larger data/compute) rather than an architectural or algorithmic bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2604.02139)
- [PDF](https://arxiv.org/pdf/2604.02139)

