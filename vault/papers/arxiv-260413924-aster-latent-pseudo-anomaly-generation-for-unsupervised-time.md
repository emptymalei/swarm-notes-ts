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
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "latent-space-pseudo-anomaly-generation"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-17T05:07:07Z"
created_at: "2026-04-17T05:07:07Z"
---

# ASTER: Latent Pseudo-Anomaly Generation for Unsupervised Time-Series Anomaly Detection

**Authors**: Romain Hermary, Samet Hicsonmez, Dan Pineau, Abd El Rahman Shabayek, Djamila Aouada
**Date**: 2026-04-15
**Paper ID**: [arxiv:2604.13924](https://arxiv.org/abs/2604.13924)

## Summary

ASTER is an unsupervised time-series anomaly detection framework that synthesizes pseudo-anomalies directly within a latent space, removing the reliance on handcrafted anomaly injection. By leveraging a pre-trained LLM, the model enriches temporal and contextual representations before training a Transformer-based classifier. This approach avoids the limitations of traditional reconstruction and forecasting methods, achieving state-of-the-art detection results on benchmark time-series datasets.

## Key Contributions

- Introduces ASTER, a framework that synthesizes pseudo-anomalies in the latent space to eliminate the need for manual anomaly injection or domain-specific heuristics.
- Integrates pre-trained LLMs to enhance the temporal and contextual representations within the latent space for anomaly classification.
- Demonstrates state-of-the-art performance in time-series anomaly detection across three benchmark datasets, outperforming reconstruction and forecasting-based baselines.

## Open Questions & Future Work

- [[enhancing-pseudo-anomaly-diversity]]

## Key Concepts

- [[latent-space-pseudo-anomaly-generation]]: A framework that generates synthetic anomalies directly within a latent space to train anomaly classifiers without manual intervention.

## Archivist Review

I approved the concept of Latent Space Pseudo-Anomaly Generation as a distinct, reusable paradigm for anomaly detection. I also approved an open question regarding pseudo-anomaly diversity, as it addresses a fundamental limitation in self-supervised latent-based detection methods. I rejected the open question on LLM tokenization as it is too broad and generic compared to the specific methodological contribution of the paper.

### Approved Concepts
- Latent Space Pseudo-Anomaly Generation: It enables anomaly detection without domain-specific data engineering or manual injection of anomalies, shifting the burden from domain heuristics to model-based latent synthesis.

### Approved Open Questions
- Enhancing Pseudo-Anomaly Generation Diversity: The limited diversity of generated pseudo-anomalies restricts the model's ability to learn complex decision boundaries, directly impacting performance on datasets with varied or rare anomalies.

### Rejected Candidates
- [open_question] LLM-based Time-Series Tokenization Methods (`llm-timeseries-tokenization`) - generic: This is a broad, generic research direction that is being addressed by a vast and rapidly growing literature beyond this paper.

## Links

- [Abstract](https://arxiv.org/abs/2604.13924)
- [PDF](https://arxiv.org/pdf/2604.13924)

