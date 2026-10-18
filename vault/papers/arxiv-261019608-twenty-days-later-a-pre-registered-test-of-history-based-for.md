---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Twenty Days Later: A Pre-Registered Test of History-Based Forecasts of Brand Mentions in Gemini Answers"
description: "This paper presents a pre-registered longitudinal evaluation of the temporal stability of brand mentions in Gemini 3.1 Pro Preview. Using 162 identical requests across three waves (separated by 10 hours and 20 days), the author tested whether history-based forecasts could accurately predict which brands the model would name in response to categorical software queries. The results show that brand mention behavior is highly durable, with a Brier score of 0.0281 at the 20-day mark, suggesting that LLM-based brand visibility is stable enough for actionable monitoring and strategic planning."
resource: "https://arxiv.org/abs/2610.19608"
tags:
  - "large-language-models"
  - "llm"
  - "forecasting"
  - "reliability"
  - "stability"
  - "evaluation-metrics"
  - "benchmarking"
  - "nlp"
timestamp: "2026-10-18T00:44:16Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Dmitrij Żatuchin"
issued:
  date-parts:
    - [2026, 10, 14]

# Domain-specific custom fields
paper_id: "2610.19608"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "brand-mention-durability"
    description: "The temporal stability of an LLM's tendency to include specific brand names in its generated responses over weeks or months."
datasets:
  []
open_questions:
  - name: "llm-behavioral-decay-rate"
    description: "What is the long-term decay rate of behavioral stability in LLMs across months or years, and to what extent do minor version updates vs. major model releases contribute to this decay?"
skill: "GeneralMLSkill"
processed_at: "2026-10-18T00:44:16Z"
created_at: "2026-10-18T00:44:16Z"
---

# Twenty Days Later: A Pre-Registered Test of History-Based Forecasts of Brand Mentions in Gemini Answers

**Authors**: Dmitrij Żatuchin
**Date**: 2026-10-14
**Paper ID**: [arxiv:2610.19608](https://arxiv.org/abs/2610.19608)

## Summary

This paper presents a pre-registered longitudinal evaluation of the temporal stability of brand mentions in Gemini 3.1 Pro Preview. Using 162 identical requests across three waves (separated by 10 hours and 20 days), the author tested whether history-based forecasts could accurately predict which brands the model would name in response to categorical software queries. The results show that brand mention behavior is highly durable, with a Brier score of 0.0281 at the 20-day mark, suggesting that LLM-based brand visibility is stable enough for actionable monitoring and strategic planning.

## Key Contributions

- Executed a pre-registered longitudinal study over 20.3 days to measure the consistency of brand mentions in Gemini 3.1 Pro Preview across three software categories and three languages (English, Estonian, Finnish).
- Demonstrated that historical mention rates are highly predictive of future mentions, achieving a Brier score of 0.0281 at a 20-day horizon, significantly outperforming overall rates (0.234) and brand-history baselines (0.104).
- Confirmed that model behavior for unanimous responses (where a brand is always or never mentioned) is extremely stable, with 96% of unanimous cells remaining unchanged after three weeks.
- Validated an automated lexical labeling rule for brand mentions against human adjudication, achieving 100% agreement, providing a reliable metric for automated brand-presence monitoring.

## Limitations

The study is limited to a single model version (Gemini 3.1 Pro Preview), a specific 20-day interval, and 12 specific brands, without estimating a continuous decay rate for mention stability.

## Open Questions & Future Work

- [[llm-behavioral-decay-rate]]

## Key Concepts

- [[brand-mention-durability]]: The temporal stability of an LLM's tendency to include specific brand names in its generated responses over weeks or months.

## Archivist Review

The approved items focus on the core contribution of the paper: the temporal stability of model behaviors (specifically brand mentions) and the open question of behavioral decay. I rejected 'Pre-registered LLM Testing' as it is an application of a general scientific protocol rather than a specific ML concept. No named datasets were identified in the analysis.

### Approved Concepts
- Brand Mention Durability: Addresses the critical question of whether LLM biases, preferences, or visibility rankings are ephemeral or stable enough to be used for strategic monitoring and auditing.

### Approved Open Questions
- LLM Behavioral Decay Rate: Defining the half-life of LLM behaviors is essential for establishing the reliability of AI-based monitoring tools and the reproducibility of longitudinal AI research.

### Rejected Candidates
- [concept] Pre-registered LLM Testing (`pre-registered-llm-testing`) - generic: Pre-registration is a general scientific methodology; its application to LLM evaluation is a best practice rather than a novel, reusable machine learning architectural or conceptual contribution.

## Links

- [Abstract](https://arxiv.org/abs/2610.19608)
- [PDF](https://arxiv.org/pdf/2610.19608)

