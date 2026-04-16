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
  - "forecasting"
  - "benchmark"
  - "multi-scale"
  - "time-series-forecasting"
  - "vision-language-models"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-16T05:08:05Z"
created_at: "2026-04-16T05:08:05Z"
---

# Do VLMs Truly "Read" Candlesticks? A Multi-Scale Benchmark for Visual Stock Price Forecasting

**Authors**: Kaiqi Hu, Linda Xiao, Shiyue Xu, Ziyi Tang, Mingwen Liu
**Date**: 2026-04-14
**Paper ID**: [arxiv:2604.12659](https://arxiv.org/abs/2604.12659)

## Summary

This paper critically evaluates the capability of Vision-Language Models (VLMs) to process multi-scale candlestick charts for stock price forecasting. The authors construct a new multi-scale dataset and evaluation framework to determine whether VLMs genuinely comprehend market visual dynamics or merely rely on persistent trends. The results indicate that while VLMs perform reasonably well under clear trend conditions, they suffer from significant predictive biases and a lack of precise temporal reasoning when forecasting across multiple scales. The study highlights the current limitations of VLMs in effectively integrating long-term trends with short-term inflection signals.

## Key Contributions

- Introduces a multi-scale candlestick chart benchmark for assessing VLM-based stock price forecasting.
- Evaluates representative VLMs against XGBoost temporal baselines using confusion-matrix-based diagnostics and IC metrics.
- Demonstrates that current VLMs struggle with non-trending market conditions and exhibit poor sensitivity to explicit temporal forecast horizons.

## Open Questions & Future Work

- [[vlm-financial-chart-reasoning]]
- [[vlm-temporal-reasoning-finetuning]]

## Archivist Review

The paper contributes a critique of VLM reasoning on financial charts. I approved two open questions that delineate the gap between current prompt-based VLM performance and the actual technical reasoning required for finance. No specific dataset or concept was deemed sufficiently generalizable to warrant a standalone vault note.

### Approved Open Questions
- Assessing VLM Financial Chart Reasoning: Validating the fundamental technical reasoning capabilities of VLMs in finance is critical for moving beyond 'black box' performance metrics toward robust, interpretable financial decision-support systems.
- Improving VLM Temporal Reasoning: It is necessary to determine if the identified performance bottleneck in long-term temporal reasoning is an inherent limitation of VLM architectures or a result of insufficient task-specific domain alignment.

### Rejected Candidates
- [dataset] Multi-scale candlestick charts dataset (`multi-scale-candlestick-charts-dataset`) - paper_local: The dataset is introduced without a formal, reusable name and appears to be specific to this paper's evaluation.

## Links

- [Abstract](https://arxiv.org/abs/2604.12659)
- [PDF](https://arxiv.org/pdf/2604.12659)

