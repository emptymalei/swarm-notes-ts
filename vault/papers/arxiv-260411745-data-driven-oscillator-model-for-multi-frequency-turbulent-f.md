---
# CSL-compatible fields
title: "Data-driven oscillator model for multi-frequency turbulent flows"
author:
  - literal: "Youngjae Kim"
  - literal: "Koichiro Yawata"
  - literal: "Hiroya Nakao"
  - literal: "Kunihiko Taira"
issued:
  date-parts:
    - [2026, 4, 13]
url: "https://arxiv.org/abs/2604.11745"

# Custom fields
paper_id: "2604.11745"
paper_source: "arxiv"
domain: "fluid-dynamics"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "data-driven-oscillator-modeling"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-04-14T05:02:06Z"
created_at: "2026-04-14T05:02:06Z"
---

# Data-driven oscillator model for multi-frequency turbulent flows

**Authors**: Youngjae Kim, Koichiro Yawata, Hiroya Nakao, Kunihiko Taira
**Date**: 2026-04-13
**Paper ID**: [arxiv:2604.11745](https://arxiv.org/abs/2604.11745)

## Summary

This paper proposes a data-driven framework for reduced-order modeling of multi-frequency turbulent flows by representing complex dynamics through a set of extracted oscillators. The method employs specially designed autoencoders to identify representative oscillators from flow field data and uses neural networks to learn their governing dynamics. The framework is validated on three-dimensional supersonic turbulent cavity flow, demonstrating its capability to accurately forecast long-term multi-frequency oscillatory behavior and capture dominant flow features.

## Key Contributions

- Introduces a data-driven framework that utilizes autoencoders to extract representative oscillators from high-dimensional, multi-frequency turbulent flow fields.
- Develops a neural network-based oscillator dynamics model capable of long-term forecasting of multi-frequency oscillatory behavior in turbulent flows.
- Demonstrates the model's effectiveness through successful application to three-dimensional supersonic turbulent flow over a cavity, recovering large-scale flow features.

## Open Questions & Future Work

- [[phase-reduction-for-turbulent-flows]]

## Key Concepts

- [[data-driven-oscillator-modeling]]: A reduced-order modeling approach that extracts representative oscillators from complex dynamical systems using autoencoders and models their evolution via neural networks.

## Archivist Review

The paper introduces a novel data-driven approach to reduced-order modeling in fluid dynamics. I have approved 'data-driven-oscillator-modeling' as it captures the specific architectural pattern of using autoencoders to isolate oscillatory dynamics for subsequent learning. The open question regarding phase reduction in multi-frequency turbulent flows is a significant theoretical challenge that warrants tracking as a research bottleneck. No datasets were approved as none were explicitly provided as novel contributions or specific benchmarks.

### Approved Concepts
- Data-driven Oscillator Modeling: This represents a shift from traditional analytical phase reduction to a learnable framework capable of capturing multi-frequency, non-linear dynamics from data.

### Approved Open Questions
- Phase-reduction for turbulent flows: This is a fundamental bottleneck in applying non-linear dynamical systems theory to complex fluid flows and other multi-scale chaotic physical systems.

## Links

- [Abstract](https://arxiv.org/abs/2604.11745)
- [PDF](https://arxiv.org/pdf/2604.11745)

