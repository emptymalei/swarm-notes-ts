---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Strong Field Gravitational Lensing in Full Wave Optics"
description: "This paper presents a rigorous study of strong field gravitational lensing of signals from compact binaries near massive black holes using a full wave optics approach. By moving beyond geometric optics and the thin-lens approximation, the authors calculate amplification factors that account for diffraction and interference effects, which are significant when the wavelength is comparable to the lens's gravitational radius. A major finding is that the anisotropic quadrupolar emission of edge-on binaries shifts the peak amplification away from the optical axis, breaking the axisymmetry typically expected in non-spinning systems. The results indicate that simple point-mass models are insufficient for accurate strong-field forecasting, emphasizing the need for wave-optics-based templates in future gravitational wave observations."
resource: "https://arxiv.org/abs/2610.18958"
tags:
  - "gravitational-lensing"
  - "gravitational-wave-analysis"
  - "astrophysics"
  - "physics"
  - "strong-lensing"
timestamp: "2026-10-18T00:52:34Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "João Sieiro dos Santos"
  - literal: "Luka Vujeva"
issued:
  date-parts:
    - [2026, 10, 13]

# Domain-specific custom fields
paper_id: "2610.18958"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "wave-optics-lensing"
    description: "A framework for calculating gravitational lensing amplification that accounts for wave-like properties such as interference and diffraction, essential when geometric optics approximations fail."
datasets:
  []
open_questions:
  []
skill: "GeneralMLSkill"
processed_at: "2026-10-18T00:52:34Z"
created_at: "2026-10-18T00:52:34Z"
---

# Strong Field Gravitational Lensing in Full Wave Optics

**Authors**: João Sieiro dos Santos, Luka Vujeva
**Date**: 2026-10-13
**Paper ID**: [arxiv:2610.18958](https://arxiv.org/abs/2610.18958)

## Summary

This paper presents a rigorous study of strong field gravitational lensing of signals from compact binaries near massive black holes using a full wave optics approach. By moving beyond geometric optics and the thin-lens approximation, the authors calculate amplification factors that account for diffraction and interference effects, which are significant when the wavelength is comparable to the lens's gravitational radius. A major finding is that the anisotropic quadrupolar emission of edge-on binaries shifts the peak amplification away from the optical axis, breaking the axisymmetry typically expected in non-spinning systems. The results indicate that simple point-mass models are insufficient for accurate strong-field forecasting, emphasizing the need for wave-optics-based templates in future gravitational wave observations.

## Key Contributions

- Developed a perturbative framework to calculate full wave optics amplification factors for compact binaries lensed by massive (Schwarzschild and Kerr) black holes.
- Discovered that anisotropic quadrupolar emission from edge-on binaries causes the peak lensing amplification to shift away from perfect source-lens-observer alignment.
- Identified a universal frequency dependence in the amplification factor that persists into the wave optics regime across both Schwarzschild and Kerr lens configurations.
- Demonstrated that standard point-mass lens models and geometric optics approximations produce significant inaccuracies (~10% error or more) in strong-field lensing scenarios.

## Limitations

The study's findings on universal frequency dependence are primarily restricted to the equatorial plane near the optical axis, and the agreement with ray-tracing is limited to approximately 10% in more complex configurations.

## Key Concepts

- [[wave-optics-lensing]]: A framework for calculating gravitational lensing amplification that accounts for wave-like properties such as interference and diffraction, essential when geometric optics approximations fail.

## Archivist Review

I approved the 'Wave Optics Lensing' concept as it represents the core theoretical framework and a significant shift in gravitational wave modeling from geometric optics. The other candidates were rejected because they described specific physical results (paper-local) or represented generic statistical concerns (parameter estimation bias) rather than distinct, reusable research concepts.

### Approved Concepts
- Wave Optics Lensing: Standard gravitational lensing often assumes geometric optics, but for gravitational waves with wavelengths comparable to the lens's size, wave effects like diffraction and interference become dominant.

### Rejected Candidates
- [concept] Quadrupolar Emission Anisotropy Shift (`quadrupolar-emission-anisotropy-shift`) - paper_local: This is a specific physical finding or phenomenon discovered in this study rather than a broadly applicable methodology or architectural pattern.
- [open_question] Parameter Estimation Bias from Simplified Lens Models (`lensing-model-parameter-bias`) - generic: The impact of model mismatch on parameter estimation is a generic problem in statistical inference and not an unresolved mechanism specific to this paper's novelty.
- [open_question] Impact of Binary Eccentricity on Wave Optics Signatures (`eccentricity-impact-wave-lensing`) - paper_local: Adding additional physical parameters like eccentricity to an existing model is a routine direction for future work.

## Links

- [Abstract](https://arxiv.org/abs/2610.18958)
- [PDF](https://arxiv.org/pdf/2610.18958)

