---
# CSL-compatible fields
title: "PilotBench: A Benchmark for General Aviation Agents with Safety Constraints"
author:
  - literal: "Yalun Wu"
  - literal: "Haotian Liu"
  - literal: "Zhoujun Li"
  - literal: "Boyang Wang"
issued:
  date-parts:
    - [2026, 4, 10]
url: "https://arxiv.org/abs/2604.08987"

# Custom fields
paper_id: "2604.08987"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "pilot-score"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-04-13T05:10:30Z"
created_at: "2026-04-13T05:10:30Z"
---

# PilotBench: A Benchmark for General Aviation Agents with Safety Constraints

**Authors**: Yalun Wu, Haotian Liu, Zhoujun Li, Boyang Wang
**Date**: 2026-04-10
**Paper ID**: [arxiv:2604.08987](https://arxiv.org/abs/2604.08987)

## Summary

PilotBench is a new benchmark designed to assess the reasoning and physics-based predictive capabilities of LLMs in safety-critical general aviation environments. Utilizing 708 real-world trajectories across nine flight phases, the benchmark evaluates models using the custom Pilot-Score, which weighs regression accuracy against safety and instruction adherence. The study highlights a distinct trade-off between semantic controllability in LLMs and the numerical precision of traditional forecasters, revealing significant performance degradation during high-workload flight segments. These results underscore the need for hybrid architectures that integrate symbolic LLM reasoning with specialized numerical forecasting tools.

## Key Contributions

- Introduces PilotBench, a benchmark for evaluating LLMs on safety-critical general aviation trajectory and attitude prediction using 708 real-world flight trajectories.
- Proposes Pilot-Score, a novel evaluation metric that combines regression accuracy with instruction adherence and safety compliance.
- Identifies the 'Precision-Controllability Dichotomy' where LLMs offer better controllability than traditional forecasters but at the cost of significantly lower numerical precision.
- Reveals a 'Dynamic Complexity Gap' showing that LLM performance degrades significantly in high-workload flight phases, indicating brittle physics modeling.

## Open Questions & Future Work

- [[hybrid-llm-physics-control-architectures]]

## Key Concepts

- [[pilot-score]]: A composite evaluation metric that balances regression precision with instruction adherence and safety compliance for embodied AI systems.

## Archivist Review

I have approved the Pilot-Score metric as a reusable framework for evaluating embodied AI in safety-critical domains. I also approved a research question focused on hybrid architectures to address the inherent tension between LLM-based semantic reasoning and numerical precision in embodied tasks. Empirical observations such as the 'Precision-Controllability Dichotomy' were rejected as they are domain-specific findings rather than reusable methodological concepts.

### Approved Concepts
- Pilot-Score: Provides a standardized methodology for evaluating embodied AI agents in safety-critical domains by balancing numerical precision with qualitative instruction adherence and safety compliance.

### Approved Open Questions
- Hybrid LLM-Physics Control Architectures: This addresses the fundamental 'Precision-Controllability Dichotomy' and 'Dynamic Complexity Gap' identified in safety-critical embodied AI, which are central barriers to deploying LLMs in physical environments.

### Rejected Candidates
- [concept] Precision-Controllability Dichotomy (`precision-controllability-dichotomy`) - paper_local: This describes a specific performance observation within the paper's empirical results rather than a generalizable architectural or algorithmic concept.
- [concept] Dynamic Complexity Gap (`dynamic-complexity-gap`) - paper_local: This refers to an empirical finding regarding LLM performance degradation in aviation-specific flight phases and lacks the generality of a reusable framework or method.

## Links

- [Abstract](https://arxiv.org/abs/2604.08987)
- [PDF](https://arxiv.org/pdf/2604.08987)

