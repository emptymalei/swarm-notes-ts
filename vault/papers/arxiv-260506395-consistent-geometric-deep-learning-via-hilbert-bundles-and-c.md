---
# CSL-compatible fields
title: "Consistent Geometric Deep Learning via Hilbert Bundles and Cellular Sheaves"
author:
  - literal: "Kartik Tandon"
  - literal: "Julian Gould"
  - literal: "Tanishq Bhatia"
  - literal: "Francesca Dominici"
  - literal: "Alejandro Ribeiro"
  - literal: "Claudio Battiloro"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2605.06395"

# Custom fields
paper_id: "2605.06395"
paper_source: "arxiv"
domain: "computer-vision"
tags:
  - "geometric-deep-learning"
  - "manifold-learning"
  - "neural-networks"
  - "representation-learning"
architectures:
  []
datasets:
  []
concept_slugs:
  - "hilbnets"
  - "hilbert-cellular-sheaf"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-10T05:18:31Z"
created_at: "2026-05-10T05:18:31Z"
---

# Consistent Geometric Deep Learning via Hilbert Bundles and Cellular Sheaves

**Authors**: Kartik Tandon, Julian Gould, Tanishq Bhatia, Francesca Dominici, Alejandro Ribeiro, Claudio Battiloro
**Date**: 2026-05-07
**Paper ID**: [arxiv:2605.06395](https://arxiv.org/abs/2605.06395)

## Summary

The paper presents a unified geometric learning framework for infinite-dimensional signals (e.g., time series or operators) defined on manifolds. By utilizing connection Laplacians on Hilbert bundles, the authors define a convolutional operator that is implemented through the construction of a Hilbert Cellular Sheaf. The framework provides theoretical guarantees for convergence in the discretization process and ensures model transferability across varying sampling densities of the underlying manifold.

## Key Contributions

- Introduces HilbNets, a convolutional learning framework for infinite-dimensional signals supported on a manifold using connection Laplacians.
- Proves the convergence of the sheaf Laplacian to the underlying connection Laplacian as sampling density increases, generalizing the Belkin & Niyogi result.
- Demonstrates that discretized HilbNets converge to continuous architectures and maintain transferability across different manifold samplings.

## Open Questions & Future Work

- [[scalability-of-sheaf-laplacian-computation]]

## Key Concepts

- [[hilbnets]]: A convolutional neural network architecture for infinite-dimensional signals defined over manifolds using connection Laplacians.
- [[hilbert-cellular-sheaf]]: A discrete data structure extending cellular sheaves to accommodate Hilbert spaces, serving as an approximation for manifold-based Hilbert bundles.

## Archivist Review

The paper introduces a mathematically rigorous framework for geometric deep learning on infinite-dimensional signals. The selected concepts (HilbNets, Hilbert Cellular Sheaf) are central to the contribution and provide a new paradigm for handling signals on manifolds that likely exceeds the scope of this single work. The approved open question addresses the primary computational bottleneck—scaling the operator complexity—which is crucial for the framework's adoption.

### Approved Concepts
- HilbNets: It is the core convolutional learning framework introduced by the paper for infinite-dimensional signals on manifolds.
- Hilbert Cellular Sheaf: It bridges the gap between continuous Hilbert bundles and discrete, implementable graph-based learning.

### Approved Open Questions
- Scalability of Sheaf Laplacian Computation: The current computational complexity (quadratic in the product of spatial and fiber dimensions) is a primary bottleneck for scaling these models to high-resolution data or complex signals.

## Links

- [Abstract](https://arxiv.org/abs/2605.06395)
- [PDF](https://arxiv.org/pdf/2605.06395)

