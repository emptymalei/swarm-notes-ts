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
  - "agents"
  - "evaluation"
  - "benchmarking"
architectures:
  []
datasets:
  []
concept_slugs:
  - "futuresim"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-05-16T05:10:31Z"
created_at: "2026-05-16T05:10:31Z"
---

# FutureSim: Replaying World Events to Evaluate Adaptive Agents

**Authors**: Shashwat Goel, Nikhil Chandak, Arvindh Arun, Ameya Prabhu, Steffen Staab, Moritz Hardt, Maksym Andriushchenko, Jonas Geiping
**Date**: 2026-05-14
**Paper ID**: [arxiv:2605.15188](https://arxiv.org/abs/2605.15188)

## Summary

FutureSim is a grounded simulation benchmark designed to evaluate how AI agents adapt to dynamic environments by replaying chronologically ordered real-world news and event resolutions. The framework requires agents to forecast events beyond their training knowledge cutoff, providing a high-fidelity testbed for long-horizon prediction. Evaluation of frontier models using this benchmark reveals substantial gaps in agent adaptability, with many models failing to exceed basic baseline performance metrics.

## Key Contributions

- Introduces FutureSim, a benchmark framework that evaluates AI agents on their ability to forecast real-world events across a three-month chronological replay.
- Demonstrates that current frontier agents exhibit significant limitations in long-horizon forecasting, with top performance at 25% accuracy and many underperforming baseline models.
- Establishes a realistic evaluation setting to analyze agent capabilities in test-time adaptation, search, memory, and uncertainty reasoning.

## Key Concepts

- [[futuresim]]: A grounded simulation framework that replays chronologically ordered real-world events to evaluate the long-horizon predictive capabilities and adaptability of AI agents.

## Archivist Review

FutureSim is approved as a landmark evaluation framework for testing AI agent adaptability in dynamic, long-horizon, real-world environments. No other candidates were provided, and the framework itself is distinct enough from existing benchmarks to warrant a standalone entry.

### Approved Concepts
- FutureSim: It provides a novel, grounded framework for evaluating agent adaptability in open-ended real-world scenarios by replaying chronologically ordered events.

## Links

- [Abstract](https://arxiv.org/abs/2605.15188)
- [PDF](https://arxiv.org/pdf/2605.15188)

