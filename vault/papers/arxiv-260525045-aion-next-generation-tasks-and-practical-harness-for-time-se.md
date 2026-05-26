---
# CSL-compatible fields
title: "AION: Next-Generation Tasks and Practical Harness for Time Series"
author:
  - literal: "Tianxiang Zhan"
  - literal: "Xiaobao Song"
  - literal: "Tong Guan"
  - literal: "Shirui Pan"
  - literal: "Ming Jin"
issued:
  date-parts:
    - [2026, 5, 24]
url: "https://arxiv.org/abs/2605.25045"

# Custom fields
paper_id: "2605.25045"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "aion-harness"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-26T05:28:41Z"
created_at: "2026-05-26T05:28:41Z"
---

# AION: Next-Generation Tasks and Practical Harness for Time Series

**Authors**: Tianxiang Zhan, Xiaobao Song, Tong Guan, Shirui Pan, Ming Jin
**Date**: 2026-05-24
**Paper ID**: [arxiv:2605.25045](https://arxiv.org/abs/2605.25045)

## Summary

The paper addresses the limitations of current time series forecasting benchmarks by introducing AION, a framework for realistic, agent-driven task execution. Moving beyond simple point-prediction metrics, AION structures tasks into tuples of file, workspace, and validation, facilitating complex reasoning, temporal constraints, and multi-layered review. By integrating explicit design principles like temporal grounding and knowledge-grounded reasoning, the harness improves transparency and reliability in time series analysis workflows. Empirical results on a store sales prediction task demonstrate the harness's ability to produce robust process traces and artifact-driven outputs.

## Key Contributions

- Formalized next-generation time series tasks as three-component tuples comprising task files, workspaces, and validation interfaces.
- Introduced AION, a modular harness integrating agents, skills, rules, memory, and protocols for complex time series decision support.
- Demonstrated through a Kaggle Store Sales case study that AION increases process transparency and reliability compared to standard direct-build agent modes.

## Key Concepts

- [[aion-harness]]: A modular time series harness for agent-based tasks consisting of agents, skills, rules, memory, evaluation, and protocols.

## Archivist Review

I approved the AION Harness as a central framework for agentic time series workflows, emphasizing its modular structure which is likely to recur. I rejected the concept of 'next-gen time series tasks' because it serves as an application framing/definition rather than a distinct reusable method. No datasets or open questions were proposed, and the contribution is clearly focused on the harness itself.

### Approved Concepts
- AION Harness: Provides a structured framework to move beyond simple forecasting toward comprehensive, agent-driven time series decision support.

### Rejected Candidates
- [concept] Next-generation time series tasks (`next-gen-time-series-tasks`) - subcomponent_of_broader_mechanism: This is better described as a task definition format rather than a central algorithmic concept or mechanism.

## Links

- [Abstract](https://arxiv.org/abs/2605.25045)
- [PDF](https://arxiv.org/pdf/2605.25045)

