---
# CSL-compatible fields
title: "On the Role of Preprocessing and Memristor Dynamics in Reservoir Computing for Image Classification"
author:
  - literal: "Rishona Daniels"
  - literal: "Duna Wattad"
  - literal: "Ronny Ronen"
  - literal: "David Saad"
  - literal: "Shahar Kvatinsky"
issued:
  date-parts:
    - [2026, 4, 23]
url: "https://arxiv.org/abs/2604.21602"

# Custom fields
paper_id: "2604.21602"
paper_source: "arxiv"
domain: "computer-vision"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "parallel-delayed-feedback-network-pdfn"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-24T05:07:42Z"
created_at: "2026-04-24T05:07:42Z"
---

# On the Role of Preprocessing and Memristor Dynamics in Reservoir Computing for Image Classification

**Authors**: Rishona Daniels, Duna Wattad, Ronny Ronen, David Saad, Shahar Kvatinsky
**Date**: 2026-04-23
**Paper ID**: [arxiv:2604.21602](https://arxiv.org/abs/2604.21602)

## Summary

This paper investigates the role of volatile memristor device dynamics in a Parallel Delayed Feedback Network (PDFN) for reservoir computing, specifically targeting image classification. The authors provide a comprehensive analysis of how device-level factors like decay rates, quantization, and noise variability influence reservoir performance and spatio-temporal processing capabilities. By incorporating preprocessing strategies to optimize data representation, the model achieves a 95.89% accuracy on MNIST. The work highlights the potential of using volatile memristors for energy-efficient, robust neuromorphic computing hardware.

## Key Contributions

- Identifies key volatile memristor device characteristics—decay rate, quantization, and variability—that dictate reservoir computing performance in spatio-temporal tasks.
- Demonstrates that the proposed PDFN architecture achieves 95.89% accuracy on the MNIST benchmark, competitive with state-of-the-art memristor-based reservoir systems.
- Establishes the robustness of the approach, maintaining 94.2% classification accuracy even under 20% device variability.

## Open Questions & Future Work

- [[robustness-in-stochastic-memristive-reservoirs]]

## Key Concepts

- [[parallel-delayed-feedback-network-pdfn]]: A reservoir computing architecture that leverages the intrinsic temporal dynamics of volatile memristors in parallel delayed feedback loops for efficient signal processing.

## Archivist Review

The paper was approved for its specific contributions to hardware-aware reservoir computing using volatile memristors. The PDFN concept is a distinct architectural approach for delay-based computing, and the open question regarding robustness to stochastic device variability addresses a critical barrier in physical neuromorphic systems. Routine datasets like MNIST were rejected per policy.

### Approved Concepts
- Parallel Delayed Feedback Network (PDFN): Provides the structural basis for implementing reservoir computing using volatile memristive devices and delay-based feedback.

### Approved Open Questions
- Robustness in stochastic memristive reservoirs: This is a fundamental challenge for the practical deployment of non-ideal neuromorphic hardware where device stochasticity is inherent. Understanding how to maintain computational reliability is essential for scaling reservoir computing to edge applications.

## Links

- [Abstract](https://arxiv.org/abs/2604.21602)
- [PDF](https://arxiv.org/pdf/2604.21602)

