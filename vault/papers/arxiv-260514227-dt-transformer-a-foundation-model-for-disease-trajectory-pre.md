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
  - "healthcare"
  - "clinical-forecasting"
  - "foundation-models"
  - "ehr-analysis"
architectures:
  []
datasets:
  []
concept_slugs:
  - "dt-transformer"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-16T05:13:42Z"
created_at: "2026-05-16T05:13:42Z"
---

# DT-Transformer: A Foundation Model for Disease Trajectory Prediction on a Real-world Health System

**Authors**: Yunying Zhu, Andrew R Weckstein, Kueiyu Joshua Lin, Jie Yang
**Date**: 2026-05-14
**Paper ID**: [arxiv:2605.14227](https://arxiv.org/abs/2605.14227)

## Summary

DT-Transformer is a foundation model designed for clinical disease trajectory prediction using large-scale electronic health record (EHR) data. Trained on 57.1 million entries from 1.7 million patients across the Mass General Brigham health system, the model aims to address the limitations of small-scale, single-site models. It demonstrates high predictive discrimination across nearly 900 disease categories, confirming the potential of system-wide EHR integration for robust real-world clinical forecasting.

## Key Contributions

- Introduces DT-Transformer, a foundation model trained on 57.1M structured EHR entries from 1.7M patients across 11 hospitals.
- Achieves a median age- and sex-stratified AUC of 0.871 for next-event prediction across 896 disease categories.
- Demonstrates strong performance in both held-out and prospective validation settings, validating the efficacy of health system-scale training for clinical forecasting.

## Open Questions & Future Work

- [[ehr-temporal-encoding-optimization]]
- [[clinical-utility-of-trajectory-models]]

## Key Concepts

- [[dt-transformer]]: A foundation model trained on large-scale electronic health records for clinical disease trajectory forecasting.

## Archivist Review

I approved the DT-Transformer architecture as it represents a significant shift toward system-level foundation models in healthcare. I also approved the two open questions, as they highlight critical, recurring bottlenecks in modeling irregular clinical longitudinal data and the ongoing challenge of clinical translation for foundation models. Other potential dataset candidates were excluded to maintain focus on the methodology.

### Approved Concepts
- DT-Transformer: Represents a specific implementation of a foundation model for health-system scale EHR data, likely to serve as a benchmark or reference architecture in future clinical AI research.

### Approved Open Questions
- Optimizing temporal representation for EHRs: Effective time representation is critical for foundation models to accurately predict disease trajectories over varying time horizons in fragmented real-world clinical systems.
- Clinical utility of trajectory models: Bridging the gap between high-performing predictive models in research settings and actionable clinical tools is essential for the translation of AI in medicine.

## Links

- [Abstract](https://arxiv.org/abs/2605.14227)
- [PDF](https://arxiv.org/pdf/2605.14227)

