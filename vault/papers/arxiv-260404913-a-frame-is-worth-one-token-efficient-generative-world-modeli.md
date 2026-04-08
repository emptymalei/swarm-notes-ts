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
domain: "nlp"
tags:
  - "forecasting"
  - "generative-models"
  - "video-modeling"
architectures:
  []
datasets:
  []
concept_slugs:
  - "delta-tokens"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-08T04:58:27Z"
created_at: "2026-04-08T04:58:27Z"
---

# A Frame is Worth One Token: Efficient Generative World Modeling with Delta Tokens

**Authors**: Tommie Kerssies, Gabriele Berton, Ju He, Qihang Yu, Wufei Ma, Daan de Geus, Gijs Dubbelman, Liang-Chieh Chen
**Date**: 2026-04-06
**Paper ID**: [arxiv:2604.04913](https://arxiv.org/abs/2604.04913)

## Summary

The authors introduce DeltaWorld, a generative world model that leverages a novel tokenization scheme called DeltaTok to perform efficient, diverse video forecasting. By encoding only the feature-level differences between consecutive frames from a Vision Foundation Model into a single continuous 'delta' token, the method reduces 3D spatio-temporal video data to a compact 1D temporal sequence. This efficiency allows for parallel multi-hypothesis training and inference, achieving superior performance on dense forecasting tasks with significantly reduced parameter counts and computational costs.

## Key Contributions

- Introduces DeltaTok, a novel tokenizer that compresses video sequences by capturing feature-level changes into single continuous tokens.
- Presents DeltaWorld, a generative world model that utilizes Delta tokens to achieve high-diversity future prediction with minimal compute.
- Demonstrates 35x parameter reduction and 2,000x fewer FLOPs compared to state-of-the-art generative world models while improving alignment with real-world outcomes.

## Open Questions & Future Work

- [[generative-world-model-distributional-modeling]]
- [[autoregressive-error-accumulation-delta-tokens]]

## Key Concepts

- [[delta-tokens]]: A video tokenization paradigm that encodes feature-level differences between consecutive latent frames into single, continuous delta tokens.

## Archivist Review

I approved the core concept of Delta Tokens and two high-level open questions regarding the distributional foundations and stability of generative sequence models. The rejection of DeltaWorld as a separate concept followed the policy to prefer the overarching mechanism (Delta Tokens) over implementation-specific wrappers. I also updated the open question on error accumulation to reuse existing naming conventions for consistency with the vault.

### Approved Concepts
- Delta Tokens: Enables significant compression of high-dimensional video data into compact temporal sequences, facilitating efficient generative world modeling.

### Approved Open Questions
- Principled Distributional Modeling Objectives: Establishing a principled objective is critical for ensuring the reliability and statistical validity of predictions in safety-critical applications.
- Long-term Autoregressive Error Accumulation: Long-horizon forecasting accuracy is a fundamental requirement for temporal world modeling, and addressing drift is essential for sequence stability.

## Links

- [Abstract](https://arxiv.org/abs/2604.04913)
- [PDF](https://arxiv.org/pdf/2604.04913)

