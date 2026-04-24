---
# CSL-compatible fields
title: "DialToM: A Theory of Mind Benchmark for Forecasting State-Driven Dialogue Trajectories"
author:
  - literal: "Neemesh Yadav"
  - literal: "Palakorn Achananuparp"
  - literal: "Jing Jiang"
  - literal: "Ee-Peng Lim"
issued:
  date-parts:
    - [2026, 4, 22]
url: "https://arxiv.org/abs/2604.20443"

# Custom fields
paper_id: "2604.20443"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "llm-reasoning-limits"
  - "dialogue-systems"
  - "theory-of-mind"
architectures:
  []
datasets:
  - "DialToM"
concept_slugs:
  - "prospective-diagnostic-forecasting"
dataset_slugs:
  - "dialtom"
skill: "TimeSeriesSkill"
processed_at: "2026-04-24T05:10:39Z"
created_at: "2026-04-24T05:10:39Z"
---

# DialToM: A Theory of Mind Benchmark for Forecasting State-Driven Dialogue Trajectories

**Authors**: Neemesh Yadav, Palakorn Achananuparp, Jing Jiang, Ee-Peng Lim
**Date**: 2026-04-22
**Paper ID**: [arxiv:2604.20443](https://arxiv.org/abs/2604.20443)

## Summary

This paper investigates whether Theory of Mind (ToM) in LLMs reflects genuine reasoning or spurious correlations by introducing DialToM, a human-verified benchmark for dialogue. The authors distinguish between Literal ToM (mental state prediction) and Functional ToM (using states to forecast future dialogue). Their evaluation reveals that while models are competent at predicting states, they largely fail at Prospective Diagnostic Forecasting, exposing a critical disconnect between state identification and social reasoning.

## Key Contributions

- Introduces DialToM, a human-verified benchmark for assessing both Literal and Functional Theory of Mind (ToM) in LLMs.
- Demonstrates a reasoning asymmetry where LLMs excel at predicting static mental states but fail to utilize them for accurate prospective social trajectory forecasting.
- Highlights a lack of semantic alignment between human-generated inferences and LLM-derived mental-state justifications.

## Open Questions & Future Work

- [[functional-tom-reasoning-asymmetry]]

## Key Concepts

- [[prospective-diagnostic-forecasting]]: A framework for evaluating a model's ability to forecast state-consistent dialogue trajectories based on inferred mental-state profiles.

## Archivist Review

The paper introduces a critical distinction between mental state recognition (Literal ToM) and the functional application of these states (Functional ToM). The 'Prospective Diagnostic Forecasting' concept is a high-quality methodological contribution for evaluating social AI. The 'DialToM' dataset is approved as a necessary artifact for benchmarking this capability. The open question regarding the 'Functional Theory of Mind Asymmetry' identifies a fundamental, unresolved bottleneck in LLM reasoning that transcends the immediate scope of the paper.

### Approved Concepts
- Prospective Diagnostic Forecasting: It provides a structured mechanism to evaluate the functional utility of mental states in dialogue by linking them to predicted future trajectories.

### Approved Open Questions
- Functional Theory of Mind Asymmetry: Understanding whether LLMs truly possess functional ToM or are merely using surface-level correlations is critical for the development of safe and effective social AI agents. If models cannot reliably forecast state-consistent behavior, their use in high-stakes human interaction, such as mental health support or persuasion, presents significant risks of misalignment.

## Datasets

- [[dialtom]]

## Links

- [Abstract](https://arxiv.org/abs/2604.20443)
- [PDF](https://arxiv.org/pdf/2604.20443)

