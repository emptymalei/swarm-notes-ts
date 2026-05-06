---
# CSL-compatible fields
title: "FinSTaR: Towards Financial Reasoning with Time Series Reasoning Models"
author:
  - literal: "Seunghan Lee"
  - literal: "Jun Seo"
  - literal: "Jaehoon Lee"
  - literal: "Sungdong Yoo"
  - literal: "Minjae Kim"
  - literal: "Tae Yoon Lim"
  - literal: "Dongwan Kang"
  - literal: "Hwanil Choi"
  - literal: "Soonyoung Lee"
  - literal: "Wonbin Ahn"
issued:
  date-parts:
    - [2026, 5, 5]
url: "https://arxiv.org/abs/2605.03460"

# Custom fields
paper_id: "2605.03460"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  - "FinTSR-Bench"
concept_slugs:
  - "compute-in-cot"
  - "scenario-aware-cot"
dataset_slugs:
  - "fintsr-bench"
skill: "TimeSeriesSkill"
processed_at: "2026-05-06T05:12:23Z"
created_at: "2026-05-06T05:12:23Z"
---

# FinSTaR: Towards Financial Reasoning with Time Series Reasoning Models

**Authors**: Seunghan Lee, Jun Seo, Jaehoon Lee, Sungdong Yoo, Minjae Kim, Tae Yoon Lim, Dongwan Kang, Hwanil Choi, Soonyoung Lee, Wonbin Ahn
**Date**: 2026-05-05
**Paper ID**: [arxiv:2605.03460](https://arxiv.org/abs/2605.03460)

## Summary

This paper addresses the failure of general time series reasoning models in the financial domain by proposing FinSTaR, a reasoning-focused model tailored to financial market dynamics. The authors introduce a 2x2 capability taxonomy to structure financial reasoning tasks, resulting in the new FinTSR-Bench benchmark. By applying task-specific chain-of-thought strategies—Compute-in-CoT for deterministic state assessment and Scenario-Aware CoT for stochastic future prediction—the model demonstrates superior performance over existing LLM and TSRM baselines. The study highlights that these reasoning capabilities are complementary and that scenario-based reasoning significantly improves prediction under uncertainty.

## Key Contributions

- Introduced a 2x2 capability taxonomy for Time Series Reasoning Models (TSRMs) crossing multi-entity/single-entity and assessment/prediction axes.
- Constructed FinTSR-Bench, a comprehensive benchmark for financial reasoning consisting of ten distinct tasks based on S&P stocks.
- Proposed FinSTaR, which employs category-specific chain-of-thought (CoT) strategies—Compute-in-CoT for deterministic assessments and Scenario-Aware CoT for stochastic predictions—achieving 78.9% average accuracy.

## Open Questions & Future Work

- [[reasoning-under-financial-uncertainty]]

## Key Concepts

- [[compute-in-cot]]: A programmatic chain-of-thought strategy for deterministic financial assessment tasks that derives answers directly from raw price data.
- [[scenario-aware-cot]]: A chain-of-thought prompting technique that generates multiple potential scenarios before making a final prediction to better handle stochastic uncertainty.

## Archivist Review

The paper proposes a useful framework for differentiating between deterministic assessment and stochastic prediction in financial time series analysis. I have approved the two reasoning-based CoT techniques and the benchmark dataset. The open question regarding reasoning under uncertainty is a high-level challenge relevant to the broader field of LLM-based forecasting and decision-support systems.

### Approved Concepts
- Compute-in-CoT: It provides a programmatic approach for financial reasoning tasks involving deterministic assessment, bridging the gap between raw data and reasoning.
- Scenario-Aware CoT: It explicitly addresses stochastic financial prediction by mimicking human analyst workflows under uncertainty.

### Approved Open Questions
- Reasoning Under Financial Uncertainty: This distinction is critical for building epistemically honest financial AI systems that avoid overconfident predictions in high-stakes environments.

## Datasets

- [[fintsr-bench]]

## Links

- [Abstract](https://arxiv.org/abs/2605.03460)
- [PDF](https://arxiv.org/pdf/2605.03460)

