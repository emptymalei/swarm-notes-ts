---
# CSL-compatible fields
title: "LLM-Augmented Traffic Signal Control with LSTM-Based Traffic State Prediction and Safety-Constrained Decision Support"
author:
  - literal: "Jiazhao Shi"
issued:
  date-parts:
    - [2026, 4, 26]
url: "https://arxiv.org/abs/2604.23902"

# Custom fields
paper_id: "2604.23902"
paper_source: "arxiv"
domain: "intelligent-transportation-systems"
tags:
  - "Intelligent Transportation Systems"
  - "Traffic Signal Control"
  - "Large Language Models"
  - "LSTM"
  - "Safety-Constrained Control"
architectures:
  []
datasets:
  []
concept_slugs:
  - "safety-constrained-decision-support"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-04-28T05:16:22Z"
created_at: "2026-04-28T05:16:22Z"
---

# LLM-Augmented Traffic Signal Control with LSTM-Based Traffic State Prediction and Safety-Constrained Decision Support

**Authors**: Jiazhao Shi
**Date**: 2026-04-26
**Paper ID**: [arxiv:2604.23902](https://arxiv.org/abs/2604.23902)

## Summary

This paper introduces an LLM-augmented traffic signal control framework that enhances decision-making in intelligent transportation systems by combining LSTM-based state prediction with structured LLM reasoning. The system generates candidate actions and provides natural-language explanations for traffic management, which are then validated by a safety filter before execution to ensure reliability. Experimental results using the SUMO simulator demonstrate that this approach significantly improves traffic efficiency under dynamic and surge demand conditions compared to conventional methods.

## Key Contributions

- Introduced an LLM-augmented framework for traffic signal control that decouples high-level reasoning from low-level control actions.
- Developed a hybrid module combining LSTM-based traffic state prediction with an LLM for structured congestion diagnosis and decision explanation.
- Demonstrated superior efficiency over fixed-time and rule-based baselines in non-recurrent and surge traffic scenarios, maintaining zero constraint violations.

## Key Concepts

- [[safety-constrained-decision-support]]: A framework integrating LLM reasoning with a formal safety filter to validate control decisions before execution.

## Archivist Review

I approved the 'safety-constrained decision support' concept as it represents a broader architectural pattern for embedding non-deterministic LLM reasoning into safety-critical control loops, which is highly reusable. I rejected the application-specific framework and the simulator tool as they did not meet the novelty or reusability thresholds for the vault.

### Approved Concepts
- Safety-constrained decision support: It provides a mechanism to safely bridge LLM reasoning with high-stakes physical control systems.

### Rejected Candidates
- [concept] LLM-augmented traffic signal control (`llm-augmented-traffic-signal-control`) - paper_local: This is a specific application instance rather than a reusable architectural methodology.
- [dataset] SUMO Simulation (`sumo-simulation`) - not_novel: SUMO is a well-known open-source traffic simulator tool, not a unique or novel dataset.

## Links

- [Abstract](https://arxiv.org/abs/2604.23902)
- [PDF](https://arxiv.org/pdf/2604.23902)

