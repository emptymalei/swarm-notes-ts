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
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "nexus-framework"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-17T05:24:48Z"
created_at: "2026-05-17T05:24:48Z"
---

# Nexus : An Agentic Framework for Time Series Forecasting

**Authors**: Sarkar Snigdha Sarathi Das, Palash Goyal, Mihir Parmar, Nanyun Peng, Vishy Tirumalashetty, Chun-Liang Li, Rui Zhang, Jinsung Yoon, Tomas Pfister
**Date**: 2026-05-14
**Paper ID**: [arxiv:2605.14389](https://arxiv.org/abs/2605.14389)

## Summary

Nexus is a multi-agent forecasting framework that bridges the gap between specialized Time Series Foundation Models and LLMs by decomposing the forecasting process into specialized stages. It integrates macro and micro-level temporal fluctuations with unstructured textual context to handle complex, event-driven dynamics. Validated on Zillow and stock market data, Nexus consistently outperforms existing methods while providing explicit reasoning traces for its forecasts. This work reformulates real-world forecasting as an agentic reasoning task rather than a purely sequence-modeling one.

## Key Contributions

- Introduces Nexus, a multi-agent forecasting framework that decomposes time series prediction into stages for macro-temporal, micro-temporal, and contextual integration.
- Demonstrates that current LLMs exhibit strong intrinsic forecasting capabilities when numerical and contextual reasoning are systematically organized.
- Outperforms SOTA Time Series Foundation Models (TSFMs) and LLM baselines on real estate and volatile stock market datasets, specifically on data post-dating LLM knowledge cutoffs.
- Produces interpretable reasoning traces that clarify the drivers of each forecast, moving beyond black-box sequence modeling.

## Open Questions & Future Work

- [[evaluation-cost-agentic-forecasting]]

## Key Concepts

- [[nexus-framework]]: A multi-agent forecasting framework that decomposes time series prediction into stages for macro-temporal, micro-temporal, and contextual integration to bridge numerical and reasoning gaps.

## Archivist Review

I have approved the Nexus Framework as a representative architectural approach for multi-agent temporal reasoning and defined an open question regarding the evaluation scalability of these compute-intensive systems. I rejected generic candidates and prioritized the overarching framework over specific module components. The evaluation focuses on the shift toward agentic forecasting as a research field rather than paper-specific implementation details.

### Approved Concepts
- Nexus Framework: It introduces a multi-agent decomposition paradigm for time series forecasting that separates numerical pattern extraction from contextual reasoning, framing forecasting as a multi-stage agentic task rather than monolithic sequence modeling.

### Approved Open Questions
- Evaluation cost agentic forecasting: This question highlights a critical systemic limitation that hinders the transition of agentic forecasting from prototype to production-grade reliable systems.

### Rejected Candidates
- [concept] Nexus (`nexus`) - other: Renamed to Nexus Framework for specificity.
- [open_question] Efficiency of Evaluating Agentic Forecasting (`reproducibility-cost-agentic-forecasting`) - other: Renamed for conciseness.

## Links

- [Abstract](https://arxiv.org/abs/2605.14389)
- [PDF](https://arxiv.org/pdf/2605.14389)

