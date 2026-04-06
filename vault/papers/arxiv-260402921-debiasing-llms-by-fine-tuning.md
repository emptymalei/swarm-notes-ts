---
# CSL-compatible fields
title: "Debiasing LLMs by Fine-tuning"
author:
  - literal: "Zhenyu Gao"
  - literal: "Wenxi Jiang"
  - literal: "Yutong Yan"
issued:
  date-parts:
    - [2026, 4, 3]
url: "https://arxiv.org/abs/2604.02921"

# Custom fields
paper_id: "2604.02921"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "debiasing-via-instruction-fine-tuning"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-06T05:02:33Z"
created_at: "2026-04-06T05:02:33Z"
---

# Debiasing LLMs by Fine-tuning

**Authors**: Zhenyu Gao, Wenxi Jiang, Yutong Yan
**Date**: 2026-04-03
**Paper ID**: [arxiv:2604.02921](https://arxiv.org/abs/2604.02921)

## Summary

This paper addresses the systematic extrapolation bias observed in LLMs when making predictions from data. The authors propose a supervised fine-tuning (SFT) method using Low-Rank Adaptation (LoRA) on instruction datasets derived from rational benchmark forecasts. By intervening at the parameter level, this approach alters the model's mapping of information to forecasts, effectively mitigating extrapolation bias in both controlled experiments and financial market forecasting.

## Key Contributions

- Introduces a supervised fine-tuning (SFT) approach utilizing LoRA to mitigate systematic extrapolation bias in LLMs during forecasting tasks.
- Demonstrates that parameter-level interventions effectively alter how LLMs map observed information into predictions compared to prompt-based debiasing.
- Evaluates the method's efficacy in both controlled forecasting experiments and cross-sectional stock return prediction, showing consistent out-of-sample bias reduction.

## Open Questions & Future Work

- [[long-term-impact-of-sft-debiasing]]

## Key Concepts

- [[debiasing-via-instruction-fine-tuning]]: A supervised fine-tuning method using LoRA to align LLM forecasting behavior with rational benchmarks to mitigate systematic extrapolation bias.

## Archivist Review

The paper provides a clean, replicable approach to mitigating LLM forecasting bias through targeted fine-tuning rather than prompt engineering. The approved concepts and questions focus on the mechanism of parameter-level alignment and the subsequent risks to general model integrity, which are highly relevant to the long-term reliability of foundation models in forecasting contexts.

### Approved Concepts
- Debiasing via Instruction Fine-tuning: Addresses systematic extrapolation bias in LLMs through parameter-level intervention rather than prompting.

### Approved Open Questions
- Long-term impact of SFT-debiasing: Understanding the trade-offs between domain-specific bias correction and general model performance is essential for deploying reliable, autonomous AI agents in high-stakes environments.

## Links

- [Abstract](https://arxiv.org/abs/2604.02921)
- [PDF](https://arxiv.org/pdf/2604.02921)

