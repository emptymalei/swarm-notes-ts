---
# CSL-compatible fields
title: "TIGFlow-GRPO: Trajectory Forecasting via Interaction-Aware Flow Matching and Reward-Driven Optimization"
author:
  - literal: "Xuepeng Jing"
  - literal: "Wenhuan Lu"
  - literal: "Hao Meng"
  - literal: "Zhizhi Yu"
  - literal: "Jianguo Wei"
issued:
  date-parts:
    - [2026, 3, 26]
url: "https://arxiv.org/abs/2603.24936"

# Custom fields
paper_id: "2603.24936"
paper_source: "openalex"
domain: "computer-vision"
tags:
  - "trajectory forecasting"
  - "conditional flow matching"
  - "generative modeling"
  - "reinforcement learning"
  - "graph neural networks"
architectures:
  []
datasets:
  []
concept_slugs:
  - "interaction-aware-flow-matching-tigflow"
  - "reward-driven-optimization-trajectory-flow"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-03-29T20:16:51Z"
created_at: "2026-03-29T20:16:51Z"
---

# TIGFlow-GRPO: Trajectory Forecasting via Interaction-Aware Flow Matching and Reward-Driven Optimization

**Authors**: Xuepeng Jing, Wenhuan Lu, Hao Meng, Zhizhi Yu, Jianguo Wei
**Date**: 2026-03-26
**Paper ID**: [openalex:2603.24936](https://arxiv.org/abs/2603.24936)

## Summary

This paper introduces TIGFlow-GRPO, a two-stage generative framework for human trajectory forecasting that addresses the limitations of purely supervised Conditional Flow Matching (CFM). The first stage incorporates a Trajectory-Interaction-Graph (TIG) module into the CFM predictor to capture fine-grained agent-agent and agent-scene relations, yielding better conditional features. The second stage employs Flow-GRPO post-training, which reformulates deterministic flow rollout into stochastic SDE sampling, guided by composite rewards balancing social compliance and physical feasibility. Evaluations on ETH/UCY and SDD show TIGFlow-GRPO achieves superior accuracy, stability, and behavioral realism in generated multimodal trajectories.

## Key Contributions

- Proposed TIGFlow-GRPO, a two-stage generative framework that integrates Conditional Flow Matching with a Trajectory-Interaction-Graph (TIG) module for enhanced context encoding.
- Introduced Flow-GRPO post-training, reformulating deterministic flow rollout into stochastic ODE-to-SDE sampling guided by composite rewards (view-aware social compliance and map-aware feasibility).
- Demonstrated improved forecasting accuracy, long-horizon stability, and generation of more socially compliant and physically feasible trajectories compared to existing methods on ETH/UCY and SDD.

## Limitations

The paper does not explicitly state limitations, but the reliance on a composite reward function for the GRPO stage implies potential sensitivity to reward shaping.

## Open Questions & Future Work

- [[flow-matching-behavioral-alignment-pretraining]]

## Key Concepts

- [[interaction-aware-flow-matching-tigflow]]: A Conditional Flow Matching model enhanced with a Trajectory-Interaction-Graph module to explicitly encode agent-agent and agent-scene relations for trajectory prediction.
- [[reward-driven-optimization-trajectory-flow]]: A post-training optimization method that refines Conditional Flow Matching predictions by using stochastic SDE sampling guided by rewards reflecting social compliance and physical feasibility.

## Archivist Review

Two novel architectural and procedural concepts were approved: Interaction-Aware Flow Matching (TIGFlow) which integrates graph context into CFM, and Reward-Driven Optimization (GRPO) applied to SDE-based flow rollouts for behavioral alignment. The listed datasets were rejected as they are standard benchmarks. One open question was approved regarding the challenge of integrating complex behavioral constraints directly into the supervised pretraining stage, rather than relying solely on post-hoc reinforcement learning alignment.

### Approved Concepts
- Interaction-Aware Flow Matching (TIGFlow): This combines Conditional Flow Matching with explicit graph-based modeling of interactions, moving beyond simple observational conditioning in trajectory generation.
- Reward-Driven Optimization (GRPO) for Trajectory Flow: This technique adapts Reinforcement Learning (GRPO) principles to fine-tune a pre-trained generative flow model by treating trajectory exploration as stochastic SDE sampling guided by composite behavioral rewards.

### Approved Open Questions
- Integrating Behavioral Constraints in Pretraining: Addressing this gap could lead to single-stage, more efficient models that inherently respect real-world constraints without the overhead of a separate reinforcement learning post-training step.

### Rejected Candidates
- [dataset] ETH/UCY and SDD (`eth-ucy-sdd-datasets`) - paper_local: These are common, named benchmarks in trajectory forecasting and do not warrant permanent, standalone vault notes unless a novel dataset was introduced.
- [concept] Trajectory-Interaction-Graph (TIG) module (`trajectory-interaction-graph-tig`) - subcomponent_of_broader_mechanism: The TIG module is a specific graph component used to implement the broader, reusable concept of Interaction-Aware Flow Matching, making it a subcomponent.
- [concept] Flow-GRPO post-training (`flow-grpo-post-training`) - subcomponent_of_broader_mechanism: This is the specific implementation/application of the broader, reusable concept of Reward-Driven Optimization (GRPO) for flow models.

## Links

- [Abstract](https://arxiv.org/abs/2603.24936)
- [PDF](https://arxiv.org/pdf/2603.24936)

