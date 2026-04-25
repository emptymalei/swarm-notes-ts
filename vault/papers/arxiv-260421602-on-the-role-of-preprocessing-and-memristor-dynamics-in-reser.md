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
  - "parallel-delayed-feedback-network-pdfn"
datasets:
  []
concept_slugs:
  - "parallel-delayed-feedback-network-pdfn"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-25T04:54:26Z"
created_at: "2026-04-25T04:54:26Z"
---

# On the Role of Preprocessing and Memristor Dynamics in Reservoir Computing for Image Classification

**Authors**: Rishona Daniels, Duna Wattad, Ronny Ronen, David Saad, Shahar Kvatinsky
**Date**: 2026-04-23
**Paper ID**: [arxiv:2604.21602](https://arxiv.org/abs/2604.21602)

## Summary

This paper investigates the role of volatile memristor dynamics in a parallel delayed feedback network (PDFN) architecture for reservoir computing. By characterizing device-level requirements such as decay rates and quantization, the authors establish how physical hardware constraints influence performance in image classification tasks. The proposed framework achieves competitive classification accuracy on the MNIST benchmark and exhibits significant robustness to device variability. These findings underscore the suitability of volatile memristors for energy-efficient, neuromorphic spatio-temporal processing.

## Key Contributions

- Analyzed the impact of volatile memristor dynamics (decay rate, quantization, variability) on the performance of the PDFN architecture.
- Achieved 95.89% classification accuracy on the MNIST dataset, demonstrating competitiveness with existing memristor-based RC implementations.
- Demonstrated high robustness of the proposed RC approach, maintaining 94.2% accuracy under 20% device variability.

## Open Questions & Future Work

- [[robust-co-design-memristive-rc]]

## Key Concepts

- [[parallel-delayed-feedback-network-pdfn]]: A recurrent neural network architecture designed to leverage memristor dynamics for efficient reservoir computing.

## Archivist Review

I approved the PDFN concept as it is a specific, reusable architectural model for hardware-based reservoir computing. I also approved the co-design open question because it captures the critical bottleneck in scaling memristive hardware—moving from isolated performance measurements to systematic, robust system design. MNIST was rejected as a routine dataset unsuitable for a permanent vault entry under these strict guidelines.

### Approved Concepts
- Parallel Delayed Feedback Network (PDFN): The paper provides a comprehensive analysis of the PDFN architecture in the context of memristive device constraints.

### Approved Open Questions
- Robust Co-design of Memristive RC: This is critical because memristor-based hardware is inherently prone to variability; without clear co-design methodologies, scaling these systems to more complex, real-world tasks will be hindered by the lack of reliability.

## Links

- [Abstract](https://arxiv.org/abs/2604.21602)
- [PDF](https://arxiv.org/pdf/2604.21602)

