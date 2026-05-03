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
  - literal: "Shie Mannor, Hagai Rossman"
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
  - "transformer"
  - "generative-modeling"
  - "medical-ai"
  - "longitudinal-forecasting"
architectures:
  []
datasets:
  - "Human Phenotype Project"
concept_slugs:
  - "healthformer"
dataset_slugs:
  - "human-phenotype-project"
skill: "TimeSeriesSkill"
processed_at: "2026-05-03T05:14:31Z"
created_at: "2026-05-03T05:14:31Z"
---

# Simulating clinical interventions with a generative multimodal model of human physiology

**Authors**: Guy Lutsker, Gal Sapir, Jordi Merino, Smadar Shilo, Anastasia Godneva, Eli Meirom, Shie Mannor, Hagai Rossman, Gal Chechik, Eran Segal
**Date**: 2026-04-30
**Paper ID**: [arxiv:2604.27899](https://arxiv.org/abs/2604.27899)

## Summary

HealthFormer is a decoder-only transformer model trained on multi-modal, longitudinal health data to serve as a generative world model for human physiology. By tokenizing 667 diverse health measurements, the model learns to forecast individual physiological trajectories without task-specific training. The model demonstrates strong zero-shot transfer capabilities across independent clinical cohorts and accurately simulates the effects of interventions, establishing a pathway for personalized, in silico clinical decision support.

## Key Contributions

- Introduces HealthFormer, a generative transformer architecture trained on 15,000+ deeply phenotyped individuals to model complex physiological trajectories.
- Demonstrates that HealthFormer acts as a foundation model, achieving superior zero-shot performance on 27 of 30 clinical risk prediction endpoints compared to traditional scores.
- Validates the model's in silico intervention simulation capability by recovering 6-month biomarker changes and matching outcomes from 41 randomized clinical trials.

## Key Concepts

- [[healthformer]]: A decoder-only transformer model designed to generatively forecast multi-domain human physiological trajectories and simulate clinical interventions.

## Archivist Review

The paper presents an integrated approach to generative longitudinal health forecasting. I have approved 'HealthFormer' as it represents a novel foundation model architecture for multiscale clinical physiology, and the 'Human Phenotype Project' dataset as a uniquely large, longitudinal source necessary for training such models. Generic tags like 'transformer' or 'medical-ai' were rejected as they do not constitute specific research contributions.

### Approved Concepts
- HealthFormer: It is the central contribution of the paper, serving as a foundational generative world model for human physiology.

### Rejected Candidates
- [concept] transformer (`transformer`) - generic: Generic architectural component.
- [concept] generative-modeling (`generative-modeling`) - generic: Generic ML paradigm.
- [concept] medical-ai (`medical-ai`) - generic: Generic field descriptor.
- [concept] longitudinal-forecasting (`longitudinal-forecasting`) - generic: Generic task classification.

## Datasets

- [[human-phenotype-project]]

## Links

- [Abstract](https://arxiv.org/abs/2604.27899)
- [PDF](https://arxiv.org/pdf/2604.27899)

