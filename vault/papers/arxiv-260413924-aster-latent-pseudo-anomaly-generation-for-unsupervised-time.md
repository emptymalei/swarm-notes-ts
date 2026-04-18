---
# CSL-compatible fields
title: "ASTER: Latent Pseudo-Anomaly Generation for Unsupervised Time-Series Anomaly Detection"
author:
  - literal: "Romain Hermary"
  - literal: "Samet Hicsonmez"
  - literal: "Dan Pineau"
  - literal: "Abd El Rahman Shabayek"
  - literal: "Djamila Aouada"
issued:
  date-parts:
    - [2026, 4, 15]
url: "https://arxiv.org/abs/2604.13924"

# Custom fields
paper_id: "2604.13924"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series-anomaly-detection"
  - "unsupervised-learning"
  - "transformer"
  - "llm"
architectures:
  []
datasets:
  []
concept_slugs:
  - "latent-pseudo-anomaly-generation"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-18T04:53:47Z"
created_at: "2026-04-18T04:53:47Z"
---

# ASTER: Latent Pseudo-Anomaly Generation for Unsupervised Time-Series Anomaly Detection

**Authors**: Romain Hermary, Samet Hicsonmez, Dan Pineau, Abd El Rahman Shabayek, Djamila Aouada
**Date**: 2026-04-15
**Paper ID**: [arxiv:2604.13924](https://arxiv.org/abs/2604.13924)

## Summary

ASTER is an unsupervised time-series anomaly detection framework that addresses the scarcity of labeled data by generating pseudo-anomalies directly within the latent space. By leveraging a latent-space decoder and pre-trained LLMs, the model enhances temporal and contextual representation learning for more effective anomaly classification. This approach avoids the limitations of traditional reconstruction-based methods and handcrafted anomaly injection, demonstrating state-of-the-art performance across three benchmark datasets.

## Key Contributions

- Introduces ASTER, which generates pseudo-anomalies in the latent space, eliminating the reliance on domain-specific handcrafted anomaly injections.
- Integrates pre-trained LLMs to enrich temporal and contextual representations within the latent space for improved anomaly classification.
- Achieves state-of-the-art performance on three standard time-series anomaly detection benchmarks, surpassing existing reconstruction and forecasting-based methods.

## Open Questions & Future Work

- [[enhancing-pseudo-anomaly-diversity]]

## Key Concepts

- [[latent-pseudo-anomaly-generation]]: A method for generating tailored pseudo-anomalies directly within a model's latent representation space to train anomaly classifiers.

## Archivist Review

I have approved the core concept of Latent Pseudo-Anomaly Generation and the specific research question regarding its diversity limitation. The second open question regarding general LLM-time-series translation was rejected for being too generic and broad, failing to address the specific TSAD mechanism.

### Approved Concepts
- Latent Pseudo-Anomaly Generation: It replaces traditional handcrafted anomaly injection with a generative approach in the latent space to improve TSAD robustness without domain-specific knowledge.

### Approved Open Questions
- Enhancing Pseudo-Anomaly Diversity: Diversity in pseudo-anomalies is critical for the robustness of anomaly classifiers; the current observation that generated pseudo-anomalies occupy a limited latent space suggests a bottleneck in model generalization.

### Rejected Candidates
- [open_question] Optimizing LLM-based Time-Series Representations (`llm-time-series-translation-optimization`) - generic: The question of bridging modality gaps between time-series and LLMs is too broad and generic for a standalone note compared to specific mechanism questions.

## Links

- [Abstract](https://arxiv.org/abs/2604.13924)
- [PDF](https://arxiv.org/pdf/2604.13924)

