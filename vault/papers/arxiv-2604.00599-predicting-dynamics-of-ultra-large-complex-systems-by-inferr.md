---
# CSL-compatible fields
title: "Predicting Dynamics of Ultra-Large Complex Systems by Inferring Governing Equations"
author:
  - literal: "Qi Shao"
  - literal: "Duxin Chen"
  - literal: "Jiawen Chen"
  - literal: "Yujie Zeng"
  - literal: "Athen Ma"
  - literal: "Wenwu Yu, Vito Latora, Wei Lin"
issued:
  date-parts:
    - [2026, 4, 1]
url: "https://arxiv.org/abs/2604.00599"

# Custom fields
paper_id: "2604.00599"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "causal-insight"
architectures:
  []
datasets:
  []
concept_slugs:
  - "sparse-identification-graph-neural-network"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-04-02T05:38:17Z"
created_at: "2026-04-02T05:38:17Z"
---

# Predicting Dynamics of Ultra-Large Complex Systems by Inferring Governing Equations

**Authors**: Qi Shao, Duxin Chen, Jiawen Chen, Yujie Zeng, Athen Ma, Wenwu Yu, Vito Latora, Wei Lin
**Date**: 2026-04-01
**Paper ID**: [arxiv:2604.00599](https://arxiv.org/abs/2604.00599)

## Summary

The paper introduces the Sparse Identification Graph Neural Network (SIGN), a framework that bridges the gap between scalable black-box neural models and interpretable equation discovery methods. By treating symbolic discovery as an edge-level operation, SIGN enables the inference of governing equations for complex networked systems with over 100,000 nodes. The approach demonstrates robust performance against noise and sparse sampling, successfully identifying compact predictive models for high-dimensional dynamics such as global sea surface temperatures.

## Key Contributions

- Introduces Sparse Identification Graph Neural Network (SIGN) to infer governing equations for complex networks with over 100,000 nodes.
- Decouples the scalability of sparse identification from network size by defining symbolic discovery at the edge level.
- Demonstrates high precision and long-term predictive robustness on benchmark systems including chaotic oscillators, neural dynamics, and sea surface temperature data.

## Open Questions & Future Work

- [[multi-channel-state-discovery]]
- [[higher-order-delayed-interactions]]

## Key Concepts

- [[sparse-identification-graph-neural-network]]: A graph neural network framework for inferring governing equations of large-scale networked systems by treating symbolic discovery as edge-level information.

## Archivist Review

The paper presents a significant advancement in bridging neural network scalability with interpretable equation discovery. I approved the SIGN framework as a central architectural pattern for large-scale system modeling and included the two identified open questions as they represent non-trivial technical challenges for symbolic discovery frameworks in complex dynamical systems.

### Approved Concepts
- Sparse Identification Graph Neural Network: It provides a novel mechanism to decouple equation discovery from network size, bridging the gap between symbolic interpretability and neural scalability.

### Approved Open Questions
- Multi-channel state discovery: Generalizing the framework to multi-dimensional internal states is critical for accurately modeling complex, high-dimensional dynamical systems like biological cells or advanced neural circuits.
- Higher-order delayed interactions: Standard network frameworks often struggle with systems where dynamics depend on past states or non-adjacent nodes; addressing this is essential for predictive accuracy in complex, real-world phenomena.

## Links

- [Abstract](https://arxiv.org/abs/2604.00599)
- [PDF](https://arxiv.org/pdf/2604.00599)

