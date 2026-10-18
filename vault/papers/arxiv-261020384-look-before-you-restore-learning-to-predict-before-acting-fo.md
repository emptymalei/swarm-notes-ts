---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Look Before You Restore: Learning to Predict Before Acting for Agentic Image Restoration"
description: "This paper introduces PreActIR, an agentic framework for mixed-degradation image restoration that employs a tool-conditioned world model to predict the consequences of actions before execution. Unlike traditional reactive agents that rely on trial-and-error, PreActIR forecasts changes in image quality, fidelity, and potential risks, allowing it to rank and select the most promising restoration tools while avoiding harmful or redundant calls. The system includes an independent verifier for commitment/rollback and demonstrates significant efficiency gains, reducing rejected tool calls by over 60% while simultaneously improving restoration accuracy (PSNR) on complex degradation tasks."
resource: "https://arxiv.org/abs/2610.20384"
tags:
  - "computer-vision"
  - "agentic-workflow"
  - "world-models"
  - "uncertainty-estimation"
  - "decision-making"
  - "efficiency"
  - "robustness"
timestamp: "2026-10-18T00:33:01Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Xu Zhang"
  - literal: "Jun Wan"
  - literal: "Lefei Zhang"
  - literal: "Liangpei Zhang"
issued:
  date-parts:
    - [2026, 10, 14]

# Domain-specific custom fields
paper_id: "2610.20384"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "pre-act-ir"
    description: "An agentic image restoration framework that uses a tool-conditioned world model to forecast the outcomes and risks of candidate restoration tools before they are executed."
  - name: "tool-conditioned-world-model"
    description: "A predictive model that simulates the effect of specific image processing tools or discrete actions on environment states, including quality metrics and execution risk."
datasets:
  []
open_questions:
  - name: "targeted-tool-adaptation-gap-analysis"
    description: "How can agentic systems automatically identify gaps in their toolsets and perform targeted adaptation or synthesis of new tools to resolve specific failure modes?"
skill: "GeneralMLSkill"
processed_at: "2026-10-18T00:33:01Z"
created_at: "2026-10-18T00:33:01Z"
---

# Look Before You Restore: Learning to Predict Before Acting for Agentic Image Restoration

**Authors**: Xu Zhang, Jun Wan, Lefei Zhang, Liangpei Zhang
**Date**: 2026-10-14
**Paper ID**: [arxiv:2610.20384](https://arxiv.org/abs/2610.20384)

## Summary

This paper introduces PreActIR, an agentic framework for mixed-degradation image restoration that employs a tool-conditioned world model to predict the consequences of actions before execution. Unlike traditional reactive agents that rely on trial-and-error, PreActIR forecasts changes in image quality, fidelity, and potential risks, allowing it to rank and select the most promising restoration tools while avoiding harmful or redundant calls. The system includes an independent verifier for commitment/rollback and demonstrates significant efficiency gains, reducing rejected tool calls by over 60% while simultaneously improving restoration accuracy (PSNR) on complex degradation tasks.

## Key Contributions

- Proposed PreActIR, a predictive agentic framework for image restoration that replaces reactive trial-and-error with a 'look-before-acting' strategy using a tool-conditioned world model.
- Introduced a multi-objective forecasting mechanism that predicts residual degradation, image quality, fidelity, and uncertainty, allowing for safer and more efficient tool selection.
- Achieved a 42.5% reduction in total tool calls and a 63.4% reduction in rejected calls compared to reactive baselines while improving Y-PSNR by 0.92 dB.
- Developed an auditing method to distinguish between performance bottlenecks caused by the tool selector versus the limitations of the available candidate tool space.

## Limitations

The framework relies on the accuracy of the world model's predictions and currently studies targeted tool adaptation as a primary method to expand the candidate space.

## Open Questions & Future Work

- [[targeted-tool-adaptation-gap-analysis]]

## Key Concepts

- [[pre-act-ir]]: An agentic image restoration framework that uses a tool-conditioned world model to forecast the outcomes and risks of candidate restoration tools before they are executed.
- [[tool-conditioned-world-model]]: A predictive model that simulates the effect of specific image processing tools or discrete actions on environment states, including quality metrics and execution risk.

## Archivist Review

The approved candidates represent the core architectural novelty (PreActIR) and the reusable design pattern (Tool-Conditioned World Model) introduced in the paper. The open question highlights a critical bottleneck identified in the paper's auditing process: the need to distinguish between poor planning and insufficient tool capabilities, which is a generalizable challenge for all agentic systems. No datasets were identified as candidates.

### Approved Concepts
- PreActIR: It shifts agentic image restoration from reactive trial-and-error to a predictive 'look-before-acting' paradigm, significantly improving efficiency and safety.
- Tool-Conditioned World Model: It allows an agent to simulate environment state transitions in a latent or predicted space specifically conditioned on discrete tool actions, enabling internal planning without execution.

### Approved Open Questions
- Targeted Tool Adaptation and Gap Analysis: Distinguishing between selector limitations and toolset limitations is crucial for autonomous systems to self-improve and adapt to novel or complex environments.

## Links

- [Abstract](https://arxiv.org/abs/2610.20384)
- [PDF](https://arxiv.org/pdf/2610.20384)

