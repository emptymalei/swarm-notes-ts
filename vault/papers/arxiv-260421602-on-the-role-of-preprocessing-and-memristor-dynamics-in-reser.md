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
domain: "nlp"
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
processed_at: "2026-04-26T05:08:57Z"
created_at: "2026-04-26T05:08:57Z"
---

# On the Role of Preprocessing and Memristor Dynamics in Reservoir Computing for Image Classification

**Authors**: Rishona Daniels, Duna Wattad, Ronny Ronen, David Saad, Shahar Kvatinsky
**Date**: 2026-04-23
**Paper ID**: [arxiv:2604.21602](https://arxiv.org/abs/2604.21602)

## Summary

This paper investigates the viability of using volatile memristors as the foundation for reservoir computing (RC) architectures in neuromorphic systems. By analyzing a parallel delayed feedback network (PDFN), the authors identify how specific device-level dynamics like decay rate and variability influence system-wide performance in image recognition. The proposed framework achieves competitive classification accuracy on the MNIST dataset and exhibits significant resilience to hardware-induced variability. These findings provide critical design guidelines for developing compact and energy-efficient neuromorphic computing hardware.

## Key Contributions

- Analyzes the impact of volatile memristor device-level characteristics—including decay rate, quantization, and variability—on reservoir computing performance.
- Achieves 95.89% classification accuracy on MNIST using a parallel delayed feedback network (PDFN) architecture.
- Demonstrates high robustness for the proposed memristive reservoir, maintaining 94.2% accuracy even under 20% device variability.

## Open Questions & Future Work

- [[memristor-parameter-scaling-laws]]

## Key Concepts

- [[parallel-delayed-feedback-network-pdfn]]: A recurrent reservoir computing architecture optimized for memristive hardware that uses parallel delayed feedback to process information.

## Archivist Review

The review process focused on identifying the specific architectural innovation (PDFN) and the broader research challenge regarding memristor parameterization. The PDFN was approved as it represents a specific class of recurrent architecture for physical reservoir computing, while the open question was reformulated to emphasize the lack of mapping strategies rather than inventing scaling laws. MNIST was rejected as a routine benchmark.

### Approved Concepts
- Parallel Delayed Feedback Network (PDFN): The paper focuses on the specific analysis and operational explanation of this architecture for memristor-based reservoir computing.

### Approved Open Questions
- Universal Memristor Parameter Scaling: Crucial for enabling the transition from empirical, task-specific memristor configurations to scalable, predictable neuromorphic system designs.

### Rejected Candidates
- [dataset] MNIST (`mnist`) - low_impact: MNIST is a routine, ubiquitous benchmark that does not require a standalone vault entry.

## Links

- [Abstract](https://arxiv.org/abs/2604.21602)
- [PDF](https://arxiv.org/pdf/2604.21602)

