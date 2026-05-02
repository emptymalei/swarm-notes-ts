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
  []
concept_slugs:
  - "healthformer"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-02T05:07:46Z"
created_at: "2026-05-02T05:07:46Z"
---

# Simulating clinical interventions with a generative multimodal model of human physiology

**Authors**: Guy Lutsker, Gal Sapir, Jordi Merino, Smadar Shilo, Anastasia Godneva, Eli Meirom, Shie Mannor, Hagai Rossman, Gal Chechik, Eran Segal
**Date**: 2026-04-30
**Paper ID**: [arxiv:2604.27899](https://arxiv.org/abs/2604.27899)

## Summary

HealthFormer is a decoder-only transformer model designed to serve as a generative 'world model' for human physiology. By tokenizing longitudinal health data across 667 measurements spanning seven diverse domains, the model learns to forecast individual physiological trajectories and simulate the effects of clinical interventions. It demonstrates strong zero-shot transfer performance across independent cohorts and surpasses traditional clinical risk scores in predicting disease and mortality endpoints.

## Key Contributions

- Introduces HealthFormer, a generative transformer trained on 15,000 deeply phenotyped individuals to model multimodal physiological trajectories.
- Demonstrates cross-task transferability by outperforming established clinical risk scores on 27 of 30 incident-disease and mortality endpoints without task-specific tuning.
- Enables in silico intervention simulation, showing high alignment with clinical trial outcomes for biomarker changes and intervention effects.

## Key Concepts

- [[healthformer]]: A decoder-only transformer model designed for generative forecasting and in silico simulation of individual human physiological trajectories across heterogeneous clinical domains.

## Archivist Review

I approved the HealthFormer model as a foundational concept in generative clinical digital twins. It provides a unique, reusable framework for modeling highly heterogeneous longitudinal physiological data that extends beyond standard time-series forecasting. I kept the vault selective by only approving this core contribution, as other potential candidates were too closely tied to specific performance metrics or implementation details.

### Approved Concepts
- HealthFormer: It introduces the first generative foundation model architecture specifically designed to simulate individual human physiological trajectories across 667 heterogeneous health measurements.

## Links

- [Abstract](https://arxiv.org/abs/2604.27899)
- [PDF](https://arxiv.org/pdf/2604.27899)

