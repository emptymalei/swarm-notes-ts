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
processed_at: "2026-04-18T04:51:53Z"
created_at: "2026-04-18T04:51:53Z"
---

# Degradation-aware Predictive Energy Management for Fuel Cell-Battery Ship Power System with Data-driven Load Forecasting

**Authors**: Timon Kopka, Sara Tamburello, Luca Oneto, Lindert van Biert, Henk Polinder, Andrea Coraddu
**Date**: 2026-04-16
**Paper ID**: [arxiv:2604.14994](https://arxiv.org/abs/2604.14994)

## Summary

This paper addresses the economic optimization of hydrogen-based zero-emission ships by proposing a degradation-aware energy management strategy. The approach integrates data-driven load forecasting into a predictive control framework to balance hydrogen consumption with fuel cell longevity. Evaluation on a retrofitted harbor tug demonstrates significant reductions in both fuel usage and cell degradation across different forecast horizons, outperforming conventional filter-based control strategies.

## Key Contributions

- Develops a degradation-aware predictive energy management strategy for hybrid fuel cell-battery ship power systems that simultaneously optimizes for hydrogen consumption and cell degradation.
- Demonstrates that integrating data-driven load forecasting over 15-minute and 1-hour horizons enables significant operational cost reduction, including up to 36.4% lower cell degradation compared to filter-based benchmarks.
- Validates the proposed control strategy using real-world operational measurements from a harbor tug vessel.

## Open Questions & Future Work

- [[degradation-aware-ems-optimization-refinement]]

## Archivist Review

I have approved the open question regarding the refinement of degradation-aware energy management because it identifies a substantial research gap in hierarchical control and component-aging modeling that is relevant to broader time-series and power systems literature. I rejected the proposed 'degradation-aware predictive energy management strategy' as a concept because it is an application-specific system architecture rather than a reusable machine learning abstraction.

### Approved Open Questions
- Refining Degradation-Aware Energy Management: These improvements are critical for enhancing the economic viability and operational life of fuel cell-based maritime power systems by more accurately reflecting the physical and economic reality of component aging.

### Rejected Candidates
- [concept] Degradation-aware predictive energy management strategy (`degradation-aware-predictive-energy-management-strategy`) - paper_local: This is an application-specific framework rather than a general, reusable machine learning method or concept.

## Links

- [Abstract](https://arxiv.org/abs/2604.14994)
- [PDF](https://arxiv.org/pdf/2604.14994)

