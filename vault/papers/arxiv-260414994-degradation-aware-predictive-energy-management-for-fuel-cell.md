---
# CSL-compatible fields
title: "Degradation-aware Predictive Energy Management for Fuel Cell-Battery Ship Power System with Data-driven Load Forecasting"
author:
  - literal: "Timon Kopka"
  - literal: "Sara Tamburello"
  - literal: "Luca Oneto"
  - literal: "Lindert van Biert"
  - literal: "Henk Polinder"
  - literal: "Andrea Coraddu"
issued:
  date-parts:
    - [2026, 4, 16]
url: "https://arxiv.org/abs/2604.14994"

# Custom fields
paper_id: "2604.14994"
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
skill: "TimeSeriesSkill"
processed_at: "2026-04-17T05:05:15Z"
created_at: "2026-04-17T05:05:15Z"
---

# Degradation-aware Predictive Energy Management for Fuel Cell-Battery Ship Power System with Data-driven Load Forecasting

**Authors**: Timon Kopka, Sara Tamburello, Luca Oneto, Lindert van Biert, Henk Polinder, Andrea Coraddu
**Date**: 2026-04-16
**Paper ID**: [arxiv:2604.14994](https://arxiv.org/abs/2604.14994)

## Summary

This paper addresses the economic optimization of hydrogen-based ship power systems by developing a predictive energy management strategy that accounts for both hydrogen consumption and fuel cell degradation. By utilizing data-driven load forecasting over 15-minute and 1-hour horizons, the proposed control framework significantly outperforms conventional filter-based management strategies. The approach is validated on real-world vessel measurements from a harbor tug, demonstrating substantial simultaneous reductions in operational costs and hardware wear.

## Key Contributions

- Introduces a degradation-aware predictive energy management strategy for hybrid fuel cell-battery ship power systems that co-optimizes for hydrogen consumption and cell aging.
- Demonstrates that integrating 15-minute and 1-hour load forecasting horizons enables significant reductions in both fuel usage and degradation compared to filter-based benchmarks.
- Provides empirical evidence on a virtually retrofitted harbor tug, achieving up to 5.8% hydrogen savings and 36.4% reduction in fuel cell degradation using historical operational measurements.

## Open Questions & Future Work

- [[degradation-aware-maritime-energy-optimization-refinement]]

## Archivist Review

I have approved the open question regarding the refinement of degradation-aware maritime energy management as it identifies specific, structural research bottlenecks (multi-layer optimization vs. inner MPC, variable EOL definitions). I rejected the proposed concept as it describes a domain-specific control framework rather than a generalizable temporal modeling or forecasting concept. No datasets were identified or provided for approval.

### Approved Open Questions
- Advanced Maritime Energy Management Optimization: The transition from static, simplified degradation modeling to dynamic, variable, and system-level optimized degradation management is essential for the economic viability of hydrogen-based ship propulsion. Determining whether multi-layered optimization architectures or variable end-of-life definitions yield significant operational cost reductions is a key open problem in maritime energy management.

### Rejected Candidates
- [concept] Degradation-aware Predictive Energy Management (`degradation-aware-predictive-energy-management`) - paper_local: This is an application-specific control strategy rather than a general, reusable time-series forecasting or modeling mechanism.

## Links

- [Abstract](https://arxiv.org/abs/2604.14994)
- [PDF](https://arxiv.org/pdf/2604.14994)

