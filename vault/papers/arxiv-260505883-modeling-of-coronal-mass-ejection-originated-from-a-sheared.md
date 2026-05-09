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
domain: "physics-informed-modeling"
tags:
  - "physics-informed-modeling"
  - "time-series-forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  - "semi-relativistic-boris-correction-for-mhd"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-09T05:11:52Z"
created_at: "2026-05-09T05:11:52Z"
---

# Modeling of Coronal Mass Ejection Originated from a Sheared Arcade of Realistic Active-Region Scale and Its Propagation in the Heliosphere: Methodology

**Authors**: Chaowei Jiang, Xueshang Feng, Liping Yang, Huichao Li, Jinhan Guo, Pingbing Zuo, Yi Wang
**Date**: 2026-05-07
**Paper ID**: [arxiv:2605.05883](https://arxiv.org/abs/2605.05883)

## Summary

This paper presents an end-to-end computational framework for modeling coronal mass ejections (CMEs) from their active-region origins to their propagation through the heliosphere. By coupling nested magnetohydrodynamic simulations with block-structured adaptive mesh refinement and a semi-relativistic Boris correction, the model resolves active-region scales at high magnetic field strengths with significant computational efficiency. The approach successfully captures critical physical processes, including pre-eruption energy buildup, magnetic reconnection triggering, and shock formation, providing a viable two-day lead time for forecasting CME arrivals.

## Key Contributions

- Introduces an end-to-end CME modeling methodology using three coupled nested magnetohydrodynamic simulations covering from the solar surface to 1.5 AU.
- Achieves sub-megameter resolution (700 km) in the corona while maintaining global computational efficiency through block-structured adaptive mesh refinement.
- Demonstrates 2-day lead-time predictive capability for CME arrival at 1 AU by simulating initiation, eruption, and propagation on a standard compute cluster.

## Open Questions & Future Work

- [[realistic-thermodynamics-cme-simulations]]

## Key Concepts

- [[semi-relativistic-boris-correction-for-mhd]]: A numerical stability technique that utilizes semi-relativistic modifications to the Boris integrator to handle extreme magnetic field strengths without forcing prohibitively small computational time steps.

## Archivist Review

I have approved the Boris correction method as it provides a reusable, domain-specific numerical stability technique for high-intensity MHD simulations. The open question on thermodynamic modeling addresses a significant bottleneck in physical fidelity for solar forecasting models. No other candidates met the high selectivity threshold for permanent vault inclusion.

### Approved Concepts
- Semi-relativistic Boris Correction for MHD: Enables high-fidelity magnetohydrodynamic simulations of solar coronal phenomena by bypassing severe stability constraints in strong-field regimes.

### Approved Open Questions
- Advanced Thermodynamic Modeling in MHD: Accurate thermodynamics are essential for predicting the speed, density, and magnetic field characteristics of the solar wind, which directly influence the impact of CMEs on Earth. Simplified polytropic indices are a known limitation in the existing methodology for reproducing observed solar wind properties.

## Links

- [Abstract](https://arxiv.org/abs/2605.05883)
- [PDF](https://arxiv.org/pdf/2605.05883)

