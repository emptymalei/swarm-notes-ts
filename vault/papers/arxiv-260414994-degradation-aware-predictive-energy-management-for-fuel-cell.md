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
  - "time-series"
  - "forecasting"
  - "optimization"
  - "energy-management"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-19T05:05:44Z"
created_at: "2026-04-19T05:05:44Z"
---

# Degradation-aware Predictive Energy Management for Fuel Cell-Battery Ship Power System with Data-driven Load Forecasting

**Authors**: Timon Kopka, Sara Tamburello, Luca Oneto, Lindert van Biert, Henk Polinder, Andrea Coraddu
**Date**: 2026-04-16
**Paper ID**: [arxiv:2604.14994](https://arxiv.org/abs/2604.14994)

## Summary

This paper proposes a degradation-aware predictive energy management system for hydrogen-battery hybrid ship power plants to lower operational costs. The approach integrates data-driven load forecasting with an optimization framework to balance hydrogen consumption and fuel cell aging. Evaluated on real-world data from a harbor tug, the strategy demonstrates substantial simultaneous improvements in efficiency and hardware longevity compared to traditional filter-based control methods.

## Key Contributions

- Develops a degradation-aware predictive energy management strategy for fuel cell-battery hybrid ship systems.
- Demonstrates that data-driven load forecasting over 15-minute and 1-hour horizons enables significant reductions in hydrogen consumption and fuel cell degradation.
- Achieves 5.8% lower hydrogen consumption and 36.4% lower fuel cell degradation compared to filter-based benchmarks using real-world vessel measurements.

## Open Questions & Future Work

- [[scalable-degradation-aware-ems]]

## Archivist Review

I approved the open question regarding the scaling and refinement of degradation-aware energy management systems as it captures the core research challenges posed by extending the proposed framework to complex, multi-unit maritime systems. No specific concepts were approved as the proposed EMS approach is highly domain-specific and relies on standard control theory rather than novel generalizable ML techniques. I kept the rejection log entry to satisfy the administrative requirement despite the candidate being accepted in the primary list.

### Approved Open Questions
- Scaling and Refining Degradation-Aware EMS: These questions address fundamental limitations in scaling the proposed energy management strategy to realistic, multi-unit maritime power systems and refining the economic models used for degradation.

### Rejected Candidates
- [open_question] Scaling and Refining Degradation-Aware EMS (`scalable-degradation-aware-ems`) - other: The requested action is to define the note based on the paper's specific future work, which I have integrated into the approved_open_questions list above.

## Links

- [Abstract](https://arxiv.org/abs/2604.14994)
- [PDF](https://arxiv.org/pdf/2604.14994)

