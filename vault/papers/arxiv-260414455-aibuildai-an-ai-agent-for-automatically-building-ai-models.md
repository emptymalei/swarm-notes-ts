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
  - "ai-agents"
  - "automl"
  - "large-language-models"
architectures:
  []
datasets:
  - "mle-bench"
concept_slugs:
  - "aibuildai"
dataset_slugs:
  - "mle-bench"
skill: "TimeSeriesSkill"
processed_at: "2026-04-18T04:52:55Z"
created_at: "2026-04-18T04:52:55Z"
---

# AIBuildAI: An AI Agent for Automatically Building AI Models

**Authors**: Ruiyi Zhang, Peijia Qin, Qi Cao, Li Zhang, Pengtao Xie
**Date**: 2026-04-15
**Paper ID**: [arxiv:2604.14455](https://arxiv.org/abs/2604.14455)

## Summary

AIBuildAI is a hierarchical multi-agent framework designed to automate the complete AI model development process, from task specification and architectural design to implementation and performance tuning. The system employs three specialized LLM-based sub-agents—designer, coder, and tuner—to perform multi-step reasoning and tool use. Evaluated on the MLE-Bench dataset, AIBuildAI achieves a 63.1% medal rate, outperforming existing AutoML baselines and demonstrating human-level capability in diverse machine learning tasks.

## Key Contributions

- Introduces AIBuildAI, a hierarchical multi-agent system coordinating design, implementation, and tuning sub-agents for automated end-to-end AI model creation.
- Demonstrates that AIBuildAI achieves state-of-the-art performance on MLE-Bench, securing a 63.1% medal rate.
- Provides empirical evidence that hierarchical LLM agents can effectively replicate the end-to-end workflows of experienced AI engineers.

## Open Questions & Future Work

- [[autonomous-resource-management-for-ml-agents]]
- [[structured-knowledge-accumulation-for-ml-agents]]

## Key Concepts

- [[aibuildai]]: A hierarchical multi-agent framework that automates the end-to-end AI model development lifecycle.

## Archivist Review

I approved the AIBuildAI hierarchical agent framework as a novel architectural pattern for autonomous ML development. The MLE-Bench dataset was approved as a critical, reusable benchmark for this specific domain. The two open questions regarding large-scale resource management and structured knowledge accumulation were approved as they represent fundamental scaling bottlenecks for current autonomous ML systems beyond simple benchmark environments.

### Approved Concepts
- AIBuildAI: Establishes a hierarchical multi-agent architectural pattern (designer, coder, tuner) for end-to-end automation of the machine learning development lifecycle.

### Approved Open Questions
- Autonomous Resource Management for ML Agents: Bridging the gap between sandbox evaluation and large-scale industrial training is essential for the practical utility of autonomous AI development systems.
- Structured Knowledge Accumulation for ML Agents: Structured knowledge accumulation is a critical bottleneck for evolving these agents from zero-shot reasoning to cumulative, expert-level system performance.

## Datasets

- [[mle-bench]]

## Links

- [Abstract](https://arxiv.org/abs/2604.14455)
- [PDF](https://arxiv.org/pdf/2604.14455)

