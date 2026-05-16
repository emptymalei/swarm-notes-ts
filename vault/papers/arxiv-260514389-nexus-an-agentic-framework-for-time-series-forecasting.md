---
# CSL-compatible fields
title: "Nexus : An Agentic Framework for Time Series Forecasting"
author:
  - literal: "Sarkar Snigdha Sarathi Das"
  - literal: "Palash Goyal"
  - literal: "Mihir Parmar"
  - literal: "Nanyun Peng"
  - literal: "Vishy Tirumalashetty"
  - literal: "Chun-Liang Li"
  - literal: "Rui Zhang"
  - literal: "Jinsung Yoon"
  - literal: "Tomas Pfister"
issued:
  date-parts:
    - [2026, 5, 14]
url: "https://arxiv.org/abs/2605.14389"

# Custom fields
paper_id: "2605.14389"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "time-series-foundation-models"
  - "large-language-models"
  - "agentic-reasoning"
  - "contextual-grounding"
architectures:
  []
datasets:
  []
concept_slugs:
  - "nexus"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-16T05:13:07Z"
created_at: "2026-05-16T05:13:07Z"
---

# Nexus : An Agentic Framework for Time Series Forecasting

**Authors**: Sarkar Snigdha Sarathi Das, Palash Goyal, Mihir Parmar, Nanyun Peng, Vishy Tirumalashetty, Chun-Liang Li, Rui Zhang, Jinsung Yoon, Tomas Pfister
**Date**: 2026-05-14
**Paper ID**: [arxiv:2605.14389](https://arxiv.org/abs/2605.14389)

## Summary

Nexus is a multi-agent framework designed to address the limitations of existing TSFMs and LLMs in time series forecasting by treating prediction as an agentic reasoning problem. The framework decomposes the forecasting process into distinct stages that isolate macro and micro temporal fluctuations and integrate contextual textual data, such as news or events. By organizing these reasoning tasks, Nexus effectively bridges the gap between numerical pattern recognition and real-world contextual grounding, achieving superior performance on post-knowledge-cutoff datasets compared to traditional benchmarks.

## Key Contributions

- Nexus introduces an agentic decomposition approach to forecasting, separating macro-level, micro-level, and contextual reasoning stages to enhance prediction in event-driven scenarios.
- Demonstrates that LLMs possess strong intrinsic forecasting capabilities when numerical and contextual reasoning are systematically organized within an agentic framework.
- Outperforms state-of-the-art TSFMs and zero-shot LLM baselines on post-cutoff datasets, including Zillow real estate and stock market equities, while providing human-interpretable reasoning traces.

## Open Questions & Future Work

- [[computational-efficiency-in-agentic-forecasting]]

## Key Concepts

- [[nexus]]: A multi-agent framework for time series forecasting that decomposes predictions into specialized macro/micro-temporal and contextual reasoning stages.

## Archivist Review

I approved the 'Nexus' concept as it introduces a reusable agentic decomposition paradigm for time-series forecasting. I also approved a refined version of the open question regarding the efficiency of agentic forecasting, as it identifies a critical bottleneck for future research in this area. I rejected the Zillow metrics as a dataset candidate because it lacks the formal structure and provenance of a specific, named research benchmark.

### Approved Concepts
- Nexus: It establishes a novel agentic paradigm for time series forecasting that bridges the gap between TSFMs and LLMs through task decomposition and contextual grounding.

### Approved Open Questions
- Efficiency of Agentic Forecasting: The absence of rigorous statistical validation and suitable non-leaking benchmarks currently prevents accurate assessment of agentic forecasting performance versus traditional statistical baselines.

### Rejected Candidates
- [dataset] Zillow real estate metrics (`zillow-real-estate-metrics`) - low_impact: This is a general category of real-world metrics rather than a standardized, specifically named research dataset.

## Links

- [Abstract](https://arxiv.org/abs/2605.14389)
- [PDF](https://arxiv.org/pdf/2605.14389)

