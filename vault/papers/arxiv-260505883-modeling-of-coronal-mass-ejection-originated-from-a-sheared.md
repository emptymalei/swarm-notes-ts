---
# CSL-compatible fields
title: "Modeling of Coronal Mass Ejection Originated from a Sheared Arcade of Realistic Active-Region Scale and Its Propagation in the Heliosphere: Methodology"
author:
  - literal: "Chaowei Jiang"
  - literal: "Xueshang Feng"
  - literal: "Liping Yang"
  - literal: "Huichao Li"
  - literal: "Jinhan Guo"
  - literal: "Pingbing Zuo"
  - literal: "Yi Wang"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2605.05883"

# Custom fields
paper_id: "2605.05883"
paper_source: "arxiv"
domain: "physics-simulations-ml"
tags:
  - "physics-informed-ml"
  - "space-weather-forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  - "semi-relativistic-boris-correction-for-mhd"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-10T05:20:00Z"
created_at: "2026-05-10T05:20:00Z"
---

# Modeling of Coronal Mass Ejection Originated from a Sheared Arcade of Realistic Active-Region Scale and Its Propagation in the Heliosphere: Methodology

**Authors**: Chaowei Jiang, Xueshang Feng, Liping Yang, Huichao Li, Jinhan Guo, Pingbing Zuo, Yi Wang
**Date**: 2026-05-07
**Paper ID**: [arxiv:2605.05883](https://arxiv.org/abs/2605.05883)

## Summary

This paper presents an end-to-end magnetohydrodynamic (MHD) modeling methodology for coronal mass ejections (CMEs) that spans from the solar active region to 1.5 au. To balance high resolution with computational efficiency, the authors utilize a nested, block-structured adaptive mesh refinement strategy and a novel semi-relativistic Boris correction to handle high magnetic field strengths. The approach successfully simulates the initiation, acceleration, and propagation of CMEs, yielding synthetic observations that align with physical expectations and demonstrating potential for operational space weather forecasting.

## Key Contributions

- Introduced a nested MHD modeling framework coupling three domains from solar surface to 1.5 au, achieving ~700 km resolution in the low corona.
- Implemented a semi-relativistic Boris correction to simulate realistic 10^3 G magnetic fields without requiring excessively small time steps.
- Demonstrated an end-to-end CME simulation from energy buildup to 1 au arrival, capturing characteristic three-part structures and in-situ shock/B_z signatures.

## Open Questions & Future Work

- [[realistic-thermodynamics-in-solar-wind-modeling]]
- [[data-driven-mhd-cme-modeling]]

## Key Concepts

- [[semi-relativistic-boris-correction-for-mhd]]: A numerical technique for handling extreme magnetic field strengths in MHD simulations by limiting the effective speed of light to prevent prohibitively small time steps.

## Archivist Review

I approved the semi-relativistic Boris correction as it is a specific, reusable numerical technique for MHD stability. I also approved two high-level research challenges concerning thermodynamic realism and data-driven assimilation, as these represent fundamental bottlenecks for the field of space weather forecasting. Other candidates were rejected to maintain focus on high-impact, reusable primitives.

### Approved Concepts
- Semi-relativistic Boris Correction for MHD: Enables high-fidelity magnetohydrodynamic simulations in regions with extreme magnetic field strengths by decoupling simulation time-step constraints from the Alfven speed.

### Approved Open Questions
- Advanced Solar Wind Thermodynamics: Thermodynamic realism is crucial for reproducing the structure and speed of the solar wind, which directly impacts the predicted arrival times and impact strengths of CMEs.
- Data-Driven CME Modeling: Data-driven modeling is essential for moving from theoretical studies to reliable operational space weather forecasting that reflects actual solar conditions.

## Links

- [Abstract](https://arxiv.org/abs/2605.05883)
- [PDF](https://arxiv.org/pdf/2605.05883)

