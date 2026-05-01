---
# CSL-compatible fields
title: "Simulating clinical interventions with a generative multimodal model of human physiology"
author:
  - literal: "Guy Lutsker"
  - literal: "Gal Sapir"
  - literal: "Jordi Merino"
  - literal: "Smadar Shilo"
  - literal: "Anastasia Godneva"
  - literal: "Eli Meirom"
  - literal: "Shie Mannor"
  - literal: "Hagai Rossman"
  - literal: "Gal Chechik"
  - literal: "Eran Segal"
issued:
  date-parts:
    - [2026, 4, 30]
url: "https://arxiv.org/abs/2604.27899"

# Custom fields
paper_id: "2604.27899"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  - "Human Phenotype Project"
concept_slugs:
  - "healthformer"
dataset_slugs:
  - "human-phenotype-project"
skill: "TimeSeriesSkill"
processed_at: "2026-05-01T05:22:30Z"
created_at: "2026-05-01T05:22:30Z"
---

# Simulating clinical interventions with a generative multimodal model of human physiology

**Authors**: Guy Lutsker, Gal Sapir, Jordi Merino, Smadar Shilo, Anastasia Godneva, Eli Meirom, Shie Mannor, Hagai Rossman, Gal Chechik, Eran Segal
**Date**: 2026-04-30
**Paper ID**: [arxiv:2604.27899](https://arxiv.org/abs/2604.27899)

## Summary

HealthFormer is a decoder-only transformer trained on the Human Phenotype Project to model complex physiological trajectories across 667 diverse clinical and behavioral measurements. By treating health states as tokens, the model functions as an initial health world model capable of forecasting future physiological states and performing risk stratification. It demonstrates significant clinical utility by accurately simulating individualized responses to interventions, outperforming traditional risk scores and aligning with findings from external randomized controlled trials.

## Key Contributions

- Introduces HealthFormer, a generative transformer architecture that models human physiological health as a multi-domain tokenized trajectory.
- Demonstrates cross-cohort transferability, outperforming established clinical risk scores on 27 of 30 incident-disease and mortality endpoints without task-specific tuning.
- Validates in silico simulation of clinical interventions against 41 randomized controlled trials, consistently predicting the correct direction of physiological effects.

## Key Concepts

- [[healthformer]]: A decoder-only transformer architecture that models multi-domain human physiological health as a tokenized generative trajectory to facilitate in-silico intervention simulation and risk stratification.

## Archivist Review

I approved the HealthFormer architecture as a significant contribution to clinical trajectory modeling and the Human Phenotype Project as a core dataset. I rejected the additional concept candidate because it was redundant with the first. I refrained from adding open questions as the current candidates did not highlight specific unresolved bottlenecks in the research beyond generic scalability.

### Approved Concepts
- HealthFormer: The paper proposes this as an initial health world model, treating longitudinal, heterogeneous multi-domain physiological data as tokenized trajectories to enable both forecasting and intervention-conditioned simulation.

### Rejected Candidates
- [concept] HealthFormer (`healthformer-concept`) - duplicate_existing: The concept was already captured under the slug 'healthformer'.

## Datasets

- [[human-phenotype-project]]

## Links

- [Abstract](https://arxiv.org/abs/2604.27899)
- [PDF](https://arxiv.org/pdf/2604.27899)

