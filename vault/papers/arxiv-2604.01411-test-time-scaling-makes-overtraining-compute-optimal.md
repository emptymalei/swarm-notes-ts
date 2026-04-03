---
# CSL-compatible fields
title: "Test-Time Scaling Makes Overtraining Compute-Optimal"
author:
  - literal: "Nicholas Roberts"
  - literal: "Sungjun Cho"
  - literal: "Zhiqi Gao"
  - literal: "Tzu-Heng Huang"
  - literal: "Albert Wu"
  - literal: "Gabriel Orlanski"
  - literal: "Avi Trost"
  - literal: "Kelly Buchanan"
  - literal: "Aws Albarghouthi"
  - literal: "Frederic Sala"
issued:
  date-parts:
    - [2026, 4, 1]
url: "https://arxiv.org/abs/2604.01411"

# Custom fields
paper_id: "2604.01411"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "llm"
  - "scaling-laws"
  - "inference-optimization"
  - "model-training"
architectures:
  []
datasets:
  []
concept_slugs:
  - "train-to-test-scaling-laws"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-04-03T05:24:46Z"
created_at: "2026-04-03T05:24:46Z"
---

# Test-Time Scaling Makes Overtraining Compute-Optimal

**Authors**: Nicholas Roberts, Sungjun Cho, Zhiqi Gao, Tzu-Heng Huang, Albert Wu, Gabriel Orlanski, Avi Trost, Kelly Buchanan, Aws Albarghouthi, Frederic Sala
**Date**: 2026-04-01
**Paper ID**: [arxiv:2604.01411](https://arxiv.org/abs/2604.01411)

## Summary

The paper addresses the limitation of traditional pretraining scaling laws by introducing Train-to-Test (T^2) scaling, which accounts for inference-time costs like repeated sampling. By jointly optimizing pretraining compute and test-time compute, the authors show that modern compute-optimal strategies should favor significantly more overtraining than previously suggested. The framework is validated empirically across eight downstream tasks and remains effective even after post-training.

## Key Contributions

- Introduces Train-to-Test (T^2) scaling laws to jointly optimize model size, training tokens, and inference samples under fixed end-to-end budgets.
- Demonstrates that accounting for inference costs shifts optimal pretraining regimes toward significant overtraining compared to standard Chinchilla-optimal targets.
- Validates T^2 predictions by training overtrained models that outperform traditional compute-optimal counterparts on eight downstream tasks.
- Shows that the benefits of overtraining persist through the post-training (alignment) stage for frontier LLMs.

## Open Questions & Future Work

- [[overtrained-model-finetuning-difficulty]]

## Key Concepts

- [[train-to-test-scaling-laws]]: A framework for jointly optimizing model pretraining and test-time sampling resources under a unified end-to-end compute budget.

## Archivist Review

I approved the core concept of Train-to-Test scaling, as it represents a fundamental shift in how compute budget is allocated across the machine learning lifecycle. I also approved the open question regarding the alignment difficulty of overtrained models because it addresses a significant tension between the proposed efficiency gains and real-world deployment requirements. Other candidates were rejected for being overly incremental or focusing on specific architecture variations.

### Approved Concepts
- Train-to-Test Scaling Laws: Integrates test-time compute into the pretraining optimization objective, filling a gap in traditional scaling laws like Chinchilla.

### Approved Open Questions
- Alignment Difficulty of Overtrained Models: This is a critical practical bottleneck: if overtraining models for test-time scaling makes them significantly harder to align or adapt, the net utility of the scaling strategy is limited in real-world deployment scenarios.

### Rejected Candidates
- [open_question] Architecture-Specific Inference Cost Modeling (`architecture-specific-inference-scaling`) - low_impact: Future work on architecture-specific cost models is too incremental and falls under routine refinements for scaling law research.

## Links

- [Abstract](https://arxiv.org/abs/2604.01411)
- [PDF](https://arxiv.org/pdf/2604.01411)

