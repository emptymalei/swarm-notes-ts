---
# CSL-compatible fields
title: "Probing non-Gaussianity during reheating with SIGW in the LISA band"
author:
  - literal: "Gabriele Perna"
  - literal: "Guillem Domènech"
issued:
  date-parts:
    - [2026, 4, 9]
url: "https://arxiv.org/abs/2604.08493"

# Custom fields
paper_id: "2604.08493"
paper_source: "arxiv"
domain: "time-series"
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
processed_at: "2026-04-11T04:43:21Z"
created_at: "2026-04-11T04:43:21Z"
---

# Probing non-Gaussianity during reheating with SIGW in the LISA band

**Authors**: Gabriele Perna, Guillem Domènech
**Date**: 2026-04-09
**Paper ID**: [arxiv:2604.08493](https://arxiv.org/abs/2604.08493)

## Summary

This paper investigates how non-standard cosmological evolution during the reheating epoch affects the spectrum of scalar-induced gravitational waves (SIGWs). By incorporating primordial non-Gaussianity into the calculation, the authors demonstrate that specific reheating parameters, such as the equation of state w and sound speed cs^2, imprint characteristic signals onto the SIGW spectrum. The study uses Fisher forecasting to show that these unique signatures are potentially detectable by future gravitational wave detectors like LISA, providing a new probe into early Universe physics.

## Key Contributions

- Established the theoretical relationship between non-standard reheating epoch parameters (w, cs^2) and the resulting scalar-induced gravitational wave (SIGW) power spectrum.
- Demonstrated that primordial non-Gaussianity leaves distinctive, potentially detectable spectral features in SIGWs within the frequency range observable by LISA.
- Performed Fisher information forecasts to quantify the parameter estimation sensitivity of future space-based interferometers to reheating dynamics.

## Open Questions & Future Work

- [[non-instantaneous-reheating-sigw-kernel]]
- [[non-perturbative-non-gaussianity-sigw-framework]]

## Archivist Review

I approved two open questions that highlight fundamental theoretical limitations in the modeling of scalar-induced gravitational waves (SIGWs). I rejected no concepts because the paper, while mathematically rigorous in its application of Fisher forecasting, did not propose new reusable architectural patterns or methods that distinguish themselves from established cosmological perturbative frameworks. The approved questions capture specific bottlenecks (analytical kernels and non-perturbative treatments) that will be relevant as the field moves towards high-precision gravitational wave cosmology.

### Approved Open Questions
- SIGW kernels for non-instantaneous reheating: This is a critical technical bottleneck because the current reliance on the instantaneous reheating approximation may lead to inaccurate predictions for signals whose characteristic frequencies are close to the reheating temperature scale.
- Non-perturbative non-Gaussianity for SIGWs: Moving beyond perturbative non-Gaussianity is essential for precise parameter estimation of the early Universe, especially for scenarios where non-linear effects may become significant or where non-local non-Gaussianity is predicted.

### Rejected Candidates
- [open_question] SIGW kernels for non-instantaneous reheating (`non-instantaneous-reheating-sigw-kernel`) - other: Re-submitted with minor edits to improve clarity and reduce reliance on paper-specific context.
- [open_question] Non-perturbative non-Gaussianity for SIGWs (`general-non-gaussianity-sigw-framework`) - other: Re-submitted with minor edits to improve clarity and reduce reliance on paper-specific context.

## Links

- [Abstract](https://arxiv.org/abs/2604.08493)
- [PDF](https://arxiv.org/pdf/2604.08493)

