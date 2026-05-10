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
domain: "social-science-ml"
tags:
  - "conformal-prediction"
  - "fairness"
  - "survey-data"
  - "uncertainty-estimation"
  - "calibration"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-10T05:21:29Z"
created_at: "2026-05-10T05:21:29Z"
---

# Socio-Conformal Calibration in Complex Survey Data: Marginal Validity Is Not Enough for Subgroup Reliability

**Authors**: Amir Rafe, Subasish Das
**Date**: 2026-05-07
**Paper ID**: [arxiv:2605.05562](https://arxiv.org/abs/2605.05562)

## Summary

This paper investigates the reliability of ordinal conformal prediction for AI-attitude forecasting using complex survey data from the Pew American Trends Panel. The authors demonstrate that while standard conformal prediction achieves nominal marginal coverage, it leads to significant weighted subgroup reliability gaps. Furthermore, they find that traditional group-specific (Mondrian) calibration can exacerbate the fairness-efficiency trade-off, with a regularized variant offering only marginal improvements. The study highlights the challenges of achieving subgroup fairness in survey settings and traces these failures to calibration-cell fragmentation.

## Key Contributions

- Demonstrates that standard marginal conformal prediction leads to significant weighted subgroup coverage gaps in survey-based AI-attitude forecasting.
- Shows that Mondrian (group-specific) conformal prediction can worsen the fairness-efficiency trade-off and exacerbate subgroup gaps in complex survey data due to calibration-cell fragmentation.
- Proposes and evaluates a regularized Mondrian comparator that shrinks group thresholds, demonstrating it reduces instability but provides limited improvements in subgroup fairness.

## Open Questions & Future Work

- [[formal-survey-weighted-conformal-calibration]]
- [[adaptive-data-driven-subgroup-calibration]]

## Archivist Review

The paper highlights a specific failure mode (calibration-cell fragmentation) of existing methods (Mondrian conformal prediction) when applied to complex survey data. I approved two open questions that address the theoretical and methodological gaps identified: the need for formal integration of survey weights into conformal inference and the shift from static to adaptive, data-driven subgroup calibration. No new concepts were approved as the proposed methodology (regularized Mondrian) is a incremental modification rather than a distinct, reusable framework.

### Approved Open Questions
- Formal Survey-Weighted Conformal Calibration: This is essential for applying machine learning-based uncertainty quantification reliably in social science and policy-making where survey data are the standard for population inference.
- Adaptive Data-Driven Subgroup Calibration: Moving away from manual group definitions is critical for ensuring fairness and validity guarantees are robust in diverse, real-world population data.

### Rejected Candidates
- [concept] Socio-Conformal Calibration (`socio-conformal-calibration`) - paper_local: The term is paper-local and describes an application context rather than a reusable methodological innovation.

## Links

- [Abstract](https://arxiv.org/abs/2605.05562)
- [PDF](https://arxiv.org/pdf/2605.05562)

