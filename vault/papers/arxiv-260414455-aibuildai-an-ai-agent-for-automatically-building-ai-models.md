---
# CSL-compatible fields
title: "AIBuildAI: An AI Agent for Automatically Building AI Models"
author:
  - literal: "Ruiyi Zhang"
  - literal: "Peijia Qin"
  - literal: "Qi Cao"
  - literal: "Li Zhang"
  - literal: "Pengtao Xie"
issued:
  date-parts:
    - [2026, 4, 15]
url: "https://arxiv.org/abs/2604.14455"

# Custom fields
paper_id: "2604.14455"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  - "mle-bench"
concept_slugs:
  - "aibuildai"
dataset_slugs:
  - "mle-bench"
skill: "TimeSeriesSkill"
processed_at: "2026-04-17T05:06:21Z"
created_at: "2026-04-17T05:06:21Z"
---

# AIBuildAI: An AI Agent for Automatically Building AI Models

**Authors**: Ruiyi Zhang, Peijia Qin, Qi Cao, Li Zhang, Pengtao Xie
**Date**: 2026-04-15
**Paper ID**: [arxiv:2604.14455](https://arxiv.org/abs/2604.14455)

## Summary

AIBuildAI is a hierarchical LLM-based agent system designed to automate the full lifecycle of AI model development, addressing limitations in traditional AutoML methods. The system utilizes three specialized sub-agents—designer, coder, and tuner—to handle model strategy, implementation, and performance optimization respectively. Evaluated on the comprehensive MLE-Bench, AIBuildAI achieves state-of-the-art performance, demonstrating its capability to perform end-to-end AI development across various data modalities with minimal human intervention.

## Key Contributions

- Introduces AIBuildAI, a hierarchical agent framework for automating the entire AI model development lifecycle from task specification to implementation.
- Implements a specialized multi-agent coordination system consisting of a designer, coder, and tuner sub-agent.
- Achieves a 63.1% medal rate on the MLE-Bench, outperforming existing baselines and demonstrating human-expert-level capabilities across diverse modalities.

## Open Questions & Future Work

- [[dynamic-llm-routing-for-cost-reduction]]
- [[resource-aware-autonomous-development]]

## Key Concepts

- [[aibuildai]]: A hierarchical agent-based system that automates the end-to-end development of AI models by coordinating strategy, coding, and tuning agents.

## Archivist Review

I approved the AIBuildAI architecture as a representative hierarchical agent framework for automated modeling and MLE-Bench as a critical domain-spanning benchmark for agentic evaluation. The approved open questions capture the two primary bottlenecks identified for moving autonomous model-building agents into production: computational cost management and resource-aware scheduling. Standard filtering was applied to ensure the vault remains focused on fundamental architectural and system-level challenges rather than project-local implementation details.

### Approved Concepts
- AIBuildAI: It introduces a novel hierarchical agent framework for full-lifecycle AI model development automation.

### Approved Open Questions
- Dynamic LLM Routing Efficiency: This is critical for scaling autonomous AI development systems to production-grade environments where computational efficiency and cost-effectiveness are primary constraints.
- Scaling to Distributed Compute: This is critical for transitioning from proof-of-concept tasks to solving real-world, large-scale scientific and industrial problems.

## Datasets

- [[mle-bench]]

## Links

- [Abstract](https://arxiv.org/abs/2604.14455)
- [PDF](https://arxiv.org/pdf/2604.14455)

