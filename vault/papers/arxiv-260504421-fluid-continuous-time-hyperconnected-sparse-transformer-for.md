---
# CSL-compatible fields
title: "FLUID: Continuous-Time Hyperconnected Sparse Transformer for Sink-Free Learning"
author:
  - literal: "Waleed Razzaq"
  - literal: "Yun-Bo Zhao"
issued:
  date-parts:
    - [2026, 5, 6]
url: "https://arxiv.org/abs/2605.04421"

# Custom fields
paper_id: "2605.04421"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "liquid-attention-network-lan"
  - "liquid-hyper-connections"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-07T05:15:58Z"
created_at: "2026-05-07T05:15:58Z"
---

# FLUID: Continuous-Time Hyperconnected Sparse Transformer for Sink-Free Learning

**Authors**: Waleed Razzaq, Yun-Bo Zhao
**Date**: 2026-05-06
**Paper ID**: [arxiv:2605.04421](https://arxiv.org/abs/2605.04421)

## Summary

FLUID is a continuous-time transformer designed to overcome the discrete nature of standard scaled-dot-product attention by reformulating attention as a continuous dynamical system. The core mechanism, Liquid Attention Network (LAN), treats attention logits as solutions to linear ODEs modulated by nonlinear recurrent gates, while an explicit attention-sink gate addresses issues with uninformative nodes. Furthermore, FLUID utilizes Liquid Hyper-Connections instead of static residuals to adaptively regulate information flow across network layers, showing superior performance and robustness in irregular time-series and control tasks.

## Key Contributions

- Introduced FLUID, a continuous-time transformer architecture replacing SDPA with Liquid Attention Network (LAN) to model attention as a solution to linear ODEs.
- Developed Liquid Hyper-Connections to replace static residual connections, enabling adaptive, input-dependent inter-layer information regulation.
- Demonstrated empirical improvements of up to 47% across diverse tasks including irregular time-series, long-range modeling, autonomous vehicle control, and physical dynamics learning.

## Open Questions & Future Work

- [[stochastic-lan-uncertainty]]
- [[manifold-constrained-hyper-connections]]

## Key Concepts

- [[liquid-attention-network-lan]]: An attention mechanism that reformulates attention logits as the solution to a linear ODE modulated by input-dependent nonlinear recurrent gates.
- [[liquid-hyper-connections]]: A replacement for standard residual connections that uses input-dependent gating to adaptively regulate information flow between layers.

## Archivist Review

The paper presents a significant departure from standard discrete attention mechanisms by framing attention as a continuous dynamical system. I have approved the two primary mechanisms (LAN and Liquid Hyper-Connections) as they offer modular, reusable architectural components for future research in continuous-time transformers and adaptive deep learning. The open questions were approved for identifying key stability and uncertainty challenges inherent in this novel paradigm.

### Approved Concepts
- Liquid Attention Network (LAN): It is the core innovation, replacing discrete SDPA with a continuous dynamical system for attention computation.
- Liquid Hyper-Connections: It provides a novel approach to regulating information flow in deep architectures through adaptive, input-dependent connections.

### Approved Open Questions
- Stochastic Liquid Attention Networks: Addressing uncertainty in attention is critical for more robust and reliable sequence modeling, especially in high-stakes control environments.
- Manifold-Constrained Hyper-Connections: This addresses the fundamental stability/performance bottleneck in deep residual learning by imposing structural constraints on learnable connections.

## Links

- [Abstract](https://arxiv.org/abs/2605.04421)
- [PDF](https://arxiv.org/pdf/2605.04421)

