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
  - "nlp"
architectures:
  []
datasets:
  []
concept_slugs:
  - "monetary-policy-sentiment-indicators"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-05-17T05:22:39Z"
created_at: "2026-05-17T05:22:39Z"
---

# Monetary Policy in the Media Spotlight: Sentiments, Signals, and Economic Impact

**Authors**: Firmin Ayivodji, Etienne Briand, Kevin Moran, Dalibor Stevanovic
**Date**: 2026-05-14
**Paper ID**: [arxiv:2605.15092](https://arxiv.org/abs/2605.15092)

## Summary

This paper explores how news media sentiment influences monetary policy transmission by constructing indicators from over 50,000 newspaper articles. Using a behavioral New-Keynesian model and Bayesian SVAR, the researchers demonstrate that media sentiment is not merely informative but an active driver of economic expectations and policy dynamics. Their findings indicate that 'narrative shocks' significantly influence macroeconomic variance and that the feedback loop between media sentiment and central bank policy is central to the transmission of monetary policy to output and prices.

## Key Contributions

- Constructs novel monetary-policy sentiment indicators from a large-scale Canadian newspaper corpus using a multi-model pipeline.
- Demonstrates that media sentiment significantly impacts household expectations and improves GDP and inflation forecasting.
- Integrates media sentiment into a behavioral New-Keynesian model, proving that central bank reactions to sentiment are a vital component of monetary policy transmission.
- Identifies a 'narrative shock' via Bayesian SVAR analysis, showing it accounts for a non-trivial share of medium-horizon macroeconomic variance.

## Open Questions & Future Work

- [[llm-temporal-alignment-bias]]

## Key Concepts

- [[monetary-policy-sentiment-indicators]]: A hybrid construction pipeline using dictionary, transformer, and generative-AI techniques to quantify monetary-policy narratives from news media.

## Archivist Review

I have approved the concept of Monetary Policy Sentiment Indicators as it provides a clear, multi-methodological framework for economic narrative analysis that is likely to be reused in behavioral macroeconomics. The open question regarding LLM temporal alignment addresses a fundamental, recurring bottleneck in applying modern foundation models to historical economic time-series analysis without contaminating inference with post-event information.

### Approved Concepts
- Monetary Policy Sentiment Indicators: This represents a formal methodology for translating news narratives into quantitative exogenous drivers for macroeconomic models.

### Approved Open Questions
- Mitigating LLM look-ahead bias: Look-ahead bias currently undermines the validity of applying state-of-the-art LLMs to historical longitudinal data, especially in policy transmission and causal discovery tasks.

## Links

- [Abstract](https://arxiv.org/abs/2605.15092)
- [PDF](https://arxiv.org/pdf/2605.15092)

