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
  []
architectures:
  []
datasets:
  - "dialtom"
concept_slugs:
  - "prospective-diagnostic-forecasting"
dataset_slugs:
  - "dialtom"
skill: "TimeSeriesSkill"
processed_at: "2026-04-23T05:06:45Z"
created_at: "2026-04-23T05:06:45Z"
---

# DialToM: A Theory of Mind Benchmark for Forecasting State-Driven Dialogue Trajectories

**Authors**: Neemesh Yadav, Palakorn Achananuparp, Jing Jiang, Ee-Peng Lim
**Date**: 2026-04-22
**Paper ID**: [arxiv:2604.20443](https://arxiv.org/abs/2604.20443)

## Summary

This paper presents DialToM, a new benchmark designed to evaluate Theory of Mind (ToM) in LLMs by testing their ability to perform Prospective Diagnostic Forecasting on human dialogue. Unlike traditional benchmarks focusing on literal mental state prediction, DialToM requires models to forecast state-consistent social trajectories based on inferred mental profiles. The results highlight a critical reasoning gap, showing that most LLMs cannot effectively translate their understanding of mental states into functional social predictions. The study provides evidence that current models often rely on spurious correlations rather than robust ToM-based reasoning.

## Key Contributions

- Introduces DialToM, a human-verified benchmark for assessing Theory of Mind in LLMs via multiple-choice dialogue trajectory forecasting.
- Identifies a reasoning asymmetry where LLMs demonstrate proficiency in mental state prediction but fail at utilizing that information for social trajectory forecasting.
- Demonstrates that Gemini 3 Pro is uniquely capable of leveraging mental state profiles for consistent dialogue trajectory forecasting compared to other evaluated LLMs.

## Open Questions & Future Work

- [[functional-tom-reasoning-asymmetry]]

## Key Concepts

- [[prospective-diagnostic-forecasting]]: A task formulation for assessing whether a model can predict state-consistent future dialogue trajectories based on inferred mental-state profiles.

## Archivist Review

Approved the diagnostic forecasting framework and the specific reasoning asymmetry it uncovers as foundational contributions to social AI evaluation. The DialToM dataset is approved as a necessary artifact for this evaluation, though I restricted the approval to these items to maintain the requested scarcity. Rejected no candidates as the initial list was already highly focused.

### Approved Concepts
- Prospective Diagnostic Forecasting: It shifts the evaluation of Theory of Mind from static state classification to active forecasting of trajectory consistency.

### Approved Open Questions
- Functional ToM Reasoning Asymmetry: This is a fundamental open problem in social AI. If models cannot translate mental state understanding into functional action, their social reasoning remains shallow and non-generalizable to real-world interactions where forward-looking planning is required.

## Datasets

- [[dialtom]]

## Links

- [Abstract](https://arxiv.org/abs/2604.20443)
- [PDF](https://arxiv.org/pdf/2604.20443)

