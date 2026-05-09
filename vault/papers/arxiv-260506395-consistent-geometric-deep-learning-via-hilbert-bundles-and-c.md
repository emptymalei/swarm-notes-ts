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
domain: "nlp"
tags:
  - "geometric-deep-learning"
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
processed_at: "2026-05-09T05:10:21Z"
created_at: "2026-05-09T05:10:21Z"
---

# Consistent Geometric Deep Learning via Hilbert Bundles and Cellular Sheaves

**Authors**: Kartik Tandon, Julian Gould, Tanishq Bhatia, Francesca Dominici, Alejandro Ribeiro, Claudio Battiloro
**Date**: 2026-05-07
**Paper ID**: [arxiv:2605.06395](https://arxiv.org/abs/2605.06395)

## Summary

This paper introduces HilbNets, a novel geometric deep learning framework designed for signals residing in infinite-dimensional Hilbert spaces over irregular manifold domains. The authors leverage connection Laplacians and formalize a Hilbert Cellular Sheaf to enable the discretization and implementation of these architectures. By proving the convergence of sheaf Laplacians to continuous connection Laplacians and establishing the transferability of discretized networks, the work provides a rigorous theoretical foundation for learning on complex, bundle-valued data.

## Key Contributions

- Introduces HilbNets, a convolutional learning framework for infinite-dimensional signals supported on manifolds using connection Laplacians.
- Establishes a Hilbert Cellular Sheaf framework, proving its sheaf Laplacian converges to the underlying manifold connection Laplacian as sampling density increases.
- Provides theoretical consistency proofs demonstrating that discretized HilbNets converge to continuous architectures and remain transferable across different manifold samplings.

## Open Questions & Future Work

- [[convergence-hilbert-bundle-laplacian]]

## Key Concepts

- [[hilbnets]]: A convolutional neural network framework designed for infinite-dimensional signals on manifolds, utilizing the connection Laplacian of a Hilbert bundle.
- [[hilbert-cellular-sheaf]]: A generalized graph structure that maps continuous manifold Hilbert bundles to discrete, computationally tractable representations for learning.

## Archivist Review

I have approved the core architectural framework (HilbNets) and its theoretical foundation (Hilbert Cellular Sheaf) as they represent a significant advancement in geometric learning for infinite-dimensional signals. The open question regarding convergence is critical for scaling these theoretical insights to more complex, real-world non-compact domains. No datasets were approved as none were identified as central, canonical, or reusable across the field.

### Approved Concepts
- HilbNets: Core architectural contribution for learning on infinite-dimensional signals supported on a manifold using connection Laplacians.
- Hilbert Cellular Sheaf: A novel theoretical bridge between continuous Hilbert bundles and discrete, implementable graph structures.

### Approved Open Questions
- Convergence for Infinite-Dimensional Fibers: This question is fundamental to unifying geometric deep learning theory and establishing consistent convergence for infinite-dimensional data modalities on non-Euclidean domains.

## Links

- [Abstract](https://arxiv.org/abs/2605.06395)
- [PDF](https://arxiv.org/pdf/2605.06395)

