---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Perceive, Solve, Reason: Progressive Capability Formation in Time Series-LLMs"
description: "This paper introduces a systematic framework for developing Time Series Large Language Models (TS-LLMs) that move beyond simple forecasting toward complex reasoning. By curating a massive 'Perceive, Solve, Reason' (PSR) suite of 381K samples, the authors demonstrate that dedicated encoders and a progressive training curriculum are essential for mastering the full spectrum of time series tasks. Their results show that a 4B TS-LLM, trained sequentially to perceive before it reasons, can outperform significantly larger 7B models in zero-shot and out-of-domain scenarios."
resource: "https://arxiv.org/abs/2610.23521"
tags:
  - "time-series"
  - "large-language-models"
  - "reasoning"
  - "zero-shot-learning"
  - "representation-learning"
  - "evaluation-benchmark"
  - "out-of-distribution"
  - "foundation-models"
  - "transformer"
timestamp: "2026-10-19T04:26:54Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Xin Qiu"
  - literal: "Junlong Tong"
  - literal: "Wei Zhang"
  - literal: "Xiaoyu Shen"
issued:
  date-parts:
    - [2026, 10, 16]

# Domain-specific custom fields
paper_id: "2610.23521"
paper_source: "arxiv"
architectures:
  - "transformer"
concepts:
  - name: "psr-framework-time-series"
    description: "A tripartite capability hierarchy for time series LLMs that structures learning from basic perception to complex reasoning."
  - name: "progressive-capability-formation"
    description: "A training strategy for multi-modal models where capabilities are taught sequentially based on a hierarchy of complexity to improve transfer and efficiency."
datasets:
  []
open_questions:
  - name: "multivariate-phase-transition-tracking-ts-llms"
    description: "Current time-series large language models (TS-LLMs) struggle to accurately track coordinated phase transitions—such as simultaneous reversals in trend across multiple variables—over the full length of a sequence, which often results in incorrect grounding and extrapolation during complex reasoning tasks."
  - name: "progressive-learning-readiness-indicators-ts-llms"
    description: "Local performance saturation on a specific stage's benchmarks (e.g., reaching an F1-score ceiling in perception) does not necessarily indicate that the model is fully prepared for subsequent stages. The specific internal metrics or behavioral indicators that signify sufficient foundational capability for effective cross-stage transfer remain unidentified."
skill: "TimeSeriesSkill"
processed_at: "2026-10-19T04:26:54Z"
created_at: "2026-10-19T04:26:54Z"
---

# Perceive, Solve, Reason: Progressive Capability Formation in Time Series-LLMs

**Authors**: Xin Qiu, Junlong Tong, Wei Zhang, Xiaoyu Shen
**Date**: 2026-10-16
**Paper ID**: [arxiv:2610.23521](https://arxiv.org/abs/2610.23521)

## Summary

This paper introduces a systematic framework for developing Time Series Large Language Models (TS-LLMs) that move beyond simple forecasting toward complex reasoning. By curating a massive 'Perceive, Solve, Reason' (PSR) suite of 381K samples, the authors demonstrate that dedicated encoders and a progressive training curriculum are essential for mastering the full spectrum of time series tasks. Their results show that a 4B TS-LLM, trained sequentially to perceive before it reasons, can outperform significantly larger 7B models in zero-shot and out-of-domain scenarios.

## Key Contributions

- Established the first comprehensive training and evaluation suite (337K/44K samples) spanning perception, solving, and reasoning for time series LLMs.
- Identified that dedicated modality encoders are critical for reasoning tasks, with textualization causing an 8-10 point drop in reasoning accuracy.
- Demonstrated that a sequential training recipe (Perceive -> Solve -> Reason) is significantly more data-efficient and effective than mixing data or training on reasoning alone.
- Developed a 4B parameter TS-LLM that outperforms contemporary 7B models on seven out of eight out-of-domain benchmarks without target-domain fine-tuning.

## Limitations

The authors note that convergence on a specific capability benchmark does not inherently guarantee the model's readiness to transition to the next stage of the hierarchy.

## Open Questions & Future Work

- [[multivariate-phase-transition-tracking-ts-llms]]
- [[progressive-learning-readiness-indicators-ts-llms]]

## Key Concepts

- [[psr-framework-time-series]]: A tripartite capability hierarchy for time series LLMs that structures learning from basic perception to complex reasoning.
- [[progressive-capability-formation]]: A training strategy for multi-modal models where capabilities are taught sequentially based on a hierarchy of complexity to improve transfer and efficiency.

## Archivist Review

I have approved the core conceptual framework (PSR) and the training methodology (Progressive Capability Formation) as they represent a significant shift in how time-series LLMs are developed and evaluated. These concepts provide a reusable taxonomy for future foundation model research in this domain. I have also approved two open questions that target the specific technical limitations of this approach: multivariate synchronization and stage-wise optimization. The dataset was rejected because, although large, it functions primarily as an internal experimental suite rather than a standalone, community-standard benchmark.

### Approved Concepts
- PSR Framework (Perceive, Solve, Reason): Defines a hierarchical taxonomy for time series understanding in LLMs beyond simple forecasting, providing a roadmap for developing complex reasoning capabilities.
- Progressive Capability Formation: Demonstrates that curriculum learning based on task complexity (perception before reasoning) is more data-efficient than joint training for multi-modal time series models.

### Approved Open Questions
- Tracking Coordinated Phase Transitions: Accurate temporal reasoning depends on the model's ability to maintain a consistent state of variable inter-dependencies throughout the input window; failure to recognize synchronized phase shifts leads to misaligned trend analysis.
- Stage-wise Readiness Indicators: Identifying the optimal point to transition between training stages is critical for training efficiency and ensuring foundational knowledge is deep enough to support complex downstream reasoning.

### Rejected Candidates
- [dataset] TS-PSR Suite (`ts-psr-suite`) - paper_local: While the paper describes a suite of 337K/44K samples, it does not provide a distinct, formal name that is likely to become a standard community benchmark outside this paper's specific context.

## Links

- [Abstract](https://arxiv.org/abs/2610.23521)
- [PDF](https://arxiv.org/pdf/2610.23521)

