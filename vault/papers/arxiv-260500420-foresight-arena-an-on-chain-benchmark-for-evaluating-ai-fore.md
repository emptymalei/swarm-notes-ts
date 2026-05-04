---
# CSL-compatible fields
title: "Foresight Arena: An On-Chain Benchmark for Evaluating AI Forecasting Agents"
author:
  - literal: "Maksym Nechepurenko"
  - literal: "Pavel Shuvalov"
issued:
  date-parts:
    - [2026, 5, 1]
url: "https://arxiv.org/abs/2605.00420"

# Custom fields
paper_id: "2605.00420"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "nlp"
architectures:
  []
datasets:
  - "polymarket"
concept_slugs:
  - "alpha-score"
dataset_slugs:
  - "polymarket"
skill: "TimeSeriesSkill"
processed_at: "2026-05-04T05:15:51Z"
created_at: "2026-05-04T05:15:51Z"
---

# Foresight Arena: An On-Chain Benchmark for Evaluating AI Forecasting Agents

**Authors**: Maksym Nechepurenko, Pavel Shuvalov
**Date**: 2026-05-01
**Paper ID**: [arxiv:2605.00420](https://arxiv.org/abs/2605.00420)

## Summary

Foresight Arena is an on-chain evaluation platform that addresses data contamination and trust issues in AI forecasting benchmarks by utilizing real-world prediction markets. Agents submit probabilistic forecasts on binary outcomes, which are resolved via smart contracts to ensure an immutable, trustless record. The framework uses the Alpha Score—a novel, proper scoring rule—to isolate an agent's predictive edge from market consensus, complemented by Murphy decomposition for granular performance analysis. A formal power analysis quantifies the number of predictions required to distinguish agent skill levels, establishing a rigorous standard for benchmarking autonomous forecasters.

## Key Contributions

- Introduces Foresight Arena, a permissionless, on-chain benchmark for AI agents that mitigates data contamination by leveraging real-world prediction markets.
- Proposes the Alpha Score to decouple predictive accuracy from market timing and risk appetite, ensuring incentive-compatible evaluation.
- Provides a formal power analysis for predictive edge detection and conducts a 50-round empirical evaluation of five frontier LLMs.

## Open Questions & Future Work

- [[conditional-scoring-for-forecasting-benchmarks]]

## Key Concepts

- [[alpha-score]]: A proper scoring rule for probabilistic forecasts designed to isolate predictive edge from market consensus.

## Archivist Review

I have approved the Alpha Score as a central, reusable metric for forecasting and Polymarket as a dataset. The open question regarding conditional scoring represents a substantial and defined bottleneck in benchmarking methodology. I rejected the Foresight Arena concept itself because it is an implementation framework best defined by its underlying scoring and evaluation principles.

### Approved Concepts
- Alpha Score: It provides a novel, incentive-compatible metric for isolating predictive edge from market consensus in probabilistic forecasting.

### Approved Open Questions
- Conditional Scoring for Benchmarks: Critical for accelerating benchmarking cycles by reducing the required number of resolved predictions without sacrificing statistical power.

### Rejected Candidates
- [concept] Foresight Arena (`foresight-arena`) - paper_local: The framework is specific to the paper's implementation of an on-chain benchmark and is better characterized by its components (e.g., Alpha Score).

## Datasets

- [[polymarket]]

## Links

- [Abstract](https://arxiv.org/abs/2605.00420)
- [PDF](https://arxiv.org/pdf/2605.00420)

