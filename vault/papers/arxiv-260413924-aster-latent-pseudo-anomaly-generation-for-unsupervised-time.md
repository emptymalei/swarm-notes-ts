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
processed_at: "2026-04-16T05:06:03Z"
created_at: "2026-04-16T05:06:03Z"
---

# ASTER: Latent Pseudo-Anomaly Generation for Unsupervised Time-Series Anomaly Detection

**Authors**: Romain Hermary, Samet Hicsonmez, Dan Pineau, Abd El Rahman Shabayek, Djamila Aouada
**Date**: 2026-04-15
**Paper ID**: [arxiv:2604.13924](https://arxiv.org/abs/2604.13924)

## Summary

ASTER is an unsupervised time-series anomaly detection framework that circumvents the need for manual anomaly engineering by generating pseudo-anomalies directly within the latent space. A learned latent-space decoder produces context-aware anomalies, while a pre-trained LLM provides robust temporal and contextual embeddings to support a downstream Transformer-based classifier. This approach successfully addresses the challenge of rare and heterogeneous anomalies by learning discriminative features without labelled training data. Performance evaluation confirms that ASTER sets a new standard for LLM-integrated anomaly detection across multiple benchmark datasets.

## Key Contributions

- ASTER generates pseudo-anomalies directly in the latent space via a learned decoder, eliminating the need for handcrafted anomaly injection or domain expertise.
- Integrates a pre-trained LLM to enrich temporal and contextual representations within the latent space for enhanced classification.
- Achieves state-of-the-art performance on three standard time-series anomaly detection benchmarks.

## Open Questions & Future Work

- [[pseudo-anomaly-diversity-and-coverage]]

## Key Concepts

- [[latent-space-pseudo-anomaly-generation]]: A method for training unsupervised anomaly detectors by synthesizing pseudo-anomalies within the learned latent embedding space of the model.

## Archivist Review

I approved the central concept of latent-space anomaly generation as a distinct methodological advancement over domain-specific handcrafted injection. The open question was reframed to prioritize the broader research bottleneck of ensuring anomaly coverage rather than focusing on the specific implementation of the ASTER paper. No datasets were approved as none were identified as uniquely foundational to the field.

### Approved Concepts
- Latent-Space Pseudo-Anomaly Generation: Moves anomaly injection from the raw data domain (which is often domain-specific and brittle) to the latent manifold, allowing for more flexible and model-aware pseudo-anomaly synthesis.

### Approved Open Questions
- Pseudo-anomaly diversity and coverage: High-quality, diverse anomaly synthesis is the primary bottleneck for the performance of self-supervised and unsupervised anomaly detection frameworks.

### Rejected Candidates
- [concept] Latent Pseudo-Anomaly Generation (ASTER) (`latent-pseudo-anomaly-generation-aster`) - duplicate_existing: Redundant with 'latent-space-pseudo-anomaly-generation'; stripped the paper-specific name for a broader concept.
- [open_question] Improving latent pseudo-anomaly diversity (`improving-pseudo-anomaly-diversity`) - duplicate_existing: Rephrased for professional naming consistency and broader relevance.

## Links

- [Abstract](https://arxiv.org/abs/2604.13924)
- [PDF](https://arxiv.org/pdf/2604.13924)

