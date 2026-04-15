---
# CSL-compatible fields
title: "Do VLMs Truly \"Read\" Candlesticks? A Multi-Scale Benchmark for Visual Stock Price Forecasting"
author:
  - literal: "Kaiqi Hu"
  - literal: "Linda Xiao"
  - literal: "Shiyue Xu"
  - literal: "Ziyi Tang"
  - literal: "Mingwen Liu"
issued:
  date-parts:
    - [2026, 4, 14]
url: "https://arxiv.org/abs/2604.12659"

# Custom fields
paper_id: "2604.12659"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series"
  - "forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-15T05:03:30Z"
created_at: "2026-04-15T05:03:30Z"
---

# Do VLMs Truly "Read" Candlesticks? A Multi-Scale Benchmark for Visual Stock Price Forecasting

**Authors**: Kaiqi Hu, Linda Xiao, Shiyue Xu, Ziyi Tang, Mingwen Liu
**Date**: 2026-04-14
**Paper ID**: [arxiv:2604.12659](https://arxiv.org/abs/2604.12659)

## Summary

This paper investigates the actual capability of Vision-Language Models (VLMs) to analyze stock price candlestick charts by introducing a dedicated multi-scale benchmark. The authors demonstrate that while VLMs perform reasonably well during clear market trends, they lack robustness in common market scenarios and show significant weaknesses in precise temporal reasoning. By comparing model outputs against an XGBoost baseline, the study reveals that VLM predictive performance is often biased and lacks sensitivity to specific forecast horizons provided in prompts.

## Key Contributions

- Introduces a multi-scale candlestick chart dataset designed to test VLM integration of long-term trends and short-term inflection signals.
- Establishes a standardized VLM evaluation framework using confusion-matrix diagnostics and IC-based metrics compared against XGBoost baselines.
- Reveals that current representative VLMs struggle with non-trending market scenarios and demonstrate limited sensitivity to explicit temporal forecast prompts.

## Open Questions & Future Work

- [[vlm-financial-pattern-understanding]]

## Archivist Review

I have rejected the proposed benchmark concept as it is a specific implementation of an evaluation pipeline rather than a reusable conceptual contribution. Similarly, I rejected the fine-tuning open question as overly generic. I approved one open question concerning the interpretability of VLM visual pattern recognition, which is a significant bottleneck for the field.

### Approved Open Questions
- Evaluating VLM Financial Pattern Understanding: Understanding whether VLMs 'see' these specific technical indicators is crucial for determining if they can function as reliable analytical tools or if their performance is merely a product of statistical correlation.

### Rejected Candidates
- [concept] Multi-Scale Candlestick Benchmark (`multi-scale-candlestick-benchmark`) - paper_local: The proposed benchmark is a paper-specific dataset and evaluation routine rather than a reusable core mechanism or conceptual framework.
- [open_question] Impact of Fine-Tuning VLMs (`vlm-fine-tuning-financial-reasoning`) - generic: This is a generic future research direction common to almost all VLM domain-adaptation papers, rather than a specific unresolved theoretical or mechanism-level bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2604.12659)
- [PDF](https://arxiv.org/pdf/2604.12659)

