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
domain: "nlp"
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
processed_at: "2026-05-03T05:14:37Z"
created_at: "2026-05-03T05:14:37Z"
---

# CastFlow: Learning Role-Specialized Agentic Workflows for Time Series Forecasting

**Authors**: Bokai Pan, Mingyue Cheng, Zhiding Liu, Shuo Yu, Xiaoyu Tao, Yuchong Wu, Qi Liu, Defu Lian, Enhong Chen
**Date**: 2026-04-30
**Paper ID**: [arxiv:2604.27840](https://arxiv.org/abs/2604.27840)

## Summary

CastFlow is an agentic framework for time series forecasting that moves beyond static, one-shot generative paradigms by utilizing iterative, multi-view, and ensemble-based processes. The framework organizes the forecasting task into specialized planning, action, and reflection agents supported by a memory module and diagnostic toolkits. By leveraging a role-specialized design that combines frozen general reasoning with fine-tuned domain-specific numerical forecasting, CastFlow achieves superior accuracy on diverse forecasting benchmarks. A workflow-oriented training approach further ensures the system effectively learns to integrate evidence and ensemble baselines.

## Key Contributions

- Introduces CastFlow, an agentic forecasting framework that decomposes the task into planning, action, forecasting, and reflection stages.
- Employs a role-specialized architecture by combining frozen LLM reasoning with a fine-tuned, domain-specific model for numerical evidence-guided forecasting.
- Develops a two-stage workflow-oriented training strategy utilizing supervised fine-tuning and reinforcement learning with verifiable rewards (RLVR).

## Open Questions & Future Work

- [[balancing-reasoning-and-precision-in-llm-forecasting]]

## Key Concepts

- [[castflow]]: An agentic time series forecasting framework that uses role-specialized agents to perform iterative multi-view temporal analysis and forecast refinement.

## Archivist Review

I approved the 'CastFlow' framework as it introduces a reusable agentic paradigm for time series analysis that decouples general reasoning from numerical tasks. The open question 'Balancing Reasoning and Precision' was approved as it effectively captures the core technical bottleneck in LLM-based time series modeling. No datasets were approved because the paper did not propose or highlight a single novel dataset, but rather used diverse existing benchmarks.

### Approved Concepts
- CastFlow: The paper introduces an agentic forecasting workflow that decomposes time series analysis into multi-stage tasks (planning, action, reflection), which is a distinct departure from single-pass generative models.

### Approved Open Questions
- Balancing Reasoning and Precision: This bottleneck characterizes the fundamental trade-off in modern LLM-driven forecasting systems and is crucial for measuring progress in the field.

## Links

- [Abstract](https://arxiv.org/abs/2604.27840)
- [PDF](https://arxiv.org/pdf/2604.27840)

