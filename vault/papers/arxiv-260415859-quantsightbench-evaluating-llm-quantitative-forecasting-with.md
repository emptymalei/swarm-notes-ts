---
# CSL-compatible fields
title: "QuantSightBench: Evaluating LLM Quantitative Forecasting with Prediction Intervals"
author:
  - literal: "Jeremy Qin"
  - literal: "Maksym Andriushchenko"
issued:
  date-parts:
    - [2026, 4, 17]
url: "https://arxiv.org/abs/2604.15859"

# Custom fields
paper_id: "2604.15859"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  - "QuantSightBench"
concept_slugs:
  - "quantsightbench"
dataset_slugs:
  - "quantsightbench"
skill: "TimeSeriesSkill"
processed_at: "2026-04-20T05:09:51Z"
created_at: "2026-04-20T05:09:51Z"
---

# QuantSightBench: Evaluating LLM Quantitative Forecasting with Prediction Intervals

**Authors**: Jeremy Qin, Maksym Andriushchenko
**Date**: 2026-04-17
**Paper ID**: [arxiv:2604.15859](https://arxiv.org/abs/2604.15859)

## Summary

QuantSightBench addresses the limitations of existing LLM forecasting evaluations by focusing on continuous numerical estimates rather than binary or multiple-choice questions. The benchmark utilizes prediction intervals as a rigorous format to measure both empirical coverage and interval sharpness. Empirical results across 11 frontier models reveal a persistent failure to achieve target coverage, with all models exhibiting systematic overconfidence, particularly when forecasting extreme magnitudes.

## Key Contributions

- Introduces QuantSightBench, a novel benchmark for evaluating LLM quantitative forecasting using prediction intervals to capture uncertainty in continuous outcomes.
- Demonstrates that 11 frontier and open-weight models consistently fail to meet 90% coverage targets, with top models like Gemini 3.1 Pro only reaching 79.1%.
- Identifies systematic overconfidence in LLMs, specifically noting that calibration quality degrades significantly at extreme numerical magnitudes.

## Open Questions & Future Work

- [[improving-llm-calibration-numerical-forecasting]]

## Key Concepts

- [[quantsightbench]]: A benchmark for evaluating large language model quantitative forecasting capabilities through the use of prediction intervals.

## Archivist Review

The benchmark QuantSightBench was approved because it introduces a crucial evaluation shift from point-estimates to prediction intervals for LLMs, which is a necessary maturation for forecasting tasks. The corresponding open question was approved for focusing on the alignment bottleneck (mitigating overconfidence) rather than generic performance improvements. No other candidates were proposed.

### Approved Concepts
- QuantSightBench: It establishes a standardized, rigorous evaluation interface for numerical forecasting using prediction intervals, which addresses a significant gap in current LLM benchmarking.

### Approved Open Questions
- Improving LLM Calibration for Numerical Forecasting: Improving calibration in numerical prediction is a fundamental requirement for the safe deployment of LLMs in quantitative decision-making contexts.

## Datasets

- [[quantsightbench]]

## Links

- [Abstract](https://arxiv.org/abs/2604.15859)
- [PDF](https://arxiv.org/pdf/2604.15859)

