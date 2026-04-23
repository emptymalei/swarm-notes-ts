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
domain: "nlp"
tags:
  - "stochastic-attention"
  - "uncertainty-quantification"
  - "calibration"
  - "transformer-foundation-models"
  - "inference-time-adaptation"
architectures:
  []
datasets:
  []
concept_slugs:
  - "stochastic-attention"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-23T05:09:39Z"
created_at: "2026-04-23T05:09:39Z"
---

# Calibrating Scientific Foundation Models with Inference-Time Stochastic Attention

**Authors**: Akash Yadav, Taiwo A. Adebiyi, Ruda Zhang
**Date**: 2026-04-21
**Paper ID**: [arxiv:2604.19530](https://arxiv.org/abs/2604.19530)

## Summary

Scientific foundation models often lack native mechanisms for calibrated uncertainty, limiting their utility in high-stakes environments. This paper proposes Stochastic Attention, an inference-time technique that randomizes attention weights using multinomial sampling to generate ensembles without model retraining. By optimizing a single concentration parameter via a univariate calibration objective, the method achieves competitive uncertainty quantification with significantly lower computational overhead than traditional retraining baselines. Results across weather and time-series forecasting tasks show enhanced calibration and sharper prediction intervals.

## Key Contributions

- Introduces Stochastic Attention, a plug-and-play inference-time method that replaces standard softmax attention with normalized multinomial sampling to generate predictive ensembles.
- Develops a post-hoc calibration objective for the concentration parameter that reduces tuning time from days of training to minutes of computation.
- Demonstrates superior calibration and sharper prediction intervals on weather and time-series benchmarks compared to existing uncertainty-aware baseline models.

## Key Concepts

- [[stochastic-attention]]: An inference-time modification to transformer attention mechanisms that produces predictive ensembles by sampling from normalized multinomial attention weights.

## Archivist Review

I approved 'Stochastic Attention' as a distinct, reusable mechanism for achieving post-hoc uncertainty quantification in transformer models. I rejected the other concepts as they represent general, well-known ML terminology that does not warrant standalone vault entries. No datasets or open questions were submitted that met the criteria for retention.

### Approved Concepts
- Stochastic Attention: It enables calibrated uncertainty quantification for pre-trained transformer-based foundation models without requiring expensive model retraining.

### Rejected Candidates
- [concept] Uncertainty Quantification (`uncertainty-quantification`) - generic: This is a broad, well-established field in statistics and machine learning, not a specific novel concept introduced by this paper.
- [concept] Calibration (`calibration`) - generic: This is a standard ML term for model performance evaluation rather than a unique technical contribution.
- [concept] Transformer Foundation Models (`transformer-foundation-models`) - generic: This is a widely used, general category of machine learning architectures.
- [concept] Inference-time Adaptation (`inference-time-adaptation`) - generic: This is a general paradigm for model deployment and adaptation that is not specific to the mechanism proposed in the paper.

## Links

- [Abstract](https://arxiv.org/abs/2604.19530)
- [PDF](https://arxiv.org/pdf/2604.19530)

