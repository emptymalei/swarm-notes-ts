---
# CSL-compatible fields
title: "Frontier Coding Agents Can Now Implement an AlphaZero Self-Play Machine Learning Pipeline For Connect Four That Performs Comparably to an External Solver"
author:
  - literal: "Joshua Sherwood"
  - literal: "Ben Aybar"
  - literal: "Benjamin Kaplan"
issued:
  date-parts:
    - [2026, 4, 27]
url: "https://arxiv.org/abs/2604.25067"

# Custom fields
paper_id: "2604.25067"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-29T05:12:12Z"
created_at: "2026-04-29T05:12:12Z"
---

# Frontier Coding Agents Can Now Implement an AlphaZero Self-Play Machine Learning Pipeline For Connect Four That Performs Comparably to an External Solver

**Authors**: Joshua Sherwood, Ben Aybar, Benjamin Kaplan
**Date**: 2026-04-27
**Paper ID**: [arxiv:2604.25067](https://arxiv.org/abs/2604.25067)

## Summary

This paper presents a new benchmark designed to assess the capability of AI coding agents to autonomously implement complex machine learning pipelines, such as AlphaZero for Connect Four, given minimal instructions. By evaluating agents against a known solver (Pascal Pons), the researchers identify significant performance differentiation among frontier models and observe emergent behaviors like non-optimal time-budget utilization. The study suggests this task serves as an early warning signal for recursive self-improvement capabilities, as performance has shifted from failure to near-saturation within a few months.

## Key Contributions

- Introduces a recursive self-improvement benchmark evaluating AI agents on their ability to autonomously implement end-to-end ML research pipelines from minimal task descriptions.
- Demonstrates that frontier models have moved from an inability to reliably implement AlphaZero-style pipelines for Connect Four to near-saturation performance within a three-hour budget.
- Provides empirical evidence of agent-specific performance variance and behavior anomalies, such as time-budget usage discrepancies in GPT-5.4.

## Open Questions & Future Work

- [[generalization-to-novel-research-capabilities]]
- [[detecting-strategic-underperformance]]

## Archivist Review

I approved the two open questions regarding recursive self-improvement and sandbagging detection as they represent substantial, unresolved challenges in AI capability assessment. I rejected all concept candidates as none met the strict criteria for permanent, reusable technical artifacts central to the paper's contribution beyond the specific benchmark instance.

### Approved Open Questions
- Generalization to Novel Research: Clarifying the relationship between replication capabilities and novel research capabilities is critical for establishing effective early warning systems for recursive self-improvement.
- Detecting Strategic Underperformance: As models become more capable and evaluation-aware, the inability to reliably detect strategic underperformance compromises the integrity of dangerous capability benchmarks.

### Rejected Candidates
- [open_question] Generalization to Novel Research (`generalization-to-novel-research`) - duplicate_existing: Renamed to be more precise.

## Links

- [Abstract](https://arxiv.org/abs/2604.25067)
- [PDF](https://arxiv.org/pdf/2604.25067)

