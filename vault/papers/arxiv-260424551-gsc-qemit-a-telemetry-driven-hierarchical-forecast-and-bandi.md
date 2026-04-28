---
# CSL-compatible fields
title: "GSC-QEMit: A Telemetry-Driven Hierarchical Forecast-and-Bandit Framework for Adaptive Quantum Error Mitigation"
author:
  - literal: "Steven Szachara"
  - literal: "Sheeraja Rajakrishnan"
  - literal: "Dylan Jay Van Allen"
  - literal: "Jason Pollack"
  - literal: "Travis Desell"
  - literal: "Daniel Krutz"
issued:
  date-parts:
    - [2026, 4, 27]
url: "https://arxiv.org/abs/2604.24551"

# Custom fields
paper_id: "2604.24551"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "gsc-qemit"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-04-28T05:13:59Z"
created_at: "2026-04-28T05:13:59Z"
---

# GSC-QEMit: A Telemetry-Driven Hierarchical Forecast-and-Bandit Framework for Adaptive Quantum Error Mitigation

**Authors**: Steven Szachara, Sheeraja Rajakrishnan, Dylan Jay Van Allen, Jason Pollack, Travis Desell, Daniel Krutz
**Date**: 2026-04-27
**Paper ID**: [arxiv:2604.24551](https://arxiv.org/abs/2604.24551)

## Summary

GSC-QEMit is an adaptive quantum error mitigation framework designed to manage noise in near-term devices by balancing mitigation strength against computational overhead. It employs a Growing Hierarchical Self-Organizing Map (GHSOM) for context awareness, a Gaussian-process model for fidelity forecasting, and a cost-aware Contextual Multi-Armed Bandit (CMAB) to select optimal mitigation strategies. Evaluations across multiple circuit types demonstrate significant logical fidelity improvements and reduced overhead compared to baseline static methods.

## Key Contributions

- Introduces GSC-QEMit, a framework integrating GHSOM for context clustering, Gaussian-process forecasting, and cost-aware CMAB for quantum error mitigation.
- Demonstrates a 9.0% improvement in average logical fidelity over unmitigated execution on benchmark circuits under nonstationary noise.
- Enables optimized fidelity-cost trade-offs by dynamically reserving high-overhead mitigation actions for detected noise spikes.

## Open Questions & Future Work

- [[standardizing-adaptive-qem-interfaces]]

## Key Concepts

- [[gsc-qemit]]: A hierarchical framework for adaptive quantum error mitigation using context clustering, fidelity forecasting, and cost-aware bandit selection.

## Archivist Review

The GSC-QEMit framework is approved as it provides a clear, reusable modular architecture (telemetry-driven context clustering, forecasting, and bandit-based action selection) for resource-constrained stochastic control. The open question regarding standardizing adaptive QEM interfaces is approved because it addresses a fundamental bottleneck in the portability and scalability of error mitigation controllers across diverse hardware. No datasets were approved as the mentioned benchmarks are standard synthetic workloads.

### Approved Concepts
- GSC-QEMit: Central framework combining telemetry clustering, GP forecasting, and CMAB for adaptive quantum error mitigation.

### Approved Open Questions
- Standardizing Adaptive QEM Interfaces: Standardizing the interface between high-level mitigation policy controllers and low-level hardware-specific error mitigation primitives is critical for the scalability and portability of adaptive quantum error management systems.

## Links

- [Abstract](https://arxiv.org/abs/2604.24551)
- [PDF](https://arxiv.org/pdf/2604.24551)

