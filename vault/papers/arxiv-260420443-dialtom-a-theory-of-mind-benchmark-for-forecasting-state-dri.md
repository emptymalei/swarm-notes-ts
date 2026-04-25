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
  - "nlp"
architectures:
  []
datasets:
  - "dialtom"
concept_slugs:
  - "prospective-diagnostic-forecasting"
dataset_slugs:
  - "dialtom"
skill: "TimeSeriesSkill"
processed_at: "2026-04-25T04:56:52Z"
created_at: "2026-04-25T04:56:52Z"
---

# DialToM: A Theory of Mind Benchmark for Forecasting State-Driven Dialogue Trajectories

**Authors**: Neemesh Yadav, Palakorn Achananuparp, Jing Jiang, Ee-Peng Lim
**Date**: 2026-04-22
**Paper ID**: [arxiv:2604.20443](https://arxiv.org/abs/2604.20443)

## Summary

DialToM is a new human-verified benchmark designed to decouple robust Theory of Mind (ToM) reasoning from spurious correlations in LLMs. The authors distinguish between 'Literal ToM' (mental state identification) and 'Functional ToM' (social trajectory forecasting), finding that most LLMs fail the latter despite passing the former. The study identifies a reasoning asymmetry and weak semantic alignment between model and human social inferences, suggesting that current LLM success is largely non-functional.

## Key Contributions

- Introduced DialToM, a human-verified benchmark for assessing Theory of Mind (ToM) in LLMs through mental state identification and functional trajectory forecasting.
- Demonstrated a 'reasoning asymmetry' where LLMs successfully identify mental states but struggle to utilize them for prospective dialogue forecasting.
- Revealed that LLM-generated social inferences share only weak semantic similarity with human-grounded benchmarks, questioning the robustness of current model reasoning.

## Open Questions & Future Work

- [[evaluating-functional-tom-mechanisms]]

## Key Concepts

- [[prospective-diagnostic-forecasting]]: An evaluation method that probes whether models can forecast dialogue trajectories based on inferred mental-state profiles.

## Archivist Review

I approved the core diagnostic methodology and the specific dataset introduced by the paper as they represent a reusable framework for evaluating Theory of Mind. The identified open question was refined for clarity and scope, while the concept of 'reasoning asymmetry' was rejected as it represents a finding rather than a formal technical mechanism.

### Approved Concepts
- Prospective Diagnostic Forecasting: It is the core diagnostic tool introduced to distinguish between mere state identification and functional reasoning in LLMs.

### Approved Open Questions
- Evaluating Functional ToM Mechanisms: Understanding the mechanics behind functional ToM is essential for building dialogue systems that can genuinely perform complex social interactions, as opposed to systems that merely mimic surface-level linguistic patterns. Tracking whether models perform genuine reasoning vs. memorization is a critical bottleneck for safe and reliable AI development.

### Rejected Candidates
- [concept] Reasoning Asymmetry (`reasoning-asymmetry`) - paper_local: This describes an empirical finding of the paper rather than a formal, reusable mechanism or method.

## Datasets

- [[dialtom]]

## Links

- [Abstract](https://arxiv.org/abs/2604.20443)
- [PDF](https://arxiv.org/pdf/2604.20443)

