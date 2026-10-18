---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Momentum, Commentary Tone, and Earnings Surprise in LLM Financial Forecasts"
description: "This paper investigates the drivers of financial forecasting in Large Language Models (LLMs) by testing their response to synthetic earnings announcements. By independently varying price momentum, commentary tone, and earnings surprises, the author measures how six different LLM checkpoints prioritize these inputs using conditional answer-prefix scores. The findings reveal a significant bias: most models are more sensitive to the tone of the commentary and historical momentum than to the actual earnings surprise relative to consensus."
resource: "https://arxiv.org/abs/2610.22043"
tags:
  - "large-language-models"
  - "financial-forecasting"
  - "interpretability"
  - "benchmarking"
  - "decision-making"
  - "nlp"
  - "prompt-engineering"
timestamp: "2026-10-18T00:17:46Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Alina Khaybullina"
issued:
  date-parts:
    - [2026, 10, 15]

# Domain-specific custom fields
paper_id: "2610.22043"
paper_source: "arxiv"
architectures:
  - "transformer"
concepts:
  - name: "conditional-answer-prefix-scoring"
    description: "A technique for quantifying LLM decision-making by measuring the log-probability of specific initial tokens in a response given controlled variations in the input prompt."
datasets:
  []
open_questions:
  - name: "llm-financial-rationality-scaling"
    description: "How does the reliance on non-informational cues (like commentary tone) relative to objective financial metrics (like EPS) evolve as model parameter counts scale beyond 8 billion?"
skill: "GeneralMLSkill"
processed_at: "2026-10-18T00:17:46Z"
created_at: "2026-10-18T00:17:46Z"
---

# Momentum, Commentary Tone, and Earnings Surprise in LLM Financial Forecasts

**Authors**: Alina Khaybullina
**Date**: 2026-10-15
**Paper ID**: [arxiv:2610.22043](https://arxiv.org/abs/2610.22043)

## Summary

This paper investigates the drivers of financial forecasting in Large Language Models (LLMs) by testing their response to synthetic earnings announcements. By independently varying price momentum, commentary tone, and earnings surprises, the author measures how six different LLM checkpoints prioritize these inputs using conditional answer-prefix scores. The findings reveal a significant bias: most models are more sensitive to the tone of the commentary and historical momentum than to the actual earnings surprise relative to consensus.

## Key Contributions

- Constructed a controlled experimental framework using synthetic earnings announcements to isolate the effects of 20-day momentum, commentary tone, and earnings surprises on LLM forecasts.
- Developed a direct-answer scoring protocol using conditional answer-prefix scores to evaluate six instruction-tuned LLMs from four model families (0.49B–7.61B parameters).
- Demonstrated that LLMs frequently prioritize non-informational commentary tone and historical price momentum over hard earnings surprises (EPS vs. consensus) in 5 out of 6 tested models.
- Established a benchmark for numerical recognition accuracy within financial contexts, reporting a wide performance range of 51.0% to 95.8% across model checkpoints.

## Limitations

The study measures observable input reliance and numerical recognition but does not identify internal reasoning mechanisms or evaluate the actual predictability of stock market returns.

## Open Questions & Future Work

- [[llm-financial-rationality-scaling]]

## Key Concepts

- [[conditional-answer-prefix-scoring]]: A technique for quantifying LLM decision-making by measuring the log-probability of specific initial tokens in a response given controlled variations in the input prompt.

## Archivist Review

The concept 'Conditional Answer-Prefix Scoring' is approved as it represents a specific, reusable evaluation protocol for quantifying model bias and decision-making in instruction-tuned models. The open question regarding scaling effects on financial rationality is approved as it addresses a significant unresolved bottleneck in the reliability of LLMs for specialized domain tasks. No datasets were identified as the paper describes a methodology for generating synthetic prompts rather than a named, standalone dataset.

### Approved Concepts
- Conditional Answer-Prefix Scoring: Provides a rigorous method for measuring LLM input reliance in instruction-tuned models without requiring full sequence generation or calibrated probability distributions.

### Approved Open Questions
- Scaling Effects on Financial Rationality: Understanding if larger models become more 'rational' or more sensitive to stylistic manipulation is critical for deploying LLMs in financial decision-making pipelines.

## Links

- [Abstract](https://arxiv.org/abs/2610.22043)
- [PDF](https://arxiv.org/pdf/2610.22043)

