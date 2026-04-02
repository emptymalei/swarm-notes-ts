---
# CSL-compatible fields
title: "Meteorology-Driven GPT4AP: A Multi-Task Forecasting LLM for Atmospheric Air Pollution in Data-Scarce Settings"
author:
  - literal: "Prasanjit Dey"
  - literal: "Soumyabrata Dev"
  - literal: "Bianca Schoen-Phelan"
issued:
  date-parts:
    - [2026, 3, 31]
url: "https://arxiv.org/abs/2603.29974"

# Custom fields
paper_id: "2603.29974"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "gaussian-rslora-forecasting"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-04-02T05:39:35Z"
created_at: "2026-04-02T05:39:35Z"
---

# Meteorology-Driven GPT4AP: A Multi-Task Forecasting LLM for Atmospheric Air Pollution in Data-Scarce Settings

**Authors**: Prasanjit Dey, Soumyabrata Dev, Bianca Schoen-Phelan
**Date**: 2026-03-31
**Paper ID**: [arxiv:2603.29974](https://arxiv.org/abs/2603.29974)

## Summary

GPT4AP is a parameter-efficient forecasting framework designed for air pollution monitoring in data-scarce environments. It leverages a pre-trained GPT-2 backbone adapted with Gaussian rank-stabilized LoRA (rsLoRA) to freeze core weights while training only lightweight positional and output modules. Experimental results across six air quality datasets show the framework excels in few-shot and zero-shot transfer scenarios compared to existing time-series baselines. The approach provides a robust strategy for deploying forecasting models in regions with limited ground-truth observations.

## Key Contributions

- Introduced GPT4AP, a multi-task forecasting framework utilizing a frozen GPT-2 backbone with Gaussian rank-stabilized LoRA to enable effective learning with limited data.
- Achieved superior performance in few-shot regimes (10% data) with an MSE of 0.686 and MAE of 0.442, outperforming established baselines like DLinear and ETSformer.
- Demonstrated strong zero-shot cross-station transferability for air quality monitoring, yielding an average MSE of 0.529 and MAE of 0.403.

## Limitations

While highly effective in data-scarce and transfer learning scenarios, the model is slightly outperformed by specialized time-series architectures in full-data long-term forecasting settings.

## Open Questions & Future Work

- [[hybrid-llm-temporal-modeling]]

## Key Concepts

- [[gaussian-rslora-forecasting]]: A parameter-efficient adaptation technique for fine-tuning pre-trained language model backbones on spatiotemporal forecasting tasks using Gaussian rank-stabilized LoRA.

## Archivist Review

The paper introduces a specific application of LLM adaptation (rsLoRA) to air quality forecasting. I approved the adaptation technique as a reusable concept and the open question regarding hybridizing foundation models with temporal inductive biases, as both are central to current trends in applying LLMs to domain-specific forecasting. The GPT4AP model itself was rejected as a paper-local instance.

### Approved Concepts
- Gaussian rank-stabilized LoRA (rsLoRA) for forecasting: Represents a specific architectural strategy for repurposing generative foundation models for specialized time-series forecasting, bridging the gap between LLM adaptation techniques and domain-specific modeling.

### Approved Open Questions
- Hybrid LLM-Temporal Architectures: This is a critical architectural trade-off that defines the utility of foundation models in specialized physical science domains.

### Rejected Candidates
- [concept] GPT4AP (`gpt4ap`) - paper_local: This is a specific application instance rather than a generally reusable methodological framework.

## Links

- [Abstract](https://arxiv.org/abs/2603.29974)
- [PDF](https://arxiv.org/pdf/2603.29974)

