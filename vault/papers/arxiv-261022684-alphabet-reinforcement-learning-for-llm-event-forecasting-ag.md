---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "AlphaBet: Reinforcement Learning for LLM Event Forecasting Agents"
description: "AlphaBet is an agentic reinforcement learning framework that trains LLMs to perform event forecasting by integrating search, reasoning, and probabilistic reporting into a single policy. The framework utilizes multi-date training, scoring predictions at various intervals before an event resolves against the final ground-truth outcome using proper scoring rules. The authors demonstrate that this approach significantly improves Brier scores on Forecast-Dojo and FutureX benchmarks while identifying a critical flaw in GRPO's normalization that can degrade probability calibration in multi-class settings."
resource: "https://arxiv.org/abs/2610.22684"
tags:
  - "llm-agents"
  - "reinforcement-learning"
  - "forecasting"
  - "agentic-workflow"
  - "time-series"
  - "multi-step-forecasting"
  - "optimization"
timestamp: "2026-10-19T04:39:20Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Liqin Ye"
  - literal: "Rongzhi Zhang"
  - literal: "Xin Liu"
  - literal: "Zheng Li"
  - literal: "Yuan He"
  - literal: "Qingyu Yin"
  - literal: "Priyanka Nigam"
  - literal: "Chao Zhang"
issued:
  date-parts:
    - [2026, 10, 15]

# Domain-specific custom fields
paper_id: "2610.22684"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "alphabet-forecasting-framework"
    description: "An agentic reinforcement learning framework for training LLMs to perform end-to-end event forecasting through autonomous search, reasoning, and multi-date probability reporting."
  - name: "multi-date-rl-training"
    description: "A training strategy that supervises an agent's decisions at various dates before an event's resolution using the final ground-truth outcome and proper scoring rules."
datasets:
  - name: "Forecast-Dojo"
    description: "A benchmark for event forecasting tasks used to evaluate LLM performance in evidence-based prediction across multiple temporal points."
open_questions:
  - name: "longitudinal-forecasting-credit-assignment"
    description: "In multi-step forecasting episodes where an agent maintains a belief notebook or memory, decisions made at early stages (such as specific search queries or notes taken) significantly influence the quality of forecasts at later stages. Existing methods lack a mechanism for cross-date credit assignment, where rewards from later, potentially more informed forecasts are propagated back to earlier reasoning and evidence-gathering actions. Developing such a mechanism is necessary to optimize long-term information-retention strategies."
skill: "TimeSeriesSkill"
processed_at: "2026-10-19T04:39:20Z"
created_at: "2026-10-19T04:39:20Z"
---

# AlphaBet: Reinforcement Learning for LLM Event Forecasting Agents

**Authors**: Liqin Ye, Rongzhi Zhang, Xin Liu, Zheng Li, Yuan He, Qingyu Yin, Priyanka Nigam, Chao Zhang
**Date**: 2026-10-15
**Paper ID**: [arxiv:2610.22684](https://arxiv.org/abs/2610.22684)

## Summary

AlphaBet is an agentic reinforcement learning framework that trains LLMs to perform event forecasting by integrating search, reasoning, and probabilistic reporting into a single policy. The framework utilizes multi-date training, scoring predictions at various intervals before an event resolves against the final ground-truth outcome using proper scoring rules. The authors demonstrate that this approach significantly improves Brier scores on Forecast-Dojo and FutureX benchmarks while identifying a critical flaw in GRPO's normalization that can degrade probability calibration in multi-class settings.

## Key Contributions

- Developed AlphaBet, an agentic RL framework that enables LLMs to autonomously search for evidence and report calibrated probabilities in an end-to-end learning loop.
- Proposed a multi-date training protocol that leverages the final resolution of an event to supervise forecasting decisions across different pre-resolution information states.
- Formally decomposed forecasting regret into an evidence-acquisition gap and a probability-reporting gap, providing a framework for analyzing agentic forecaster failures.
- Identified a systematic failure mode in Group Relative Policy Optimization (GRPO) where standard-deviation normalization distorts multi-class proper scoring rule performance.

## Limitations

The study notes that while top-outcome accuracy remains stable, GRPO's normalization degrades the calibration required for proper scoring, which is critical for probabilistic forecasting.

## Open Questions & Future Work

- [[longitudinal-forecasting-credit-assignment]]

## Key Concepts

- [[alphabet-forecasting-framework]]: An agentic reinforcement learning framework for training LLMs to perform end-to-end event forecasting through autonomous search, reasoning, and multi-date probability reporting.
- [[multi-date-rl-training]]: A training strategy that supervises an agent's decisions at various dates before an event's resolution using the final ground-truth outcome and proper scoring rules.

## Archivist Review

I approved AlphaBet as the primary architectural contribution and Multi-date RL Training as a reusable supervision strategy for event forecasting. Forecast-Dojo was approved as a significant benchmark dataset for this domain. The open question regarding credit assignment across dates captures a critical bottleneck in longitudinal agentic systems. FutureX was rejected as a duplicate of an existing vault entry.

### Approved Concepts
- AlphaBet Forecasting Framework: AlphaBet is the first framework to integrate autonomous search, longitudinal reasoning, and probabilistic reporting into a single end-to-end RL policy for event forecasting.
- Multi-date RL Training: This strategy addresses data scarcity in event forecasting by extracting multiple training signals from a single resolved event across different pre-resolution timestamps.

### Approved Open Questions
- Cross-Date Credit Assignment: Optimizing search and memory strategies requires the ability to link early evidence-gathering actions to eventual forecasting success at the end of a temporal horizon.

### Rejected Candidates
- [dataset] FutureX (`futurex`) - duplicate_existing: The vault already contains futurex-past-derived-dataset, which is the full name of this benchmark suite.
- [concept] Forecasting Regret Decomposition (`forecasting-regret-decomposition`) - paper_local: This is a diagnostic framework used for analysis in the paper rather than a reusable model architecture or training method.
- [concept] GRPO Normalization Distortion (`grpo-normalization-distortion`) - not_novel: This is an empirical observation and critique of an existing algorithm (GRPO) rather than a novel conceptual contribution.

## Datasets

- [[Forecast-Dojo]]

## Links

- [Abstract](https://arxiv.org/abs/2610.22684)
- [PDF](https://arxiv.org/pdf/2610.22684)

