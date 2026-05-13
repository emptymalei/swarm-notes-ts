---
# CSL-compatible fields
title: "On Predicting the Post-training Potential of Pre-trained LLMs"
author:
  - literal: "Xiaoyuan Li"
  - literal: "Yubo Ma"
  - literal: "Kexin Yang"
  - literal: "Moxin Li"
  - literal: "Keqin Bao"
  - literal: "Wenie Wang"
  - literal: "Fuli Feng"
  - literal: "Dayiheng Liu"
issued:
  date-parts:
    - [2026, 5, 12]
url: "https://arxiv.org/abs/2605.11978"

# Custom fields
paper_id: "2605.11978"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "rude-rubric-based-discriminative-evaluation"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-13T05:24:07Z"
created_at: "2026-05-13T05:24:07Z"
---

# On Predicting the Post-training Potential of Pre-trained LLMs

**Authors**: Xiaoyuan Li, Yubo Ma, Kexin Yang, Moxin Li, Keqin Bao, Wenie Wang, Fuli Feng, Dayiheng Liu
**Date**: 2026-05-12
**Paper ID**: [arxiv:2605.11978](https://arxiv.org/abs/2605.11978)

## Summary

This paper introduces the task of predicting post-training potential to overcome the limitations of standard benchmarks in reflecting base model plasticity. The authors propose RuDE (Rubric-based Discriminative Evaluation), a framework that evaluates base models via response discrimination using controlled contrastive pairs based on a 4C taxonomy of rubric violations. Experiments demonstrate that RuDE achieves a correlation exceeding 90% with final post-training performance, providing a highly efficient alternative to full post-training for model selection. Validation through reinforcement learning confirms the framework's capability to identify high-performing, compute-efficient smaller models.

## Key Contributions

- Introduced the task of predicting post-training potential to assess base model plasticity.
- Proposed RuDE, a framework that correlates >90% with actual post-training performance.
- Validated that RuDE enables compute-efficient identification of high-potential smaller models that outperform larger ones.

## Open Questions & Future Work

- [[discriminative-generative-gap-potential]]

## Key Concepts

- [[rude-rubric-based-discriminative-evaluation]]: A framework that predicts LLM post-training potential by evaluating base models through response discrimination and rubric-based contrastive pairs.

## Archivist Review

I have approved the RuDE framework as it provides a distinct, reusable methodology for forecasting model potential, and the open question regarding the discriminative-generative gap because it identifies a fundamental theoretical bottleneck in model selection practices. I rejected no candidates because only one concept and one open question were submitted, both of which met the criteria for permanence in the vault.

### Approved Concepts
- RuDE (Rubric-based Discriminative Evaluation): It introduces a novel methodology for forecasting post-training performance without requiring the costly fine-tuning process, addressing a critical bottleneck in compute-efficient LLM development.

### Approved Open Questions
- Discriminative-Generative Gap Potential: Defining the limits of using discriminative proxies to predict generative downstream performance is critical for the reliability of compute-efficient model development.

## Links

- [Abstract](https://arxiv.org/abs/2605.11978)
- [PDF](https://arxiv.org/pdf/2605.11978)

