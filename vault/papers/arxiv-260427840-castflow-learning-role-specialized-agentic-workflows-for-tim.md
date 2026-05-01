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
  - "nlp"
architectures:
  []
datasets:
  []
concept_slugs:
  - "castflow"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-01T05:22:37Z"
created_at: "2026-05-01T05:22:37Z"
---

# CastFlow: Learning Role-Specialized Agentic Workflows for Time Series Forecasting

**Authors**: Bokai Pan, Mingyue Cheng, Zhiding Liu, Shuo Yu, Xiaoyu Tao, Yuchong Wu, Qi Liu, Defu Lian, Enhong Chen
**Date**: 2026-04-30
**Paper ID**: [arxiv:2604.27840](https://arxiv.org/abs/2604.27840)

## Summary

CastFlow is an agentic framework designed to move time series forecasting beyond static generative paradigms. By organizing the process into planning, action, forecasting, and reflection stages, the system employs role-specialized agents to perform multi-view pattern extraction and iterative forecast refinement. The framework integrates a memory module and a multi-view toolkit, leveraging an ensemble forecast as a reliable baseline for domain-specific LLMs to improve numerical accuracy. Extensive experiments demonstrate that CastFlow consistently outperforms static forecasting baselines.

## Key Contributions

- Proposes CastFlow, a dynamic agentic forecasting framework that replaces static generation with multi-view temporal extraction, iterative refinement, and ensemble-based forecasting.
- Implements a role-specialized design that separates general-purpose reasoning from domain-specific numerical forecasting via a frozen and fine-tuned LLM duo.
- Develops a two-stage workflow-oriented training strategy combining supervised fine-tuning (SFT) and reinforcement learning with verifiable rewards (RLVR) to optimize agent performance.

## Open Questions & Future Work

- [[balancing-reasoning-and-numerical-forecasting]]

## Key Concepts

- [[castflow]]: A dynamic agentic forecasting framework that utilizes role-specialized agents and iterative refinement to enhance time series prediction accuracy.

## Archivist Review

I approved the CastFlow framework as a representative agentic workflow for time series, which is a novel structural approach compared to static generation. The open question regarding the balance between reasoning and numerical accuracy addresses a fundamental architectural tension in current LLM-based forecasting research. Other candidates were either too specific to the implementation or lacked the necessary generality for permanent storage.

### Approved Concepts
- CastFlow: Provides a structured approach to agentic time series forecasting, moving away from static generative paradigms.

### Approved Open Questions
- Unifying reasoning and numerical performance: This is a foundational bottleneck in LLM-based time series forecasting, impacting their application in high-stakes, real-world scenarios.

## Links

- [Abstract](https://arxiv.org/abs/2604.27840)
- [PDF](https://arxiv.org/pdf/2604.27840)

