---
# CSL-compatible fields
title: "Learning Dynamic Representations and Policies from Multimodal Clinical Time-Series with Informative Missingness"
author:
  - literal: "Zihan Liang"
  - literal: "Ziwen Pan"
  - literal: "Ruoxuan Xiong"
issued:
  date-parts:
    - [2026, 4, 23]
url: "https://arxiv.org/abs/2604.21235"

# Custom fields
paper_id: "2604.21235"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "nlp"
  - "time-series"
architectures:
  []
datasets:
  []
concept_slugs:
  - "informative-missingness-representation-learning"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-25T04:54:51Z"
created_at: "2026-04-25T04:54:51Z"
---

# Learning Dynamic Representations and Policies from Multimodal Clinical Time-Series with Informative Missingness

**Authors**: Zihan Liang, Ziwen Pan, Ruoxuan Xiong
**Date**: 2026-04-23
**Paper ID**: [arxiv:2604.21235](https://arxiv.org/abs/2604.21235)

## Summary

This paper presents a representation learning framework for multimodal clinical time-series that explicitly treats observation patterns as informative signals. By integrating a multimodal encoder with a Bayesian filtering module, the model maintains a latent patient state that accounts for both structured measurements and clinical notes alongside their distinct recording processes. The learned representations are shown to enhance both patient outcome prediction and offline treatment policy learning across multiple large-scale ICU datasets.

## Key Contributions

- Introduces a multimodal representation learning framework that explicitly models informative missingness in clinical time-series.
- Achieves superior performance on ICU sepsis cohorts, reaching 0.886 AUROC for post-72-hour mortality prediction on MIMIC-III.
- Improves offline reinforcement learning policy evaluation with a FQE score of 0.679, outperforming clinicians (0.528).

## Open Questions & Future Work

- [[leveraging-multimodal-informative-missingness-over-time]]

## Key Concepts

- [[informative-missingness-representation-learning]]: A framework for incorporating the non-random observation patterns in multimodal clinical data into latent state representations.

## Archivist Review

The paper provides a significant advancement in treating clinical observation processes as active data rather than passive noise. I have approved the 'Informative Missingness Representation Learning' concept as it represents a shift in modeling healthcare time-series. The open question was narrowed to focus on the systematic integration of multimodal missingness, as this remains a critical bottleneck in the reliability of clinical decision support systems. Established clinical datasets (MIMIC-III/IV, eICU) were rejected to avoid duplicate entries.

### Approved Concepts
- Informative Missingness Representation Learning: Central to the paper's novelty; treats observation patterns as an informative signal rather than noise in clinical time series.

### Approved Open Questions
- Leveraging Multimodal Informative Missingness: This is a central bottleneck in clinical AI because patient states are partially observed, and treatment policies depend on accurate representations of health evolution. Addressing this directly impacts the safety and efficacy of autonomous clinical decision support.

### Rejected Candidates
- [dataset] MIMIC-III (`mimic-iii`) - duplicate_existing: Established clinical datasets are already common in the vault and do not require new standalone entries.
- [dataset] MIMIC-IV (`mimic-iv`) - duplicate_existing: Established clinical datasets are already common in the vault and do not require new standalone entries.
- [dataset] eICU (`eicu`) - duplicate_existing: Established clinical datasets are already common in the vault and do not require new standalone entries.

## Links

- [Abstract](https://arxiv.org/abs/2604.21235)
- [PDF](https://arxiv.org/pdf/2604.21235)

