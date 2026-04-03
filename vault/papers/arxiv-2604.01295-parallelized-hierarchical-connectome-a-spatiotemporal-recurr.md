---
# CSL-compatible fields
title: "Parallelized Hierarchical Connectome: A Spatiotemporal Recurrent Framework for Spiking State-Space Models"
author:
  - literal: "Po-Han Chiang"
issued:
  date-parts:
    - [2026, 4, 1]
url: "https://arxiv.org/abs/2604.01295"

# Custom fields
paper_id: "2604.01295"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "parallelized-hierarchical-connectome"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-03T05:25:04Z"
created_at: "2026-04-03T05:25:04Z"
---

# Parallelized Hierarchical Connectome: A Spatiotemporal Recurrent Framework for Spiking State-Space Models

**Authors**: Po-Han Chiang
**Date**: 2026-04-01
**Paper ID**: [arxiv:2604.01295](https://arxiv.org/abs/2604.01295)

## Summary

The Parallelized Hierarchical Connectome (PHC) framework extends diagonal State-Space Models (SSMs) to incorporate spatiotemporal recurrent dynamics by mapping model cores to shared neuron and synapse layers governed by connectome topology. PHC utilizes a Multi-Transmission Loop to facilitate intra-slice spatial recurrence while preserving parallelizable sequence processing, enabling the integration of neuro-physical priors like synaptic plasticity and Dale's Law. Evaluation on the UEA multivariate time-series archive demonstrates that the resulting PHCSSM architecture achieves state-of-the-art performance with reduced parameter complexity compared to standard stacked SSMs.

## Key Contributions

- Introduces the Parallelized Hierarchical Connectome (PHC) framework, which enables spatiotemporal recurrence in diagonal SSMs while maintaining O(log T) parallelism.
- Implements PHCSSM, the first model to integrate five neuro-physical priors (including Dale's Law and STDP) into a fully parallelizable training pipeline.
- Demonstrates that PHCSSM achieves performance competitive with state-of-the-art SSMs on UEA benchmarks while significantly reducing parameter complexity to Theta(D^2).

## Open Questions & Future Work

- [[parallel-sequential-divergence-spiking-ssms]]

## Key Concepts

- [[parallelized-hierarchical-connectome]]: A framework for upgrading temporal-only SSMs into spatiotemporal recurrent networks using hierarchical connectome topologies and multi-transmission loops.

## Archivist Review

I have approved the PHC framework as a foundational architectural concept that enables spatial recurrence within the SSM paradigm, and the open question regarding the divergence between parallel and sequential execution modes, as this addresses a critical structural limitation of the proposed approach. I have rejected the UEA archive as a dataset note because it is an aggregate collection rather than a single, specific benchmark entity.

### Approved Concepts
- Parallelized Hierarchical Connectome (PHC): It introduces a novel paradigm for injecting spatial recurrence into diagonal SSMs while maintaining parallel efficiency, which is a significant structural shift in the architecture of sequence models.

### Approved Open Questions
- Parallel vs Sequential Execution Divergence: Bridging the gap between parallel training and sequential inference is essential for the reliability of hardware-efficient sequence models that rely on parallelization for training performance.

### Rejected Candidates
- [dataset] UEA multivariate time-series archive (`uea-multivariate-time-series-archive`) - generic: The UEA archive is a broad collection of datasets rather than a single specific benchmark dataset.

## Links

- [Abstract](https://arxiv.org/abs/2604.01295)
- [PDF](https://arxiv.org/pdf/2604.01295)

