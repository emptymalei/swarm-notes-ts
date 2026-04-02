---
# CSL-compatible fields
title: "One-for-All: A Lightweight Stabilized and Parameter-Efficient Pre-trained LLM for Time Series Forecasting"
author:
  - literal: "Prasanjit Dey"
  - literal: "Soumyabrata Dev"
  - literal: "Bianca Schoen-Phelan"
issued:
  date-parts:
    - [2026, 3, 31]
url: "https://arxiv.org/abs/2603.29756"

# Custom fields
paper_id: "2603.29756"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "gaussian-rank-stabilized-lora-rslora"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-04-02T05:40:05Z"
created_at: "2026-04-02T05:40:05Z"
---

# One-for-All: A Lightweight Stabilized and Parameter-Efficient Pre-trained LLM for Time Series Forecasting

**Authors**: Prasanjit Dey, Soumyabrata Dev, Bianca Schoen-Phelan
**Date**: 2026-03-31
**Paper ID**: [arxiv:2603.29756](https://arxiv.org/abs/2603.29756)

## Summary

One-for-All proposes an efficient framework for adapting frozen Large Language Models to multivariate time-series forecasting using a novel Gaussian Rank-Stabilized LoRA (rsLoRA). By injecting trainable rank-decomposition matrices into positional embeddings and output layers while keeping self-attention fixed, the model achieves drastic reductions in parameter count and memory footprint compared to state-of-the-art methods like GPT4TS and TIME-LLM. The method ensures provable gradient stability, facilitating consistent high-accuracy forecasting across diverse time horizons and benchmarks, suitable for resource-constrained edge deployment.

## Key Contributions

- Introduces One-for-All, a framework using rsLoRA to adapt frozen LLMs for multivariate time-series forecasting with significantly reduced memory and parameter requirements.
- Develops Gaussian Rank-Stabilized LoRA (rsLoRA) which provides mathematically grounded gradient stability for low-rank adapter training.
- Achieves state-of-the-art efficiency-accuracy trade-offs, demonstrating up to 21x fewer trainable parameters than existing LLM-based forecasters like GPT4TS.
- Validates performance consistency across forecasting horizons of 96-720 steps on standard benchmarks (ETT, Weather, M3, M4).

## Limitations

The current implementation focuses on keeping self-attention weights fixed, which may limit the model's capacity to learn complex cross-temporal dependencies compared to methods that fine-tune attention mechanisms.

## Open Questions & Future Work

- [[unified-llm-time-series-generalization]]

## Key Concepts

- [[gaussian-rank-stabilized-lora-rslora]]: A PEFT method that applies Gaussian rank-stabilization to low-rank adapter matrices to ensure gradient stability during LLM adaptation.

## Archivist Review

I have approved the core methodological contribution (rsLoRA) and the high-level research direction concerning generalizability in LLM-based time-series forecasting. The datasets (ETT, M3, M4) were rejected as they are standard benchmarks in the field rather than unique contributions of this work. The review focused on selecting the most impactful and reusable components for the vault.

### Approved Concepts
- Gaussian Rank-Stabilized LoRA (rsLoRA): It introduces a mathematically grounded rank-stabilization mechanism providing provable gradient stability at low ranks for PEFT.

### Approved Open Questions
- Unified Time-Series Generalization: Achieving a truly unified, cross-domain temporal foundation model would significantly reduce the computational and data labeling burdens currently required to deploy LLMs across the varied landscape of industrial and scientific time-series tasks.

## Links

- [Abstract](https://arxiv.org/abs/2603.29756)
- [PDF](https://arxiv.org/pdf/2603.29756)

