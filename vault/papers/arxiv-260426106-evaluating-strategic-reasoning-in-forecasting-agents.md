---
# CSL-compatible fields
title: "Evaluating Strategic Reasoning in Forecasting Agents"
author:
  - literal: "Tom Liptay"
  - literal: "Dan Schwarz"
  - literal: "Rafael Poyiadzi"
  - literal: "Jack Wildman"
  - literal: "Nikos I. Bosse"
issued:
  date-parts:
    - [2026, 4, 28]
url: "https://arxiv.org/abs/2604.26106"

# Custom fields
paper_id: "2604.26106"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "bench-to-the-future-2-btf-2"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-30T05:14:29Z"
created_at: "2026-04-30T05:14:29Z"
---

# Evaluating Strategic Reasoning in Forecasting Agents

**Authors**: Tom Liptay, Dan Schwarz, Rafael Poyiadzi, Jack Wildman, Nikos I. Bosse
**Date**: 2026-04-28
**Paper ID**: [arxiv:2604.26106](https://arxiv.org/abs/2604.26106)

## Summary

This paper addresses the lack of interpretability in current forecasting benchmarks by introducing Bench to the Future 2 (BTF-2), an offline platform that captures full agent reasoning traces. By leveraging a frozen 15M-document corpus for 1,417 pastcasting questions, the authors isolate research and judgment capabilities without hindsight bias. They find that high-performing forecasters are distinguished by their ability to perform pre-mortem analysis and account for black swan events, while current frontier agents struggle significantly with modeling complex human and institutional incentives.

## Key Contributions

- Introduces BTF-2, a benchmark of 1,417 offline pastcasting questions paired with a static 15M-document corpus to facilitate reproducible analysis of agent reasoning traces.
- Demonstrates that superior forecasting performance is driven by pre-mortem analysis of blind spots and robust modeling of black swan events rather than generic accuracy improvements.
- Identifies critical strategic reasoning failures in frontier models, specifically regarding the modeling of human incentives, follow-through likelihood, and institutional dynamics.

## Open Questions & Future Work

- [[causal-identification-in-forecasting]]

## Key Concepts

- [[bench-to-the-future-2-btf-2]]: A benchmark platform using pastcasting questions and a frozen document corpus to evaluate agent reasoning traces and forecasting accuracy.

## Archivist Review

I have approved the BTF-2 benchmark concept as it introduces a rigorous methodology for evaluating agentic reasoning traces in a controlled environment. I also approved the causal identification question, as it highlights a fundamental limitation in current model evaluation that goes beyond simple benchmarking improvements. The conditional forecasting suggestion was rejected as it represents a typical task-expansion request rather than an foundational open question.

### Approved Concepts
- Bench to the Future 2 (BTF-2): It establishes a platform for reproducible evaluation of agentic reasoning traces in forecasting, moving beyond accuracy-only benchmarking.

### Approved Open Questions
- Causal Identification in Forecasting: Understanding the causal drivers of forecasting performance is essential for building robust, reliable reasoning agents rather than optimizing for leaderboard metrics.

### Rejected Candidates
- [open_question] Conditional Forecasting Evaluation (`conditional-forecasting-questions`) - low_impact: This is a standard suggestion for benchmark expansion rather than a foundational unresolved research bottleneck.

## Links

- [Abstract](https://arxiv.org/abs/2604.26106)
- [PDF](https://arxiv.org/pdf/2604.26106)

