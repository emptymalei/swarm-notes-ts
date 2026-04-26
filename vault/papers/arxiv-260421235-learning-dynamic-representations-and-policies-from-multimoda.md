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
  - "time-series"
  - "multimodal-learning"
  - "clinical-prediction"
  - "offline-reinforcement-learning"
  - "missing-data"
architectures:
  []
datasets:
  - "mimic-iii"
  - "eicu"
concept_slugs:
  - "informative-missingness-representation-learning"
dataset_slugs:
  - "mimic-iii"
  - "eicu"
skill: "TimeSeriesSkill"
processed_at: "2026-04-26T05:09:58Z"
created_at: "2026-04-26T05:09:58Z"
---

# Learning Dynamic Representations and Policies from Multimodal Clinical Time-Series with Informative Missingness

**Authors**: Zihan Liang, Ziwen Pan, Ruoxuan Xiong
**Date**: 2026-04-23
**Paper ID**: [arxiv:2604.21235](https://arxiv.org/abs/2604.21235)

## Summary

This paper addresses the challenge of informative missingness in multimodal clinical time-series, where the timing and presence of records are predictive of patient health. The authors propose a unified framework combining a multimodal encoder, a Bayesian filtering module for latent state tracking, and specialized modules for offline policy learning and outcome prediction. By treating both the structured measurements and clinical notes alongside their respective recording processes, the model captures richer representations than standard imputation-based approaches. Evaluation across three major ICU datasets (MIMIC-III, MIMIC-IV, and eICU) confirms substantial improvements in both predictive accuracy and treatment policy optimization.

## Key Contributions

- Introduces a multimodal representation learning framework that treats observation patterns as latent state-dependent variables.
- Achieves an FQE of 0.679 for offline treatment policy learning, significantly outperforming clinician behavior baseline on MIMIC-III.
- Demonstrates state-of-the-art performance on post-72-hour mortality prediction (AUROC 0.886) using the proposed Bayesian filtering module.

## Open Questions & Future Work

- [[mitigating-negative-transfer-clinical-multitask-learning]]

## Key Concepts

- [[informative-missingness-representation-learning]]: A framework that embeds patient observation patterns as informative signals to improve state estimation and downstream policy learning.

## Archivist Review

The paper introduces a novel approach to modeling observation patterns in clinical data as explicit features. I approved the core concept and the open question regarding multitask negative transfer, which is a significant bottleneck in clinical modeling. The datasets chosen provide representative coverage of the ICU cohort benchmarks.

### Approved Concepts
- Informative Missingness Representation Learning: The core novelty of the paper is moving beyond imputation by explicitly modeling the observation process as a source of clinical information.

### Approved Open Questions
- Mitigating Negative Transfer in Multitask Learning: As clinical models move toward serving multiple diagnostic and prognostic endpoints simultaneously, managing task interference is essential to prevent performance degradation on critical safety-sensitive tasks.

### Rejected Candidates
- [dataset] MIMIC-IV (`mimic-iv`) - other: Limiting to two representative datasets; MIMIC-III and eICU are already established benchmarks in the vault.

## Datasets

- [[mimic-iii]]
- [[eicu]]

## Links

- [Abstract](https://arxiv.org/abs/2604.21235)
- [PDF](https://arxiv.org/pdf/2604.21235)

