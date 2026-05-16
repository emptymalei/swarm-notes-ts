---
# CSL-compatible fields
title: "Monetary Policy in the Media Spotlight: Sentiments, Signals, and Economic Impact"
author:
  - literal: "Firmin Ayivodji"
  - literal: "Etienne Briand"
  - literal: "Kevin Moran"
  - literal: "Dalibor Stevanovic"
issued:
  date-parts:
    - [2026, 5, 14]
url: "https://arxiv.org/abs/2605.15092"

# Custom fields
paper_id: "2605.15092"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "monetary-policy-sentiment-indicators"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-05-16T05:10:59Z"
created_at: "2026-05-16T05:10:59Z"
---

# Monetary Policy in the Media Spotlight: Sentiments, Signals, and Economic Impact

**Authors**: Firmin Ayivodji, Etienne Briand, Kevin Moran, Dalibor Stevanovic
**Date**: 2026-05-14
**Paper ID**: [arxiv:2605.15092](https://arxiv.org/abs/2605.15092)

## Summary

This paper investigates the role of news media in monetary policy transmission by constructing sentiment indicators from over 50,000 Canadian newspaper articles. The researchers incorporate these indicators into a behavioral New-Keynesian model, revealing that media sentiment acts as an endogenous variable that influences inflation expectations and policy reactions. Empirical results from a Bayesian structural vector autoregression (SVAR) confirm that narrative shocks drive macroeconomic fluctuations and amplify the impact of policy decisions on output and prices.

## Key Contributions

- Constructs monetary-policy sentiment indicators using a hybrid approach of dictionary methods, transformer models, and generative AI.
- Integrates media sentiment into a behavioral New-Keynesian model where sentiment is treated as an endogenous variable.
- Demonstrates that media narrative shocks significantly contribute to medium-horizon macroeconomic variance and mediate the transmission of monetary policy.

## Open Questions & Future Work

- [[llm-temporal-alignment-in-economics]]

## Key Concepts

- [[monetary-policy-sentiment-indicators]]: Indices quantifying monetary policy sentiment derived from news media through generative-AI, transformer, and dictionary-based pipelines.

## Archivist Review

The selected concept addresses a reusable methodology for constructing domain-specific sentiment indicators, while the open question highlights a fundamental methodological bottleneck regarding temporal bias in LLM-based retrospective analysis. All other candidates were rejected to maintain the required scarcity of the vault and avoid redundant or paper-local terminology.

### Approved Concepts
- Monetary-Policy Sentiment Indicators: These indicators quantify the media's filtering of central-bank communications, serving as a new endogenous variable that explains macroeconomic variance.

### Approved Open Questions
- Temporal Alignment for LLMs: Look-ahead bias compromises the validity of using LLM-based sentiment indicators as regressors in causal models or for out-of-sample forecasting, as the 'sentiment' variable becomes contaminated with future realizations.

## Links

- [Abstract](https://arxiv.org/abs/2605.15092)
- [PDF](https://arxiv.org/pdf/2605.15092)

