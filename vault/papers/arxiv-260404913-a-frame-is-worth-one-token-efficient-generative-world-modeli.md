---
# CSL-compatible fields
title: "A Frame is Worth One Token: Efficient Generative World Modeling with Delta Tokens"
author:
  - literal: "Tommie Kerssies"
  - literal: "Gabriele Berton"
  - literal: "Ju He"
  - literal: "Qihang Yu"
  - literal: "Wufei Ma"
  - literal: "Daan de Geus"
  - literal: "Gijs Dubbelman"
  - literal: "Liang-Chieh Chen"
issued:
  date-parts:
    - [2026, 4, 6]
url: "https://arxiv.org/abs/2604.04913"

# Custom fields
paper_id: "2604.04913"
paper_source: "arxiv"
domain: "computer-vision"
tags:
  - "computer-vision"
  - "generative-models"
  - "video-generation"
architectures:
  []
datasets:
  []
concept_slugs:
  - "delta-tokens"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-07T04:52:57Z"
created_at: "2026-04-07T04:52:57Z"
---

# A Frame is Worth One Token: Efficient Generative World Modeling with Delta Tokens

**Authors**: Tommie Kerssies, Gabriele Berton, Ju He, Qihang Yu, Wufei Ma, Daan de Geus, Gijs Dubbelman, Liang-Chieh Chen
**Date**: 2026-04-06
**Paper ID**: [arxiv:2604.04913](https://arxiv.org/abs/2604.04913)

## Summary

This paper presents DeltaWorld, an efficient generative world model that improves upon existing computationally expensive approaches by utilizing a novel tokenization scheme called DeltaTok. DeltaTok compresses video sequences by encoding differences in vision foundation model (VFM) feature space between consecutive frames into single continuous delta tokens, achieving significant data reduction. By operating on these compact temporal sequences, DeltaWorld enables parallel multi-hypothesis training and inference, leading to diverse and realistic future predictions with drastically reduced parameter and FLOP requirements.

## Key Contributions

- Introduced DeltaTok, a tokenizer that compresses spatio-temporal video data into a 1D sequence of delta tokens by capturing VFM feature differences between consecutive frames.
- Proposed DeltaWorld, a generative world model that leverages delta tokens for efficient, parallelized multi-hypothesis future prediction.
- Achieved over 35x fewer parameters and 2,000x fewer FLOPs compared to existing generative world models while improving alignment with real-world outcomes on dense forecasting tasks.

## Open Questions & Future Work

- [[generative-world-model-distributional-modeling]]
- [[autoregressive-error-accumulation-delta-tokens]]

## Key Concepts

- [[delta-tokens]]: A video compression approach that encodes frame-to-frame changes in vision foundation model feature space as a single continuous vector.

## Archivist Review

The paper introduces Delta Tokens as a novel approach to compress video into one-dimensional feature-space sequences, which is highly relevant for efficient world modeling. I have approved this concept along with two significant open questions concerning the distributional validity of best-of-many generative strategies and the structural challenge of autoregressive error accumulation when using differential tokens. These items meet the criteria for long-term relevance in time-series and video forecasting research.

### Approved Concepts
- Delta Tokens: This tokenization scheme serves as a highly efficient mechanism for compressing video into one-dimensional temporal sequences, suitable for generative world models.

### Approved Open Questions
- Formal Distributional Objectives: This is necessary to transition from producing mere 'plausible' futures to generating statistically accurate and representative scenarios for reliable decision-making.
- Mitigating Autoregressive Error Accumulation: Solving the drift and compounding error issue is essential for robust long-term temporal sequence prediction.

## Links

- [Abstract](https://arxiv.org/abs/2604.04913)
- [PDF](https://arxiv.org/pdf/2604.04913)

