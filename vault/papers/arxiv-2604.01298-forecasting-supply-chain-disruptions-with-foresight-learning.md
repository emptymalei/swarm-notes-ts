---
# CSL-compatible fields
title: "Forecasting Supply Chain Disruptions with Foresight Learning"
author:
  - literal: "Benjamin Turtel"
  - literal: "Paul Wilczewski"
  - literal: "Kris Skotheim"
issued:
  date-parts:
    - [2026, 4, 1]
url: "https://arxiv.org/abs/2604.01298"

# Custom fields
paper_id: "2604.01298"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "nlp"
architectures:
  []
datasets:
  - "LightningRodLabs/supply-chain-predictions"
concept_slugs:
  - "foresight-learning"
dataset_slugs:
  - "lightningrodlabssupply-chain-predictions"
skill: "TimeSeriesSkill"
processed_at: "2026-04-03T05:24:55Z"
created_at: "2026-04-03T05:24:55Z"
---

# Forecasting Supply Chain Disruptions with Foresight Learning

**Authors**: Benjamin Turtel, Paul Wilczewski, Kris Skotheim
**Date**: 2026-04-01
**Paper ID**: [arxiv:2604.01298](https://arxiv.org/abs/2604.01298)

## Summary

This paper addresses the challenge of predicting infrequent, high-impact supply chain disruptions by training LLMs to output calibrated probabilistic forecasts. The authors introduce a framework that utilizes realized disruption outcomes as supervision to adapt LLMs for domain-specific forecasting. Experimental results demonstrate significant improvements over baseline models, including GPT-5, in predictive accuracy and calibration. The study suggests that such domain-specific training facilitates more structured reasoning capabilities in LLMs, improving their utility for decision-ready signal generation.

## Key Contributions

- Introduces 'Foresight Learning,' a framework that trains LLMs to produce calibrated probabilistic forecasts for infrequent, high-impact supply chain events.
- Demonstrates that the framework outperforms general-purpose models like GPT-5 in accuracy, calibration, and precision for disruption prediction.
- Provides empirical evidence that task-specific training induces structured, reliable probabilistic reasoning within LLMs without requiring explicit prompting.

## Open Questions & Future Work

- [[long-horizon-supply-chain-risk-forecasting]]

## Key Concepts

- [[foresight-learning]]: A training framework for adapting LLMs to generate calibrated probabilistic forecasts for rare, high-impact events using realized outcomes as supervision.

## Archivist Review

I approved the 'Foresight Learning' concept as it defines a distinct paradigm for domain-adapting LLMs for rare-event forecasting, which is highly reusable. I also approved the dataset as a central artifact for evaluating this class of models. The open question was refined to focus on the technical transition from binary, short-term classification to continuous, long-term risk modeling, which is a known challenge in high-impact event forecasting.

### Approved Concepts
- Foresight Learning: It provides a task-specific training paradigm for adapting large language models to generate calibrated probabilistic forecasts for rare events, addressing a significant limitation in general-purpose models.

### Approved Open Questions
- Long-Horizon Supply Chain Forecasting: This represents a critical performance bottleneck in moving from simple detection to reliable long-term risk assessment in supply chains.

## Datasets

- [[lightningrodlabssupply-chain-predictions]]

## Links

- [Abstract](https://arxiv.org/abs/2604.01298)
- [PDF](https://arxiv.org/pdf/2604.01298)

