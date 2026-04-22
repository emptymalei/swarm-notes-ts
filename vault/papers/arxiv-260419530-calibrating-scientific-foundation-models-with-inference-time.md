---
# CSL-compatible fields
title: "Calibrating Scientific Foundation Models with Inference-Time Stochastic Attention"
author:
  - literal: "Akash Yadav"
  - literal: "Taiwo A. Adebiyi"
  - literal: "Ruda Zhang"
issued:
  date-parts:
    - [2026, 4, 21]
url: "https://arxiv.org/abs/2604.19530"

# Custom fields
paper_id: "2604.19530"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "stochastic-attention"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-22T05:03:31Z"
created_at: "2026-04-22T05:03:31Z"
---

# Calibrating Scientific Foundation Models with Inference-Time Stochastic Attention

**Authors**: Akash Yadav, Taiwo A. Adebiyi, Ruda Zhang
**Date**: 2026-04-21
**Paper ID**: [arxiv:2604.19530](https://arxiv.org/abs/2604.19530)

## Summary

This paper addresses the lack of calibrated uncertainty in deterministic scientific foundation models by introducing Stochastic Attention. This lightweight technique modifies the attention mechanism at inference time, replacing softmax weights with multinomial samples to generate predictive ensembles without the need for retraining. An associated calibration objective allows for efficient post-hoc tuning of the output, resulting in significantly improved prediction intervals and coverage on scientific forecasting tasks compared to current baselines.

## Key Contributions

- Introduced Stochastic Attention, an inference-time modification that converts deterministic attention heads into probabilistic ensembles via multinomial sampling.
- Developed a univariate calibration objective that enables efficient post-hoc tuning of predictive uncertainty with minimal computational overhead.
- Demonstrated that Stochastic Attention achieves superior calibration and sharper prediction intervals on weather and time-series forecasting benchmarks compared to existing uncertainty-aware baselines.

## Key Concepts

- [[stochastic-attention]]: An inference-time modification to transformer attention mechanisms that produces calibrated predictive ensembles via multinomial sampling.

## Archivist Review

I approved Stochastic Attention because it provides a highly reusable, model-agnostic method for transforming deterministic transformers into uncertainty-aware probabilistic models without retraining. I chose not to propose new open questions, as the paper's calibration objective is presented as a solved efficiency problem, and no major foundational bottlenecks were highlighted beyond general performance. No datasets were approved as none were uniquely identified by name in the analysis.

### Approved Concepts
- Stochastic Attention: It enables uncertainty quantification in deterministic foundation models through a plug-and-play inference-time modification, avoiding costly retraining.

## Links

- [Abstract](https://arxiv.org/abs/2604.19530)
- [PDF](https://arxiv.org/pdf/2604.19530)

