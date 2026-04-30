---
# CSL-compatible fields
title: "Beyond Fixed Formulas: Data-Driven Linear Predictor for Efficient Diffusion Models"
author:
  - literal: "Zhirong Shen"
  - literal: "Rui Huang"
  - literal: "Jiacheng Liu"
  - literal: "Chang Zou"
  - literal: "Peiliang Cai"
  - literal: "Shikang Zheng"
  - literal: "Zhengyi Shi"
  - literal: "Liang Feng"
  - literal: "Linfeng Zhang"
issued:
  date-parts:
    - [2026, 4, 29]
url: "https://arxiv.org/abs/2604.26365"

# Custom fields
paper_id: "2604.26365"
paper_source: "arxiv"
domain: "computer-vision"
tags:
  - "computer-vision"
  - "generative-models"
  - "inference-acceleration"
  - "diffusion-models"
  - "efficient-sampling"
architectures:
  []
datasets:
  []
concept_slugs:
  - "learnable-linear-predictor-l2p"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-30T05:14:08Z"
created_at: "2026-04-30T05:14:08Z"
---

# Beyond Fixed Formulas: Data-Driven Linear Predictor for Efficient Diffusion Models

**Authors**: Zhirong Shen, Rui Huang, Jiacheng Liu, Chang Zou, Peiliang Cai, Shikang Zheng, Zhengyi Shi, Liang Feng, Linfeng Zhang
**Date**: 2026-04-29
**Paper ID**: [arxiv:2604.26365](https://arxiv.org/abs/2604.26365)

## Summary

To reduce the high inference cost of Diffusion Transformers, this paper introduces L2P (Learnable Linear Predictor), a data-driven framework for feature caching. Unlike existing methods that rely on hand-crafted formulas, L2P learns per-timestep weights to accurately reconstruct features from past trajectories, allowing for more aggressive skipping during sampling. The framework is computationally efficient, requiring only ~20 seconds of training on a single GPU, and achieves significant speedups across FLUX.1-dev and Qwen-Image models. Evaluation results demonstrate that L2P consistently maintains higher visual fidelity under aggressive acceleration compared to traditional static methods.

## Key Contributions

- Introduces L2P, a data-driven caching framework that replaces heuristic forecasting formulas in Diffusion Transformers with learnable per-timestep weights.
- Achieves a 4.55x FLOPs reduction and 4.15x latency speedup on FLUX.1-dev.
- Demonstrates robust visual fidelity under up to 7.18x acceleration on Qwen-Image models, surpassing the performance of conventional fixed-formula caching.

## Open Questions & Future Work

- [[theoretical-limits-linear-diffusion-forecasting]]

## Key Concepts

- [[learnable-linear-predictor-l2p]]: A data-driven feature caching framework for Diffusion Transformers that replaces heuristic interpolation with learnable per-timestep linear weights.

## Archivist Review

The concept of Learnable Linear Predictor (L2P) is approved as a reusable, model-agnostic mechanism for diffusion inference acceleration, marking a shift from heuristic-based caching. The open question regarding the theoretical limits of such linear approximations is approved as it addresses a fundamental boundary in the efficiency scaling of diffusion models. Other candidates were not proposed, and no datasets were identified as central or reusable enough to warrant a standalone vault note.

### Approved Concepts
- Learnable Linear Predictor (L2P): It shifts from hand-crafted feature caching formulas to a data-driven approach, enabling significant acceleration in Diffusion Transformers while maintaining visual fidelity.

### Approved Open Questions
- Theoretical limits of linear diffusion forecasting: Understanding these limits is crucial for determining if performance scaling in diffusion acceleration will eventually require more complex, non-linear predictive mechanisms.

## Links

- [Abstract](https://arxiv.org/abs/2604.26365)
- [PDF](https://arxiv.org/pdf/2604.26365)

