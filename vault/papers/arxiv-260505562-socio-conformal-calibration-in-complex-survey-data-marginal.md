---
# CSL-compatible fields
title: "Socio-Conformal Calibration in Complex Survey Data: Marginal Validity Is Not Enough for Subgroup Reliability"
author:
  - literal: "Amir Rafe"
  - literal: "Subasish Das"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2605.05562"

# Custom fields
paper_id: "2605.05562"
paper_source: "arxiv"
domain: "nlp"
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
processed_at: "2026-05-09T05:13:25Z"
created_at: "2026-05-09T05:13:25Z"
---

# Socio-Conformal Calibration in Complex Survey Data: Marginal Validity Is Not Enough for Subgroup Reliability

**Authors**: Amir Rafe, Subasish Das
**Date**: 2026-05-07
**Paper ID**: [arxiv:2605.05562](https://arxiv.org/abs/2605.05562)

## Summary

This paper investigates the reliability of ordinal conformal prediction for survey-based social measurement, specifically focusing on subgroup coverage in complex social data. Through empirical evaluation on the Pew American Trends Panel, the authors demonstrate that traditional marginal validity is insufficient for ensuring subgroup reliability and that group-specific calibration (Mondrian) can paradoxically degrade fairness-efficiency trade-offs. The authors further analyze the failure mechanisms of these methods and propose a regularized comparator to improve calibration stability.

## Key Contributions

- Demonstrates that standard marginal conformal prediction fails to guarantee subgroup reliability in survey-based AI-attitude forecasting, with subgroup coverage gaps reaching 13 percentage points.
- Shows that naive Mondrian (group-specific) conformal calibration can exacerbate the fairness-efficiency trade-off in survey datasets, increasing both weighted set size and subgroup coverage instability.
- Introduces a regularized Mondrian conformal comparator that shrinks group thresholds toward the global quantile, offering improved stability but highlighting the inherent difficulty of achieving subgroup fairness in fragmented calibration cells.

## Open Questions & Future Work

- [[survey-weighted-conformal-calibration-theory]]
- [[adaptive-subgroup-selection-conformal-prediction]]

## Archivist Review

The paper highlights significant challenges in extending standard conformal prediction to complex survey data, demonstrating that aggregate marginal validity is insufficient for subgroup fairness. I have approved two open research questions that target the theoretical foundations of integrating survey weights into calibration and the need for data-driven, adaptive subgroup definitions. No concepts were approved as the methods described (Mondrian, regularized comparators) are well-established or minor modifications in this context.

### Approved Open Questions
- Survey-weighted conformal calibration theory: Without formal theoretical grounding for survey-weighted conformal calibration, researchers lack clear guidance on how to integrate survey design into uncertainty quantification, leading to potentially misleading confidence sets for public policy assessments.
- Adaptive subgroup selection methods: Addressing fixed subgroup limitations is essential because predefined demographic categories may not align with the actual dimensions where model uncertainty or disparate impact are concentrated.

## Links

- [Abstract](https://arxiv.org/abs/2605.05562)
- [PDF](https://arxiv.org/pdf/2605.05562)

