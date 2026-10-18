---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "TimeRSI: Towards Self-Improved Agentic Deployment for Time-Series Foundation Models"
description: "TimeRSI is an agentic framework designed to bridge the gap between zero-shot time-series foundation models and task-specific deployment requirements. It employs a coding agent to translate task descriptions into executable data pipelines, which are then iteratively refined based on empirical performance feedback from historical backtesting. During inference, an adaptive selector matches the current forecasting scenario with the most effective pipeline generated during the self-improvement phase. Results across 198 tasks demonstrate that TimeRSI consistently outperforms traditional human-designed pipelines and non-iterative search methods in both point and probabilistic forecasting metrics."
resource: "https://arxiv.org/abs/2610.19725"
tags:
  - "time-series-forecasting"
  - "foundation-models"
  - "ai-agents"
  - "agentic-workflow"
  - "zero-shot-learning"
  - "automl"
  - "benchmarking"
  - "probabilistic-forecasting"
timestamp: "2026-10-18T00:43:54Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Haoxin Liu"
  - literal: "Deqing Fu"
  - literal: "Lucheng Fu"
  - literal: "Yiqiao Jin"
  - literal: "Rushi Qiang"
  - literal: "Harshavardhan Kamarthi"
  - literal: "B. Aditya Prakash"
issued:
  date-parts:
    - [2026, 10, 14]

# Domain-specific custom fields
paper_id: "2610.19725"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "timersi"
    description: "An agentic framework that wraps frozen time-series foundation models in a self-improving loop, using a coding agent to iteratively refine data processing pipelines based on historical performance feedback."
datasets:
  - name: "TIME and fev-bench"
    description: "A combined benchmark suite comprising 198 diverse forecasting tasks used to evaluate zero-shot performance and pipeline adaptation in time-series foundation models."
open_questions:
  - name: "agentic-loop-overfitting-and-convergence"
    description: "Determining how to ensure that iterative feedback loops converge on robust solutions without overfitting to the specific historical windows used for backtesting, especially in the presence of non-stationary time-series data."
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T00:43:54Z"
created_at: "2026-10-18T00:43:54Z"
---

# TimeRSI: Towards Self-Improved Agentic Deployment for Time-Series Foundation Models

**Authors**: Haoxin Liu, Deqing Fu, Lucheng Fu, Yiqiao Jin, Rushi Qiang, Harshavardhan Kamarthi, B. Aditya Prakash
**Date**: 2026-10-14
**Paper ID**: [arxiv:2610.19725](https://arxiv.org/abs/2610.19725)

## Summary

TimeRSI is an agentic framework designed to bridge the gap between zero-shot time-series foundation models and task-specific deployment requirements. It employs a coding agent to translate task descriptions into executable data pipelines, which are then iteratively refined based on empirical performance feedback from historical backtesting. During inference, an adaptive selector matches the current forecasting scenario with the most effective pipeline generated during the self-improvement phase. Results across 198 tasks demonstrate that TimeRSI consistently outperforms traditional human-designed pipelines and non-iterative search methods in both point and probabilistic forecasting metrics.

## Key Contributions

- Introduced TimeRSI, a self-improving agentic framework that automates task-specific pipeline design for frozen time-series foundation models.
- Developed a feedback-guided iteration loop where an LLM coding agent analyzes historical forecast errors to refine pipeline code.
- Implemented an adaptive selector that dynamically chooses between generated pipelines during deployment based on current condition similarity.
- Demonstrated that TimeRSI outperforms all human and automated submissions on 198 tasks across the TIME and fev-bench benchmarks.

## Limitations

The paper does not explicitly detail the computational overhead of the iterative coding agent loop during the training/refinement phase.

## Open Questions & Future Work

- [[agentic-loop-overfitting-and-convergence]]

## Key Concepts

- [[timersi]]: An agentic framework that wraps frozen time-series foundation models in a self-improving loop, using a coding agent to iteratively refine data processing pipelines based on historical performance feedback.

## Archivist Review

I approved TimeRSI as it introduces a novel agentic wrapper framework that automates the deployment of time-series foundation models. The open question regarding convergence and overfitting in these iterative loops was approved because it identifies a fundamental research bottleneck in autonomous code generation for non-stationary data. The combined benchmark suite (TIME/fev-bench) is approved as the central evaluation standard for this task.

### Approved Concepts
- TimeRSI: TimeRSI addresses the 'last-mile' deployment gap for zero-shot foundation models by automating task-specific engineering, which is often the primary bottleneck in industrial time-series applications.

### Approved Open Questions
- Convergence and Overfitting in Agentic Revision Loops: If agentic loops overfit to specific validation windows, the generated pipelines may fail under distribution shift, undermining the reliability of autonomous deployment systems.

### Rejected Candidates
- [concept] Agentic Deployment (`agentic-deployment`) - generic: This is a broad industry paradigm for using agents in software deployment, not a specific technical mechanism introduced by the paper.
- [concept] Adaptive Selector (`adaptive-selector`) - subcomponent_of_broader_mechanism: The adaptive selector is a specific internal component of the TimeRSI framework rather than an independently reusable concept.

## Datasets

- [[TIME and fev-bench]]

## Links

- [Abstract](https://arxiv.org/abs/2610.19725)
- [PDF](https://arxiv.org/pdf/2610.19725)

