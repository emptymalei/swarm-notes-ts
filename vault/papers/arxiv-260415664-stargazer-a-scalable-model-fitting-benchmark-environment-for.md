---
# CSL-compatible fields
title: "Stargazer: A Scalable Model-Fitting Benchmark Environment for AI Agents under Astrophysical Constraints"
author:
  - literal: "Xinge Liu"
  - literal: "Terry Jingchen Zhang"
  - literal: "Bernhard Schölkopf"
  - literal: "Zhijing Jin"
  - literal: "Kristen Menou"
issued:
  date-parts:
    - [2026, 4, 17]
url: "https://arxiv.org/abs/2604.15664"

# Custom fields
paper_id: "2604.15664"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "benchmarking"
  - "ai-agents"
  - "scientific-modeling"
  - "model-fitting"
  - "radial-velocity-forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  - "stargazer"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-20T05:10:42Z"
created_at: "2026-04-20T05:10:42Z"
---

# Stargazer: A Scalable Model-Fitting Benchmark Environment for AI Agents under Astrophysical Constraints

**Authors**: Xinge Liu, Terry Jingchen Zhang, Bernhard Schölkopf, Zhijing Jin, Kristen Menou
**Date**: 2026-04-17
**Paper ID**: [arxiv:2604.15664](https://arxiv.org/abs/2604.15664)

## Summary

Stargazer is a novel benchmark environment designed to evaluate AI agent capabilities in complex, physics-grounded model-fitting tasks using radial-velocity time series data. The framework provides 120 tasks, including 20 real archival cases, to assess how effectively agents navigate multi-planetary system configurations. Empirical evaluation shows that while frontier agents can achieve high statistical goodness-of-fit, they often fail to recover accurate physical parameters and fall into recursive reasoning loops that do not benefit from increased test-time compute. This work highlights the urgent need for better grounding in scientific agent architectures.

## Key Contributions

- Introduces Stargazer, a benchmark with 120 radial-velocity time series tasks for evaluating AI agent scientific model-fitting performance.
- Identifies a critical failure mode where agents prioritize statistical fit over physical consistency in multi-planetary system parameter recovery.
- Demonstrates that simple test-time compute scaling is insufficient to overcome recursive failure loops in complex scientific inference tasks.

## Open Questions & Future Work

- [[statistical-fit-vs-physical-reasoning]]

## Key Concepts

- [[stargazer]]: A scalable, simulation-driven benchmark environment for assessing AI agent performance on iterative physics-grounded model-fitting tasks.

## Archivist Review

I approved Stargazer as a benchmark concept because it establishes a standardized framework for evaluating agent-based scientific inference beyond simple predictive performance. The open question regarding statistical fit versus physical reasoning highlights a fundamental failure mode in contemporary LLM-driven scientific agents that merits long-term tracking. Other candidates were not proposed, and the selection adheres to the policy of keeping the vault lean by focusing on high-level methodological contributions rather than specific instance data or routine benchmarks.

### Approved Concepts
- Stargazer: It provides a novel benchmark for evaluating autonomous AI agents on iterative, physics-grounded scientific model-fitting.

### Approved Open Questions
- Statistical Fit vs. Physical Reasoning: Understanding this limitation is essential for transitioning AI agents from passive data processors to reliable scientific research partners in physics and astronomy.

## Links

- [Abstract](https://arxiv.org/abs/2604.15664)
- [PDF](https://arxiv.org/pdf/2604.15664)

