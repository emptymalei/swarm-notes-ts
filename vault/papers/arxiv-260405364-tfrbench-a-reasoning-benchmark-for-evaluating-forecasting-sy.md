---
# CSL-compatible fields
title: "TFRBench: A Reasoning Benchmark for Evaluating Forecasting Systems"
author:
  - literal: "Md Atik Ahamed"
  - literal: "Mihir Parmar"
  - literal: "Palash Goyal"
  - literal: "Yiwen Song"
  - literal: "Long T. Le"
  - literal: "Qiang Cheng"
  - literal: "Chun-Liang Li"
  - literal: "Hamid Palangi"
  - literal: "Jinsung Yoon"
  - literal: "Tomas Pfister"
issued:
  date-parts:
    - [2026, 4, 7]
url: "https://arxiv.org/abs/2604.05364"

# Custom fields
paper_id: "2604.05364"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "llm-as-a-judge-for-time-series-explanations"
  - "causal-insight"
architectures:
  []
datasets:
  []
concept_slugs:
  - "tfrbench"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-08T04:56:23Z"
created_at: "2026-04-08T04:56:23Z"
---

# TFRBench: A Reasoning Benchmark for Evaluating Forecasting Systems

**Authors**: Md Atik Ahamed, Mihir Parmar, Palash Goyal, Yiwen Song, Long T. Le, Qiang Cheng, Chun-Liang Li, Hamid Palangi, Jinsung Yoon, Tomas Pfister
**Date**: 2026-04-07
**Paper ID**: [arxiv:2604.05364](https://arxiv.org/abs/2604.05364)

## Summary

TFRBench is a new benchmarking protocol designed to move time-series forecasting evaluation beyond simple numerical accuracy toward evaluating model reasoning. The authors introduce a multi-agent framework that uses an iterative verification loop to synthesize grounded reasoning traces covering trends, cross-channel dependencies, and external events. Extensive experiments across ten datasets demonstrate that these reasoning traces are both accurate and effective at improving the performance of foundation models in forecasting tasks.

## Key Contributions

- Introduces TFRBench, a novel benchmark evaluating the reasoning capabilities (cross-channel dependencies, trends, and external events) of forecasting systems.
- Proposes a systematic multi-agent framework utilizing an iterative verification loop to generate high-quality, numerically grounded reasoning traces.
- Demonstrates that augmenting LLM prompts with generated reasoning traces significantly improves forecasting accuracy (avg. ~40.2% to 56.6%) compared to direct numerical prediction.

## Key Concepts

- [[tfrbench]]: A benchmarking protocol for evaluating the reasoning capabilities, cross-channel dependencies, and trend analysis of time-series forecasting systems.

## Archivist Review

I approved TFRBench as it introduces a novel evaluation framework that bridges time-series forecasting with reasoning-based evaluation, a distinct and reusable paradigm for the field. No other candidates were provided, and I maintained strict selectivity by not inventing any additional concepts or questions.

### Approved Concepts
- TFRBench: It shifts the evaluation paradigm from pure black-box numerical accuracy to interpretable reasoning trace evaluation in time-series forecasting.

## Links

- [Abstract](https://arxiv.org/abs/2604.05364)
- [PDF](https://arxiv.org/pdf/2604.05364)

