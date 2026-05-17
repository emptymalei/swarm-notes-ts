---
# CSL-compatible fields
title: "DT-Transformer: A Foundation Model for Disease Trajectory Prediction on a Real-world Health System"
author:
  - literal: "Yunying Zhu"
  - literal: "Andrew R Weckstein"
  - literal: "Kueiyu Joshua Lin"
  - literal: "Jie Yang"
issued:
  date-parts:
    - [2026, 5, 14]
url: "https://arxiv.org/abs/2605.14227"

# Custom fields
paper_id: "2605.14227"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "dt-transformer"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-17T05:25:26Z"
created_at: "2026-05-17T05:25:26Z"
---

# DT-Transformer: A Foundation Model for Disease Trajectory Prediction on a Real-world Health System

**Authors**: Yunying Zhu, Andrew R Weckstein, Kueiyu Joshua Lin, Jie Yang
**Date**: 2026-05-14
**Paper ID**: [arxiv:2605.14227](https://arxiv.org/abs/2605.14227)

## Summary

DT-Transformer is a foundation model designed for large-scale disease trajectory prediction using multi-hospital electronic health record (EHR) data. By training on 57.1 million entries from 1.7 million patients, the model captures clinical complexities often missed in smaller research cohorts. Empirical evaluation across 896 disease categories demonstrates strong predictive discrimination, with a median age- and sex-stratified AUC of 0.871, supporting the viability of system-scale training for clinical forecasting.

## Key Contributions

- Introduces DT-Transformer, a foundation model for disease trajectory prediction trained on 57.1 million EHR entries from 1.7 million patients.
- Demonstrates superior clinical forecasting performance, achieving a median age- and sex-stratified AUC of 0.871 for next-event prediction across 896 disease categories.
- Validates the efficacy of health system-scale training to improve generalizability across heterogeneous multi-hospital clinical environments.

## Open Questions & Future Work

- [[cross-institutional-data-fragmentation-impact]]
- [[optimal-temporal-encoding-ehr]]

## Key Concepts

- [[dt-transformer]]: A foundation model architecture designed for predicting patient disease trajectories from large-scale, multi-hospital electronic health record systems.

## Archivist Review

I approved the DT-Transformer architecture as a representative instance of healthcare-domain foundation modeling and two open questions regarding data observability and temporal representation in clinical sequences. These items are specific, reusable, and address fundamental barriers in longitudinal EHR forecasting. I ensured no existing datasets were duplicated and adhered to the scarcity constraints.

### Approved Concepts
- DT-Transformer: Represents a scaling of foundation model architectures specifically to multi-hospital EHR records for longitudinal disease forecasting.

### Approved Open Questions
- Cross-institutional data fragmentation impact: Foundation models for healthcare depend on large-scale data to generalize; fragmentation remains a fundamental barrier to achieving reliable long-horizon clinical predictions.
- Optimal temporal encoding for EHRs: Temporal representation is a critical bottleneck for accurate clinical sequence modeling when dealing with non-uniform density and complex longitudinal gaps.

## Links

- [Abstract](https://arxiv.org/abs/2605.14227)
- [PDF](https://arxiv.org/pdf/2605.14227)

