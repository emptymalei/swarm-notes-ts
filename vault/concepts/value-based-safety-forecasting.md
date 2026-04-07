---
title: "Value-Based Safety Forecasting"
slug: "value-based-safety-forecasting"
type: concept
generated_stub: true
source_papers:
  - "[[arxiv-260403962-predict-dont-react-value-based-safety-forecasting-for-llm-st]]"
processed_at: "2026-04-07T04:54:55Z"
created_at: "2026-04-07T04:54:55Z"
---

# Value-Based Safety Forecasting

> *Auto-generated stub. Edit this file to add more details.*

A safety moderation paradigm that predicts the expected harmfulness of future sequence continuations from partial prefixes using Monte Carlo rollouts.


## Why It Matters

It shifts the safety moderation paradigm from reactive boundary detection to proactive forecasting, enabling early intervention without requiring exact token-level boundary labels.

## Evidence

> we introduce StreamGuard, a unified model-agnostic streaming guardrail that instead formulates moderation as a forecasting problem: given a partial prefix, the model predicts the expected harmfulness of likely future continuations.

## Related Papers

- [[arxiv-260403962-predict-dont-react-value-based-safety-forecasting-for-llm-st]]
