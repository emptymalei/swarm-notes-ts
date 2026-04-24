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
  []
architectures:
  []
datasets:
  - "mimic-iii"
  - "mimic-iv"
concept_slugs:
  - "informative-missingness-representation-learning"
dataset_slugs:
  - "mimic-iii"
  - "mimic-iv"
skill: "TimeSeriesSkill"
processed_at: "2026-04-24T05:08:15Z"
created_at: "2026-04-24T05:08:15Z"
---

# Learning Dynamic Representations and Policies from Multimodal Clinical Time-Series with Informative Missingness

**Authors**: Zihan Liang, Ziwen Pan, Ruoxuan Xiong
**Date**: 2026-04-23
**Paper ID**: [arxiv:2604.21235](https://arxiv.org/abs/2604.21235)

## Summary

This paper addresses the challenge of sparse, multimodal clinical time series by proposing a representation learning framework that treats missing data as an informative signal rather than a nuisance. The model incorporates a multimodal encoder for structured and textual data, a Bayesian filtering module to track latent patient health states, and dedicated heads for offline treatment policy and outcome prediction. Experimental results across major ICU benchmarks demonstrate significant improvements over conventional baselines in both clinical decision support and mortality risk assessment.

## Key Contributions

- Proposes a multimodal framework that integrates structured data and clinical notes with their unique observation patterns into a unified latent state.
- Introduces a Bayesian filtering module that systematically updates latent patient representations by conditioning on both observed data and the informativeness of missingness.
- Achieves state-of-the-art results on ICU sepsis cohorts, with FQE of 0.679 for offline policy learning and AUROC 0.886 for mortality prediction on MIMIC-III.

## Open Questions & Future Work

- [[informative-missingness-multimodal-temporal-dynamics]]

## Key Concepts

- [[informative-missingness-representation-learning]]: A representation learning framework that explicitly encodes and utilizes the timing and occurrence patterns of multimodal clinical observations to update patient latent states.

## Archivist Review

Approved the core concept of Informative Missingness Representation Learning, as it provides a valuable framework for handling endogenous observation processes in time-series data. I approved the two primary MIMIC datasets as they are foundational to the study's evaluation claims. The open question regarding informative missingness in multimodal dynamics was retained for its specific relevance to the challenges of sequential clinical decision-making, while the general multi-task negative transfer question was rejected as overly broad.

### Approved Concepts
- Informative Missingness Representation Learning: The paper explicitly models the observation process as a feature, which is a critical advancement for clinical time-series analysis where data sparsity correlates with patient health.

### Approved Open Questions
- Informative Missingness in Multimodal Dynamics: This is critical for clinical reinforcement learning, as patient state representations that fail to account for the endogenous observation processes may lead to biased policies.

### Rejected Candidates
- [open_question] Negative Transfer in Multitask Learning (`negative-transfer-multitask-clinical-learning`) - generic: The concern of negative transfer in multi-task learning is generic to machine learning and not specific to the technical mechanics of clinical time series.

## Datasets

- [[mimic-iii]]
- [[mimic-iv]]

## Links

- [Abstract](https://arxiv.org/abs/2604.21235)
- [PDF](https://arxiv.org/pdf/2604.21235)

