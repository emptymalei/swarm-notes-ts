---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Online training of Echo State Networks to predict chaotic dynamical systems"
description: "This paper investigates the performance of Echo State Networks (ESNs) utilizing online training for predicting chaotic dynamical systems, including the Lorenz, Rossler, and FitzHugh-Nagumo models. The authors specifically analyze how reservoir topology—specifically Erdos-Renyi and Watts-Strogatz networks—affects learning efficiency and prediction accuracy. The key finding is that ESNs achieve optimal performance when the reservoir's link density is near the critical point of mean-field bond percolation, suggesting a structural guideline for designing sparse, efficient reservoirs for real-time forecasting in non-stationary environments."
resource: "https://arxiv.org/abs/2610.20147"
tags:
  - "echo-state-networks"
  - "reservoir-computing"
  - "online-learning"
  - "chaotic-systems"
  - "dynamical-systems"
  - "graph-theory"
  - "time-series-forecasting"
  - "non-stationary-signals"
timestamp: "2026-10-18T00:35:15Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Astero Provata"
  - literal: "Markos Syroukis"
  - literal: "Johanne Hizanidis"
issued:
  date-parts:
    - [2026, 10, 14]

# Domain-specific custom fields
paper_id: "2610.20147"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "reservoir-percolation-threshold-optimization"
    description: "The design principle that Echo State Network performance is maximized when the reservoir's connectivity density resides near the critical bond percolation threshold of its graph topology."
datasets:
  []
open_questions:
  - name: "universality-of-reservoir-percolation-thresholds"
    description: "Does the relationship between the bond percolation threshold and prediction performance hold for more complex, heterogeneous, or multi-layered reservoir architectures, or is it specific to simple Erdos-Renyi and Watts-Strogatz topologies?"
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T00:35:15Z"
created_at: "2026-10-18T00:35:15Z"
---

# Online training of Echo State Networks to predict chaotic dynamical systems

**Authors**: Astero Provata, Markos Syroukis, Johanne Hizanidis
**Date**: 2026-10-14
**Paper ID**: [arxiv:2610.20147](https://arxiv.org/abs/2610.20147)

## Summary

This paper investigates the performance of Echo State Networks (ESNs) utilizing online training for predicting chaotic dynamical systems, including the Lorenz, Rossler, and FitzHugh-Nagumo models. The authors specifically analyze how reservoir topology—specifically Erdos-Renyi and Watts-Strogatz networks—affects learning efficiency and prediction accuracy. The key finding is that ESNs achieve optimal performance when the reservoir's link density is near the critical point of mean-field bond percolation, suggesting a structural guideline for designing sparse, efficient reservoirs for real-time forecasting in non-stationary environments.

## Key Contributions

- Demonstrates that online training of Echo State Networks (ESNs) effectively tracks the dynamics of chaotic systems like the Lorenz and Rossler models.
- Identifies that reservoir performance is maximized at low link densities, specifically near the critical point of mean-field bond percolation for Erdos-Renyi topologies.
- Establishes that Watts-Strogatz small-world reservoirs exhibit optimal performance at densities compatible with mean-field percolation when accounting for their nonlocal ring structure.
- Provides a systematic comparison of reservoir topologies (random vs. small-world) for real-time forecasting in non-stationary dynamical environments.

## Limitations

The study focuses on synthetic chaotic systems and limit cycles; the generalizability to high-dimensional real-world noisy data or multi-scale systems remains to be verified.

## Open Questions & Future Work

- [[universality-of-reservoir-percolation-thresholds]]

## Key Concepts

- [[reservoir-percolation-threshold-optimization]]: The design principle that Echo State Network performance is maximized when the reservoir's connectivity density resides near the critical bond percolation threshold of its graph topology.

## Archivist Review

The primary contribution of the paper is the identification of bond percolation thresholds as a structural guide for reservoir design. I have approved a concept for this specific topological optimization and an open question regarding its universality across different architectures. I rejected the online training candidate as it is a routine implementation detail (RLS-ESN) rather than a novel mechanism. Standard synthetic benchmarks (Lorenz, Rossler) were rejected as datasets.

### Approved Concepts
- Reservoir Percolation Threshold Optimization: Provides a theoretical grounding (bond percolation) for choosing the sparsity of the reservoir connectivity matrix, which is usually treated as a heuristic hyperparameter.

### Approved Open Questions
- Universality of Reservoir Percolation Thresholds: Determining if the 'edge of percolation' is a universal design principle would significantly simplify architecture search for dynamical system forecasting.

### Rejected Candidates
- [concept] Online Training for Echo State Networks (`online-esn-training`) - generic: Online training (e.g., via RLS or LMS) is a standard adaptation in signal processing and does not represent a novel conceptual breakthrough unique to this paper.
- [dataset] Lorenz Model (`lorenz-model`) - not_novel: The Lorenz model is a standard mathematical system for benchmarking chaotic dynamics rather than a novel dataset contribution.
- [concept] Echo State Networks (`echo-state-networks`) - duplicate_existing: Echo State Networks are a well-established architecture and do not require a new vault entry for this paper's specific use case.

## Links

- [Abstract](https://arxiv.org/abs/2610.20147)
- [PDF](https://arxiv.org/pdf/2610.20147)

