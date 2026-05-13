---
# CSL-compatible fields
title: "Multi-Timescale Conductance Spiking Networks: A Sparse, Gradient-Trainable Framework with Rich Firing Dynamics for Enhanced Temporal Processing"
author:
  - literal: "Alex Fulleda-Garcia"
  - literal: "Saray Soldado-Magraner"
  - literal: "Josep Maria Margarit-Taulé"
issued:
  date-parts:
    - [2026, 5, 12]
url: "https://arxiv.org/abs/2605.11835"

# Custom fields
paper_id: "2605.11835"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "multi-timescale-conductance-spiking-networks"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-13T05:24:32Z"
created_at: "2026-05-13T05:24:32Z"
---

# Multi-Timescale Conductance Spiking Networks: A Sparse, Gradient-Trainable Framework with Rich Firing Dynamics for Enhanced Temporal Processing

**Authors**: Alex Fulleda-Garcia, Saray Soldado-Magraner, Josep Maria Margarit-Taulé
**Date**: 2026-05-12
**Paper ID**: [arxiv:2605.11835](https://arxiv.org/abs/2605.11835)

## Summary

Multi-timescale conductance spiking networks address the traditional limitations of spiking neural networks in regression tasks by replacing simplified phenomenological models with tunable, conductance-based dynamics. By shaping current-voltage curves, this approach allows for diverse firing behaviors—such as tonic, phasic, and bursting—while remaining fully differentiable for direct backpropagation. Benchmarked on the Mackey-Glass time-series, the framework delivers higher accuracy than LIF and AdLIF baselines while simultaneously improving computational and communication sparsity.

## Key Contributions

- Introduces Multi-timescale Conductance Spiking Networks, a model that shapes I-V curves via tunable fast, slow, and ultra-slow conductances.
- Enables direct backpropagation through time without requiring surrogate gradient approximations for training spiking neurons.
- Achieves superior regression accuracy compared to standard LIF and AdLIF networks on Mackey-Glass time-series, while maintaining significantly higher activity sparsity.

## Key Concepts

- [[multi-timescale-conductance-spiking-networks]]: A gradient-trainable spiking neural network framework using tunable conductance dynamics to achieve rich firing regimes without surrogate gradients.

## Archivist Review

I approved the proposed spiking neural network framework as it represents a significant methodological shift in training spiking neurons for regression without surrogate gradients, which is highly relevant for future energy-aware and neuromorphic temporal processing. Other candidates were absent, and the paper relies on a standard chaotic time-series benchmark rather than a new or unique dataset.

### Approved Concepts
- Multi-timescale Conductance Spiking Networks: The core framework for overcoming the tradeoff between dynamical richness, gradient-trainability, and sparsity in SNNs for regression tasks.

## Links

- [Abstract](https://arxiv.org/abs/2605.11835)
- [PDF](https://arxiv.org/pdf/2605.11835)

