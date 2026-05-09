---
# CSL-compatible fields
title: "SDFlow: Similarity-Driven Flow Matching for Time Series Generation"
author:
  - literal: "Wei Li"
  - literal: "Shibo Feng"
  - literal: "Pengcheng Wu"
  - literal: "Min Wu"
  - literal: "Peilin Zhao"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2605.05736"

# Custom fields
paper_id: "2605.05736"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "similarity-driven-flow-matching"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-09T05:12:25Z"
created_at: "2026-05-09T05:12:25Z"
---

# SDFlow: Similarity-Driven Flow Matching for Time Series Generation

**Authors**: Wei Li, Shibo Feng, Pengcheng Wu, Min Wu, Peilin Zhao
**Date**: 2026-05-07
**Paper ID**: [arxiv:2605.05736](https://arxiv.org/abs/2605.05736)

## Summary

SDFlow is a non-autoregressive generative framework for time series that addresses the exposure bias inherent in autoregressive vector-quantized token models. By operating entirely within a frozen latent space, the model utilizes a variational flow-matching formulation to enable parallel sequence generation via global transport maps. The framework further incorporates a low-rank manifold decomposition and categorical posterior supervision, resulting in superior long-horizon generation quality and faster inference speeds compared to traditional autoregressive baselines.

## Key Contributions

- Introduces SDFlow, a non-autoregressive generative framework for time series that eliminates exposure bias through global transport maps.
- Implements a low-rank manifold decomposition with learned latent anchor priors to mitigate high-dimensional VQ token space complexities.
- Integrates discrete codebook supervision into continuous flow dynamics using a variational flow-matching formulation, achieving SOTA discriminative scores and reduced Context-FID.

## Open Questions & Future Work

- [[universal-time-series-tokenizer]]

## Key Concepts

- [[similarity-driven-flow-matching]]: A non-autoregressive time series generation framework that uses a variational flow-matching formulation over frozen VQ latent spaces.

## Archivist Review

The paper presents a significant departure from standard autoregressive VQ-based time series generation. I have approved the framework concept and the open question regarding universal tokenization, as both address fundamental bottlenecks in the field. The other minor implementation subcomponents were rejected to maintain the vault's focus on high-level methodology.

### Approved Concepts
- Similarity-Driven Flow Matching: It is the core methodological contribution, enabling non-autoregressive parallel generation of time series by replacing sequential token prediction with a global transport map in latent space.

### Approved Open Questions
- Universal Time Series Tokenizer: Universal tokenization is essential for scaling time series generative models across diverse domains and simplifying the pipeline for new applications.

## Links

- [Abstract](https://arxiv.org/abs/2605.05736)
- [PDF](https://arxiv.org/pdf/2605.05736)

