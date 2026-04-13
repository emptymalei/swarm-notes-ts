---
# CSL-compatible fields
title: "Analytic compression of the effective field theory of the Lyman-alpha forest"
author:
  - literal: "N. G. Karaçaylı"
  - literal: "M. Ivanov"
  - literal: "R. de Belsunce"
  - literal: "C. Ravoux"
  - literal: "J. M. Sexton"
  - literal: "Z. Lukić"
issued:
  date-parts:
    - [2026, 4, 10]
url: "https://arxiv.org/abs/2604.09407"

# Custom fields
paper_id: "2604.09407"
paper_source: "arxiv"
domain: "physics"
tags:
  - "cosmology"
  - "effective-field-theory"
  - "parameter-inference"
  - "lyman-alpha-forest"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-04-13T05:08:53Z"
created_at: "2026-04-13T05:08:53Z"
---

# Analytic compression of the effective field theory of the Lyman-alpha forest

**Authors**: N. G. Karaçaylı, M. Ivanov, R. de Belsunce, C. Ravoux, J. M. Sexton, Z. Lukić
**Date**: 2026-04-10
**Paper ID**: [arxiv:2604.09407](https://arxiv.org/abs/2604.09407)

## Summary

This paper presents an analytic compression technique to improve the efficiency of the effective field theory (EFT) framework for modeling the 1D Lyman-alpha flux power spectrum. By using Fisher-informed linear compression of the EFT parameter space, the authors enable analytic template marginalization, which drastically reduces the computational overhead typically associated with likelihood evaluations in high-resolution structure formation probes. Evaluation on DESI DR1 data demonstrates that this compressed model saturates cosmological constraining power with only six templates, providing robust estimates of power spectrum parameters comparable to expensive emulator-based methods.

## Key Contributions

- Introduces an analytic compression method for the Lyman-alpha forest effective field theory (EFT) using Fisher matrix formalism and linear template marginalization.
- Demonstrates that cosmological parameter constraints saturate using a small, compressed set of EFT templates: the linear bias, two leading-order 1D stochastic terms, and three principal combinations of higher-order EFT terms.
- Achieves forecasted precision of 10% for power spectrum amplitude (Δ²ₚ) and 2.0% for the slope (nₚ) at the pivot scale (kₚ=0.7 Mpc⁻¹), matching the performance of computationally intensive emulator-based approaches.

## Open Questions & Future Work

- [[breaking-eft-lyman-alpha-degeneracies]]
- [[robust-eft-model-compression]]

## Archivist Review

The paper introduces a method for analytic compression of EFT parameters in the Lyman-alpha forest. I have approved two open questions that highlight substantial research bottlenecks in breaking parameter degeneracies and maintaining compression robustness in non-fiducial parameter regimes. No concepts were approved as the proposed compression technique is a specific application of Fisher-based model reduction rather than a broadly reusable architectural pattern at this time.

### Approved Open Questions
- Breaking EFT Lyman-alpha Degeneracies: Breaking these degeneracies is critical for maximizing the cosmological constraining power of the Lyman-alpha forest and for moving beyond current limitations where parameter space size limits the reliability of inference.
- Robust EFT Model Compression: Ensuring the robustness of the compression technique across a wider range of parameter space is essential for reliable cosmological inference using high-precision survey data.

### Rejected Candidates
- [open_question] Breaking EFT Lyman-alpha Degeneracies (`eft-lyman-alpha-degeneracy-and-parameter-reduction`) - other: Renamed to align with vault naming conventions.

## Links

- [Abstract](https://arxiv.org/abs/2604.09407)
- [PDF](https://arxiv.org/pdf/2604.09407)

