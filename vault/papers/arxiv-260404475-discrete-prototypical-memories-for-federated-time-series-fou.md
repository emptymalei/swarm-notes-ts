---
# CSL-compatible fields
title: "Discrete Prototypical Memories for Federated Time Series Foundation Models"
author:
  - literal: "Liwei Deng"
  - literal: "Qingxiang Liu"
  - literal: "Xinhe Niu"
  - literal: "Shengchao Chen"
  - literal: "Sheng Sun"
  - literal: "Yuankai Wu"
  - literal: "Guodong Long"
  - literal: "Yuxuan Liang"
issued:
  date-parts:
    - [2026, 4, 6]
url: "https://arxiv.org/abs/2604.04475"

# Custom fields
paper_id: "2604.04475"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "discrete-prototypical-memory"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-07T04:53:47Z"
created_at: "2026-04-07T04:53:47Z"
---

# Discrete Prototypical Memories for Federated Time Series Foundation Models

**Authors**: Liwei Deng, Qingxiang Liu, Xinhe Niu, Shengchao Chen, Sheng Sun, Yuankai Wu, Guodong Long, Yuxuan Liang
**Date**: 2026-04-06
**Paper ID**: [arxiv:2604.04475](https://arxiv.org/abs/2604.04475)

## Summary

This paper addresses the challenges of using Large Language Models in federated learning for time series, specifically focusing on semantic misalignment and the limitations of continuous latent spaces. The authors propose FeDPM, a federated framework that uses discrete prototypical memories to represent recurring time-series regimes. By aligning these memories across domains while allowing for local updates, the model successfully bridges the gap between text-centric LLM spaces and heterogeneous time-series semantics.

## Key Contributions

- Introduces FeDPM, a federated learning framework for time series foundation models using discrete prototypical memories to address semantic misalignment.
- Proposes a dual-layer memory mechanism that aligns cross-domain memory priors while maintaining domain-specific updates for personalized knowledge.
- Demonstrates improved performance over standard federated fine-tuning by mapping heterogeneous time series data into a unified discrete latent space.

## Open Questions & Future Work

- [[efficient-federated-prototype-alignment]]

## Key Concepts

- [[discrete-prototypical-memory]]: A representation mechanism that maps time-series data into a discrete, learnable prototypical latent space to improve semantic alignment in foundation models.

## Archivist Review

The paper introduces 'Discrete Prototypical Memory' as a mechanism to handle semantic misalignment in LLM-based time series foundation models. I approved this concept because it offers a distinct alternative to standard continuous latent space modeling. I also approved one consolidated open question regarding the efficiency of prototype alignment and communication, as this addresses a specific, persistent bottleneck in decentralized time series modeling. Other candidates were rejected for being too generic or redundant.

### Approved Concepts
- Discrete Prototypical Memory: Provides a structured approach to mapping heterogeneous, continuous time-series data into unified, discrete semantic regimes, which is more alignment-friendly for LLM-based foundation models.

### Approved Open Questions
- Efficient Federated Prototype Alignment: Communication efficiency and computational scalability are fundamental bottlenecks to deploying foundation models in decentralized, resource-constrained federated environments.

### Rejected Candidates
- [open_question] Adaptive Hyperparameter Selection Mechanism (`adaptive-hyperparameter-selection-fl-tsfm`) - generic: Hyperparameter tuning is a generic challenge across all of ML and is not specific to the unique architectural contributions of this work.
- [open_question] Efficient Alignment and Transmission (`efficient-memory-alignment-sparse-transmission`) - duplicate_existing: Redundant with the approved open question; consolidated into a more concise, precise focus on alignment and communication costs.

## Links

- [Abstract](https://arxiv.org/abs/2604.04475)
- [PDF](https://arxiv.org/pdf/2604.04475)

