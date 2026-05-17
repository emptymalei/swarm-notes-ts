---
# CSL-compatible fields
title: "FutureSim: Replaying World Events to Evaluate Adaptive Agents"
author:
  - literal: "Shashwat Goel"
  - literal: "Nikhil Chandak"
  - literal: "Arvindh Arun"
  - literal: "Ameya Prabhu"
  - literal: "Steffen Staab"
  - literal: "Moritz Hardt"
  - literal: "Maksym Andriushchenko"
  - literal: "Jonas Geiping"
issued:
  date-parts:
    - [2026, 5, 14]
url: "https://arxiv.org/abs/2605.15188"

# Custom fields
paper_id: "2605.15188"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "futuresim"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-05-17T05:22:11Z"
created_at: "2026-05-17T05:22:11Z"
---

# FutureSim: Replaying World Events to Evaluate Adaptive Agents

**Authors**: Shashwat Goel, Nikhil Chandak, Arvindh Arun, Ameya Prabhu, Steffen Staab, Moritz Hardt, Maksym Andriushchenko, Jonas Geiping
**Date**: 2026-05-14
**Paper ID**: [arxiv:2605.15188](https://arxiv.org/abs/2605.15188)

## Summary

FutureSim is a benchmarking framework designed to evaluate the adaptive capabilities of AI agents in dynamic environments by replaying real-world events chronologically. By requiring agents to forecast unfolding news and resolve queries over a three-month horizon, the framework reveals significant limitations in current frontier models' ability to update their knowledge and reason about evolving global events. This approach provides a rigorous, longitudinal testbed for research into long-horizon adaptation, memory, and uncertainty quantification in real-world scenarios.

## Key Contributions

- Introduces FutureSim, a grounded simulation benchmark for evaluating AI agent adaptation using chronological real-world news and event data.
- Demonstrates that current frontier models struggle with long-horizon forecasting in dynamic environments, with many showing negative Brier skill scores.
- Provides a realistic experimental setup for studying long-horizon test-time adaptation, search, and reasoning about uncertainty in open-ended scenarios.

## Key Concepts

- [[futuresim]]: A grounded simulation framework that evaluates AI agent performance by replaying chronological real-world news and events to assess long-horizon adaptation and forecasting.

## Archivist Review

I have approved FutureSim as a concept because it represents a distinct methodological framework for evaluating AI agent adaptation in long-horizon dynamic settings, which is likely to see further adoption in LLM evaluation research. No open questions or datasets were approved as the former were not explicitly formulated as fundamental bottlenecks and the latter was essentially part of the framework itself.

### Approved Concepts
- FutureSim: It is the central framework proposed for evaluating AI agents' adaptive capabilities in open-ended, dynamic environments through chronological real-world event replay.

## Links

- [Abstract](https://arxiv.org/abs/2605.15188)
- [PDF](https://arxiv.org/pdf/2605.15188)

