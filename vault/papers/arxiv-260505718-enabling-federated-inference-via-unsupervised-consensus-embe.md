---
# CSL-compatible fields
title: "Enabling Federated Inference via Unsupervised Consensus Embedding"
author:
  - literal: "Yui Hashimoto"
  - literal: "Takayuki Nishio"
  - literal: "Yuichi Kitagawa"
  - literal: "Takahito Tanimura"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2605.05718"

# Custom fields
paper_id: "2605.05718"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "federated-learning"
  - "privacy-preserving-ml"
architectures:
  []
datasets:
  []
concept_slugs:
  - "consensus-embedding-based-federated-inference-ce-fi"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-10T05:20:50Z"
created_at: "2026-05-10T05:20:50Z"
---

# Enabling Federated Inference via Unsupervised Consensus Embedding

**Authors**: Yui Hashimoto, Takayuki Nishio, Yuichi Kitagawa, Takahito Tanimura
**Date**: 2026-05-07
**Paper ID**: [arxiv:2605.05718](https://arxiv.org/abs/2605.05718)

## Summary

The paper introduces Consensus Embedding-based Federated Inference (CE-FI), a framework designed for cooperative inference among independent, pretrained machine learning models while ensuring data and parameter privacy. CE-FI maps heterogeneous intermediate representations into a shared embedding space through a Consensus Embedding (CE) layer, which is trained alongside a Cooperative Output (CO) layer using only unlabeled data. By avoiding the need for shared encoders or raw data, this approach facilitates collaboration across disparate organizational models. Experimental results on CIFAR benchmarks and preliminary tests on text and time-series data demonstrate that CE-FI effectively improves prediction accuracy compared to solo inference models.

## Key Contributions

- Introduces CE-FI, a federated inference framework enabling model cooperation without sharing parameters, inputs, or encoders.
- Proposes a Consensus Embedding (CE) layer and Cooperative Output (CO) layer to align heterogeneous representations using only unlabeled data.
- Demonstrates superior performance over solo inference on CIFAR-10 and CIFAR-100 image classification benchmarks under non-IID conditions.

## Open Questions & Future Work

- [[improving-representation-alignment-federated-inference]]

## Key Concepts

- [[consensus-embedding-based-federated-inference-ce-fi]]: A federated inference framework that aligns heterogeneous model representations into a shared space using unlabeled data for cooperative prediction.

## Archivist Review

I approved the CE-FI concept as it represents a robust architectural approach to privacy-preserving federated inference. I also approved the open question regarding representation alignment, as it identifies a clear, fundamental bottleneck in cross-model cooperation that warrants further investigation. I rejected the datasets as they are routine machine learning benchmarks not specific to the unique domain of federated inference.

### Approved Concepts
- Consensus Embedding-based Federated Inference (CE-FI): It introduces a novel framework for cooperative inference that maintains data and parameter privacy without requiring a common encoder.

### Approved Open Questions
- Improving Representation Alignment and Ensemble Methods: Representation alignment was identified as the primary bottleneck in the system's performance, especially in scratch-trained settings. Addressing this is critical for the framework to achieve optimal performance across diverse distributed environments.

## Links

- [Abstract](https://arxiv.org/abs/2605.05718)
- [PDF](https://arxiv.org/pdf/2605.05718)

