---
# CSL-compatible fields
title: "AutoSOTA: An End-to-End Automated Research System for State-of-the-Art AI Model Discovery"
author:
  - literal: "Yu Li"
  - literal: "Chenyang Shao"
  - literal: "Xinyang Liu"
  - literal: "Ruotong Zhao"
  - literal: "Peijie Liu"
  - literal: "Hongyuan Su"
  - literal: "Zhibin Chen"
  - literal: "Qinglong Yang"
  - literal: "Anjie Xu"
  - literal: "Yi Fang"
  - literal: "Qingbin Zeng"
  - literal: "Tianxing Li"
  - literal: "Jingbo Xu"
  - literal: "Fengli Xu"
  - literal: "Yong Li"
  - literal: "Tie-Yan Liu"
issued:
  date-parts:
    - [2026, 4, 7]
url: "https://arxiv.org/abs/2604.05550"

# Custom fields
paper_id: "2604.05550"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "nlp"
  - "computer-vision"
architectures:
  []
datasets:
  []
concept_slugs:
  - "autosota"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-08T04:55:56Z"
created_at: "2026-04-08T04:55:56Z"
---

# AutoSOTA: An End-to-End Automated Research System for State-of-the-Art AI Model Discovery

**Authors**: Yu Li, Chenyang Shao, Xinyang Liu, Ruotong Zhao, Peijie Liu, Hongyuan Su, Zhibin Chen, Qinglong Yang, Anjie Xu, Yi Fang, Qingbin Zeng, Tianxing Li, Jingbo Xu, Fengli Xu, Yong Li, Tie-Yan Liu
**Date**: 2026-04-07
**Paper ID**: [arxiv:2604.05550](https://arxiv.org/abs/2604.05550)

## Summary

AutoSOTA is an end-to-end automated research system designed to accelerate the scientific discovery process by reproducing and improving upon published AI models. It utilizes a multi-agent architecture composed of eight specialized agents that handle tasks ranging from environment configuration and code grounding to long-horizon experiment scheduling and validity supervision. Empirical evaluation across recent top-tier conference papers demonstrates that the system can reliably discover new SOTA models, often identifying complex architectural and algorithmic improvements beyond basic hyperparameter optimization.

## Key Contributions

- Introduces AutoSOTA, a multi-agent system that automates the end-to-end pipeline of reproducing and improving AI models from published research.
- Achieves the discovery of 105 new SOTA models across diverse AI fields, averaging five hours of compute per paper.
- Demonstrates the ability to transcend simple hyperparameter tuning by performing architectural innovation and algorithmic redesigns.

## Open Questions & Future Work

- [[multi-dimensional-rubric-optimization]]

## Key Concepts

- [[autosota]]: An multi-agent system designed to automate the full pipeline of reproducing and improving AI research models.

## Archivist Review

I have approved the AutoSOTA architecture as a foundational concept for research-to-optimization workflows and the open question regarding multi-dimensional rubrics for automated discovery. The rejection policy was applied to avoid capturing specific agent implementation details that are not yet established as broad primitives, while focusing on the systemic shift in AI research methodology. No datasets were approved as none were cited as central, novel, or uniquely defined contributions.

### Approved Concepts
- AutoSOTA: The system represents a novel paradigm shift in research automation by integrating end-to-end model discovery, reproduction, and optimization.

### Approved Open Questions
- Multi-dimensional Rubric Optimization: This is critical for ensuring that automated research discovery leads to meaningful scientific advancement rather than overfitting to performance benchmarks.

## Links

- [Abstract](https://arxiv.org/abs/2604.05550)
- [PDF](https://arxiv.org/pdf/2604.05550)

