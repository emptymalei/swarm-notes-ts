---
# CSL-compatible fields
title: "CastFlow: Learning Role-Specialized Agentic Workflows for Time Series Forecasting"
author:
  - literal: "Bokai Pan"
  - literal: "Mingyue Cheng"
  - literal: "Zhiding Liu"
  - literal: "Shuo Yu"
  - literal: "Xiaoyu Tao"
  - literal: "Yuchong Wu"
  - literal: "Qi Liu"
  - literal: "Defu Lian"
  - literal: "Enhong Chen"
issued:
  date-parts:
    - [2026, 4, 30]
url: "https://arxiv.org/abs/2604.27840"

# Custom fields
paper_id: "2604.27840"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "forecasting"
  - "llm"
  - "agentic-workflow"
architectures:
  []
datasets:
  []
concept_slugs:
  - "castflow"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-02T05:07:52Z"
created_at: "2026-05-02T05:07:52Z"
---

# CastFlow: Learning Role-Specialized Agentic Workflows for Time Series Forecasting

**Authors**: Bokai Pan, Mingyue Cheng, Zhiding Liu, Shuo Yu, Xiaoyu Tao, Yuchong Wu, Qi Liu, Defu Lian, Enhong Chen
**Date**: 2026-04-30
**Paper ID**: [arxiv:2604.27840](https://arxiv.org/abs/2604.27840)

## Summary

CastFlow is a dynamic agentic forecasting framework that transitions from static, single-pass generative models to a multi-stage workflow involving planning, action, forecasting, and reflection. By utilizing a role-specialized design, it leverages a frozen LLM for reasoning and a fine-tuned domain-specific LLM for numerical forecasting, supported by an ensemble-based multi-view toolkit. This approach enables iterative forecast refinement and evidence-based predictions, significantly improving forecasting performance on diverse benchmarks.

## Key Contributions

- CastFlow implements a novel dynamic agentic forecasting workflow consisting of planning, action, forecasting, and reflection to overcome the limitations of static single-pass generative paradigms.
- Introduces a role-specialized architecture that separates general-purpose reasoning (frozen LLM) from evidence-guided numerical forecasting (fine-tuned domain-specific LLM).
- Develops a two-stage workflow-oriented training strategy utilizing supervised fine-tuning (SFT) and reinforcement learning with verifiable rewards (RLVR) to optimize forecast accuracy.

## Open Questions & Future Work

- [[generalizing-agentic-forecasting-to-noisy-domains]]

## Key Concepts

- [[castflow]]: A dynamic agentic framework for time series forecasting that decomposes the process into planning, action, forecasting, and reflection stages using role-specialized LLMs.

## Archivist Review

The paper provides a distinct architectural approach to time series forecasting by formalizing a multi-stage agentic workflow (planning, action, forecasting, reflection). I approved CastFlow as a novel forecasting paradigm and the open question regarding its generalization across noisy, heterogeneous domains, as these address significant bottlenecks in moving beyond single-pass LLM generation.

### Approved Concepts
- CastFlow: It is the core contribution of the paper, introducing a dynamic agentic paradigm for time series forecasting that replaces static generation with planning, reflection, and iterative refinement.

### Approved Open Questions
- Generalizing Agentic Forecasting Performance: The inability to maintain performance across all temporal domains, particularly when diagnostic evidence provides conflicting or non-predictive signals, represents a fundamental bottleneck for deploying agentic forecasting systems in heterogeneous real-world infrastructures.

## Links

- [Abstract](https://arxiv.org/abs/2604.27840)
- [PDF](https://arxiv.org/pdf/2604.27840)

