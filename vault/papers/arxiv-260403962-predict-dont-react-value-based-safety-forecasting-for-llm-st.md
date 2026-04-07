---
# CSL-compatible fields
title: "Predict, Don't React: Value-Based Safety Forecasting for LLM Streaming"
author:
  - literal: "Pride Kavumba"
  - literal: "Koki Wataoka"
  - literal: "Huy H. Nguyen"
  - literal: "Jiaxuan Li"
  - literal: "Masaya Ohagi"
issued:
  date-parts:
    - [2026, 4, 5]
url: "https://arxiv.org/abs/2604.03962"

# Custom fields
paper_id: "2604.03962"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  - "QWENGUARDTEST"
concept_slugs:
  - "value-based-safety-forecasting"
dataset_slugs:
  - "qwenguardtest"
skill: "TimeSeriesSkill"
processed_at: "2026-04-07T04:54:55Z"
created_at: "2026-04-07T04:54:55Z"
---

# Predict, Don't React: Value-Based Safety Forecasting for LLM Streaming

**Authors**: Pride Kavumba, Koki Wataoka, Huy H. Nguyen, Jiaxuan Li, Masaya Ohagi
**Date**: 2026-04-05
**Paper ID**: [arxiv:2604.03962](https://arxiv.org/abs/2604.03962)

## Summary

This paper proposes StreamGuard, a model-agnostic approach to LLM streaming moderation that reformulates the problem from reactive boundary detection to proactive forecasting of future harmfulness. By utilizing Monte Carlo rollouts for supervision, StreamGuard predicts the risk of future continuations based on partial generation prefixes, facilitating earlier and more accurate interventions. Experimental results on the QWENGUARDTEST benchmark demonstrate that this forecasting-based strategy consistently outperforms traditional streaming guardrails, while also exhibiting strong cross-model and cross-tokenizer transferability.

## Key Contributions

- Introduced StreamGuard, a model-agnostic streaming safety guardrail that treats moderation as a forecasting problem rather than boundary detection.
- Enabled early intervention in streaming LLM generations without requiring precise, expensive token-level boundary annotations.
- Demonstrated improved performance on the QWENGUARDTEST benchmark, reducing miss rates to 4.9% while improving intervention timing and F1 scores.

## Open Questions & Future Work

- [[scalability-forecasting-safety-long-context]]

## Key Concepts

- [[value-based-safety-forecasting]]: A safety moderation paradigm that predicts the expected harmfulness of future sequence continuations from partial prefixes using Monte Carlo rollouts.

## Archivist Review

I approved the value-based safety forecasting concept as a novel, reusable paradigm for sequence moderation tasks. I also approved the open question regarding the scalability of rollout-based supervision in long-context scenarios, as this captures a fundamental trade-off between foresight and computational expense in streaming architectures. QWENGUARDTEST was approved as a named benchmark dataset central to the paper's claims.

### Approved Concepts
- Value-Based Safety Forecasting: It shifts the safety moderation paradigm from reactive boundary detection to proactive forecasting, enabling early intervention without requiring exact token-level boundary labels.

### Approved Open Questions
- Forecasting Moderation for Long-Context: As deployments prioritize long-context capabilities, developing computationally efficient, long-horizon safety guardrails is a primary bottleneck for real-world reliability.

## Datasets

- [[qwenguardtest]]

## Links

- [Abstract](https://arxiv.org/abs/2604.03962)
- [PDF](https://arxiv.org/pdf/2604.03962)

