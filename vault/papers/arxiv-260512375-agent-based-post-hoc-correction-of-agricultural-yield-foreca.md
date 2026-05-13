---
# CSL-compatible fields
title: "Agent-Based Post-Hoc Correction of Agricultural Yield Forecasts"
author:
  - literal: "Matthew Beddows"
  - literal: "Aiden Durrant"
  - literal: "Georgios Leontidis"
issued:
  date-parts:
    - [2026, 5, 12]
url: "https://arxiv.org/abs/2605.12375"

# Custom fields
paper_id: "2605.12375"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "forecasting"
  - "llm-agent"
  - "domain-adaptation"
  - "time-series-forecasting"
architectures:
  []
datasets:
  - "usda-corn-harvest-dataset"
concept_slugs:
  - "agent-based-post-hoc-correction"
dataset_slugs:
  - "usda-corn-harvest-dataset"
skill: "TimeSeriesSkill"
processed_at: "2026-05-13T05:23:08Z"
created_at: "2026-05-13T05:23:08Z"
---

# Agent-Based Post-Hoc Correction of Agricultural Yield Forecasts

**Authors**: Matthew Beddows, Aiden Durrant, Georgios Leontidis
**Date**: 2026-05-12
**Paper ID**: [arxiv:2605.12375](https://arxiv.org/abs/2605.12375)

## Summary

This paper introduces an LLM agent framework designed to perform post-hoc correction of crop yield forecasts in environments where high-resolution environmental data is unavailable. By utilizing tools for phase detection, bias learning, and range validation, the framework embeds agricultural domain knowledge to refine predictions from established models. Experimental results on strawberry and corn datasets show significant improvements in MAE and MASE across various baselines, demonstrating the potential for LLM-driven post-processing in data-sparse domains.

## Key Contributions

- Introduced an LLM-based agent framework for post-hoc correction of agricultural yield forecasts that functions without high-resolution sensor or satellite data.
- Demonstrated that agent-refined XGBoost achieves 20% lower MAE and 56% lower MASE on strawberry yield prediction compared to raw model output.
- Showed consistent performance gains across diverse baseline architectures including Random Forest and Moirai2, with Llama 3.1 8B proving more robust than LLaVA 13B.

## Open Questions & Future Work

- [[real-time-agent-optimization]]
- [[agent-decision-explainability]]

## Key Concepts

- [[agent-based-post-hoc-correction]]: An LLM agent framework that improves time-series forecasts by applying post-hoc domain-aware corrections via tool-based domain knowledge integration.

## Archivist Review

I approved the agent-based correction concept for its modular, tool-centric approach to post-hoc forecasting improvement. The two open questions capture significant, reusable bottlenecks related to the operationalization (latency) and interpretability of LLM-agent reasoning in high-stakes forecasting. I also approved the USDA dataset as it provides a standardized, domain-specific benchmark for crop yield performance.

### Approved Concepts
- Agent-Based Post-Hoc Correction: This provides a novel approach to improving black-box model performance in data-constrained agricultural environments without requiring retraining or high-fidelity sensor data.

### Approved Open Questions
- Real-time Agent Optimization: Computational overhead is a primary barrier preventing the deployment of intelligent post-processing systems in commercial settings.
- Agent Decision Explainability: Explainability is critical for trust and accountability in commercial decision-support systems where users must understand the rationale behind AI-driven adjustments.

## Datasets

- [[usda-corn-harvest-dataset]]

## Links

- [Abstract](https://arxiv.org/abs/2605.12375)
- [PDF](https://arxiv.org/pdf/2605.12375)

