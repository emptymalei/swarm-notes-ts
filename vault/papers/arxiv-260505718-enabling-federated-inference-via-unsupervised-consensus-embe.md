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
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "consensus-embedding-based-federated-inference-ce-fi"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-09T05:12:43Z"
created_at: "2026-05-09T05:12:43Z"
---

# Enabling Federated Inference via Unsupervised Consensus Embedding

**Authors**: Yui Hashimoto, Takayuki Nishio, Yuichi Kitagawa, Takahito Tanimura
**Date**: 2026-05-07
**Paper ID**: [arxiv:2605.05718](https://arxiv.org/abs/2605.05718)

## Summary

This paper introduces Consensus Embedding-based Federated Inference (CE-FI), a novel approach for collaborative inference among heterogeneous pretrained models without requiring data or parameter sharing. CE-FI maps diverse intermediate representations into a unified space using a Consensus Embedding (CE) layer and a Cooperative Output (CO) layer trained solely on unlabeled data. The method is validated on image classification tasks under non-IID conditions, demonstrating effectiveness competitive with conventional, less-private cooperative frameworks. The authors also highlight that while applicable to text and time-series, performance is heavily contingent upon successful representation alignment.

## Key Contributions

- Proposes CE-FI, a framework for collaborative inference among heterogeneous pretrained models that avoids parameter/data sharing and requires no common encoder.
- Introduces a Consensus Embedding (CE) layer and a Cooperative Output (CO) layer that are trained exclusively on unlabeled data to align intermediate representations.
- Demonstrates consistent performance improvements over solo inference on CIFAR-10/100 under non-IID conditions, with comparable performance to methods requiring stronger privacy-compromising assumptions.

## Open Questions & Future Work

- [[improving-federated-inference-representation-alignment]]

## Key Concepts

- [[consensus-embedding-based-federated-inference-ce-fi]]: A federated inference framework that facilitates cooperation between heterogeneous pretrained models by mapping their intermediate representations to a shared embedding space using unlabeled data.

## Archivist Review

I have approved the core framework (CE-FI) and the primary unresolved research question regarding representation alignment in federated inference. These are significant contributions to the field of privacy-preserving model cooperation. I have rejected the datasets as they are standard computer vision benchmarks and do not align with the focus of this time-series and forecasting-oriented vault.

### Approved Concepts
- Consensus Embedding-based Federated Inference (CE-FI): It is the core proposed framework that enables privacy-preserving collaborative inference among heterogeneous, independently trained models without sharing parameters or data.

### Approved Open Questions
- Improving Federated Inference Alignment: This is identified as the primary performance bottleneck. Improving these components is essential for the practical viability of the proposed framework, especially for modality-specific tasks where current generic ensemble strategies show limitations.

### Rejected Candidates
- [dataset] CIFAR-10 (`cifar-10`) - not_novel: Routine computer vision benchmark not central to the forecasting-specific knowledge vault.
- [dataset] CIFAR-100 (`cifar-100`) - not_novel: Routine computer vision benchmark not central to the forecasting-specific knowledge vault.

## Links

- [Abstract](https://arxiv.org/abs/2605.05718)
- [PDF](https://arxiv.org/pdf/2605.05718)

