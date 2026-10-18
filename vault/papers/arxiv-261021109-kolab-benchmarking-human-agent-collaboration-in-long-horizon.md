---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Kolab: Benchmarking Human-Agent Collaboration in Long-Horizon Workflows"
description: "Kolab is a new benchmark designed to evaluate human-agent collaboration in complex, long-horizon professional workflows, moving beyond standard automation metrics. The dataset includes over 115 hours of multimodal screen recordings from 50 professionals across 40 occupations, paired with subjective quality and satisfaction judgments. The benchmark requires models to forecast how humans will use agent contributions (adoption vs. rejection) and to verify collaboration quality. Experimental results show that frontier models currently struggle with these tasks, often overestimating the success of their interactions and failing to leverage long-term context to improve prediction accuracy."
resource: "https://arxiv.org/abs/2610.21109"
tags:
  - "ai-agents"
  - "agent-interaction"
  - "agentic-workflow"
  - "evaluation-benchmark"
  - "large-language-models"
  - "nlp"
  - "human-computer-interaction"
timestamp: "2026-10-18T00:25:04Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Shirley Anugrah Hayati"
  - literal: "Patricia Anugrah Setiani"
  - literal: "Ruizi Wang"
  - literal: "Zhouyi Li"
  - literal: "Khanh Chi Le"
  - literal: "Young-Jun Lee"
  - literal: "Dongyeop Kang"
issued:
  date-parts:
    - [2026, 10, 15]

# Domain-specific custom fields
paper_id: "2610.21109"
paper_source: "arxiv"
architectures:
  []
concepts:
  []
datasets:
  - name: "Kolab"
    description: "A multimodal dataset containing 115+ hours of screen recordings from 50 professionals across 40 occupations, capturing long-horizon human-agent collaboration along with subjective quality and satisfaction judgments."
open_questions:
  - name: "anticipating-human-revision-patterns"
    description: "How can agents be designed to anticipate human revision patterns (adopting, modifying, or rejecting) to improve their planning in collaborative, long-horizon environments, particularly when they must operate without immediate feedback?"
  - name: "long-horizon-context-utilization-agents"
    description: "What architectural or training paradigms are required for models to effectively process and synthesize long-horizon multimodal screen context to assess collaboration quality and task progress accurately?"
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T00:25:04Z"
created_at: "2026-10-18T00:25:04Z"
---

# Kolab: Benchmarking Human-Agent Collaboration in Long-Horizon Workflows

**Authors**: Shirley Anugrah Hayati, Patricia Anugrah Setiani, Ruizi Wang, Zhouyi Li, Khanh Chi Le, Young-Jun Lee, Dongyeop Kang
**Date**: 2026-10-15
**Paper ID**: [arxiv:2610.21109](https://arxiv.org/abs/2610.21109)

## Summary

Kolab is a new benchmark designed to evaluate human-agent collaboration in complex, long-horizon professional workflows, moving beyond standard automation metrics. The dataset includes over 115 hours of multimodal screen recordings from 50 professionals across 40 occupations, paired with subjective quality and satisfaction judgments. The benchmark requires models to forecast how humans will use agent contributions (adoption vs. rejection) and to verify collaboration quality. Experimental results show that frontier models currently struggle with these tasks, often overestimating the success of their interactions and failing to leverage long-term context to improve prediction accuracy.

## Key Contributions

- Introduced Kolab, a multimodal dataset of 115+ hours of screen recordings capturing 50 professionals across 40 occupations collaborating with AI agents on complex, long-horizon tasks.
- Defined two novel benchmark tasks for agent evaluation: forecasting human utilization of agent outputs (adopt, modify, or reject) and verifying human judgments of collaboration satisfaction.
- Demonstrated that current frontier models struggle to distinguish between high- and low-quality collaborations and fail to effectively utilize long-horizon context to predict human behavior.

## Limitations

Frontier models currently overestimate collaboration effectiveness and do not consistently improve performance with increased workflow context length.

## Open Questions & Future Work

- [[anticipating-human-revision-patterns]]
- [[long-horizon-context-utilization-agents]]

## Archivist Review

I approved the Kolab dataset as it represents a significant and unique multimodal artifact for the study of human-agent collaboration. Two open questions were approved as they highlight specific, unresolved technical challenges in forecasting human feedback loops and leveraging long-horizon multimodal context. The concept 'Kolab Benchmark' was rejected because it is synonymous with the dataset entry in this context.

### Approved Open Questions
- Forecasting Human Revision Dynamics: Understanding human intent and revision behavior is critical for agents to become truly useful partners rather than just execution engines.
- Scaling Context in Collaborative Agents: Efficiently processing long-term historical context is a bottleneck for state-of-the-art agentic models, especially in multimodal settings.

### Rejected Candidates
- [concept] Kolab Benchmark (`kolab-benchmark`) - duplicate_existing: The benchmark is effectively defined by the dataset and its associated tasks; a separate concept note would be redundant with the Kolab dataset entry.

## Datasets

- [[Kolab]]

## Links

- [Abstract](https://arxiv.org/abs/2610.21109)
- [PDF](https://arxiv.org/pdf/2610.21109)

