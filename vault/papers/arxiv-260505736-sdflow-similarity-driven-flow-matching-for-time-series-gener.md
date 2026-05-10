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
domain: "time-series"
tags:
  - "time-series-augmented-generation-tsag"
  - "similarity-driven-flow-matching"
architectures:
  []
datasets:
  []
concept_slugs:
  - "similarity-driven-flow-matching"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-10T05:20:35Z"
created_at: "2026-05-10T05:20:35Z"
---

# SDFlow: Similarity-Driven Flow Matching for Time Series Generation

**Authors**: Wei Li, Shibo Feng, Pengcheng Wu, Min Wu, Peilin Zhao
**Date**: 2026-05-07
**Paper ID**: [arxiv:2605.05736](https://arxiv.org/abs/2605.05736)

## Summary

SDFlow is a non-autoregressive generative model for time series that operates within a frozen vector-quantized (VQ) latent space using flow matching. By replacing step-wise autoregressive token prediction with a global transport map, the method eliminates exposure bias, which is a major limitation for long-horizon generation. The model further improves generation quality and computational efficiency through a low-rank manifold decomposition and the integration of categorical posterior supervision into a variational flow-matching framework.

## Key Contributions

- Introduces SDFlow, a non-autoregressive flow-matching framework that eliminates exposure bias in long-horizon time-series generation by utilizing global transport maps.
- Improves training efficiency and stability through a low-rank manifold decomposition and a learned anchor prior for VQ latent spaces.
- Achieves state-of-the-art performance on Discriminative Score and Context-FID while significantly outperforming autoregressive baselines in inference speed.

## Open Questions & Future Work

- [[universal-time-series-tokenizer]]

## Key Concepts

- [[similarity-driven-flow-matching]]: A non-autoregressive framework for parallel time-series generation that maps distributions via flow matching in a frozen VQ latent space.

## Archivist Review

The paper presents a novel approach to time-series generation by utilizing flow matching within a vector-quantized (VQ) latent space. I approved 'Similarity-Driven Flow Matching' as a reusable framework for non-autoregressive sequence generation, and 'Universal Time Series Tokenizer' as a substantial open research problem in the field. Other potential candidates were not present or were deemed too specific to the proposed implementation.

### Approved Concepts
- Similarity-Driven Flow Matching: Core framework for generating long-horizon time series without autoregressive error accumulation by using flow matching in a VQ latent space.

### Approved Open Questions
- Universal Time Series Tokenizer: A universal tokenizer would significantly enhance the generalizability and utility of generative models across diverse time-series domains, facilitating pre-training on large, heterogeneous datasets.

## Links

- [Abstract](https://arxiv.org/abs/2605.05736)
- [PDF](https://arxiv.org/pdf/2605.05736)

