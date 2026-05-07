---
# CSL-compatible fields
title: "OpenWatch: A Multimodal Benchmark for Hand Gesture Recognition on Smartwatches"
author:
  - literal: "Pietro Bonazzi"
  - literal: "Youssef Ahmed"
  - literal: "Daniel Eckert"
  - literal: "Andrea Ronco"
  - literal: "Junjie Zeng"
  - literal: "Dengxin Dai"
  - literal: "Michele Magno"
issued:
  date-parts:
    - [2026, 5, 6]
url: "https://arxiv.org/abs/2605.04791"

# Custom fields
paper_id: "2605.04791"
paper_source: "arxiv"
domain: "time-series"
tags:
  - "time-series-forecasting"
  - "multimodal-learning"
  - "benchmark"
  - "gesture-recognition"
  - "wearable-sensing"
  - "edge-ai"
architectures:
  []
datasets:
  - "openwatch"
concept_slugs:
  - "mixtoken"
dataset_slugs:
  - "openwatch"
skill: "TimeSeriesSkill"
processed_at: "2026-05-07T05:15:15Z"
created_at: "2026-05-07T05:15:15Z"
---

# OpenWatch: A Multimodal Benchmark for Hand Gesture Recognition on Smartwatches

**Authors**: Pietro Bonazzi, Youssef Ahmed, Daniel Eckert, Andrea Ronco, Junjie Zeng, Dengxin Dai, Michele Magno
**Date**: 2026-05-06
**Paper ID**: [arxiv:2605.04791](https://arxiv.org/abs/2605.04791)

## Summary

OpenWatch addresses the lack of benchmarks for smartwatch-based gesture recognition by providing a large-scale, multimodal dataset of synchronized IMU and PPG signals. The authors introduce two specialized methodologies: MixToken, a memory-efficient mixture-of-experts architecture for multimodal fusion, and NormWear-Lora, a low-rank adaptation framework for foundation models. Experimental results demonstrate that incorporating PPG data significantly boosts performance, while task-specific designs like MixToken provide superior accuracy and efficiency compared to general-purpose foundation models on wearable devices.

## Key Contributions

- Introduces OpenWatch, the first open-access multimodal benchmark for wrist-based gesture recognition featuring 10 hours of synchronized IMU and PPG data across 50 participants.
- Develops MixToken, a specialized mixture-of-experts architecture that achieves 90% F1-score with 223k parameters, significantly outperforming foundation models in accuracy and memory efficiency.
- Provides empirical validation that PPG signals improve predictive performance by 12.5% F1-score for foundational smartwatch models.
- Presents NormWear-Lora, a low-rank adaptation module designed to enable efficient fine-tuning of foundation models on resource-constrained wearable hardware.

## Open Questions & Future Work

- [[multimodal-gesture-personalization-fusion]]

## Key Concepts

- [[mixtoken]]: A mixture-of-experts architecture for multimodal wearable gesture recognition that fuses IMU filterbank features with cross-channel statistical tokens via learned logit mixing.

## Archivist Review

The paper provides a valuable benchmark for wearable gesture recognition and proposes a memory-efficient fusion architecture. I approved 'MixToken' for its novel architectural fusion approach and the 'OpenWatch' dataset as a standalone benchmark. I rejected 'NormWear-Lora' as it is an application-specific instance of the established LoRA technique. The approved open question addresses the critical, unresolved bottleneck of multimodal fusion and personalization in wearable sensing.

### Approved Concepts
- MixToken: It is a novel, memory-efficient architecture tailored for resource-constrained hand gesture recognition that outperforms larger foundation models.

### Approved Open Questions
- Personalization and Multimodal Fusion: The paper identifies that while PPG adds significant value, the exact fusion dynamics and personalization strategies for in-the-wild gesture recognition remain under-optimized, creating a bottleneck for real-world adoption.

### Rejected Candidates
- [concept] NormWear-Lora (`normwear-lora`) - subcomponent_of_broader_mechanism: This is a specific implementation of low-rank adaptation (LoRA) for a domain, which does not warrant a separate concept note beyond the general LoRA mechanism already established in the community.

## Datasets

- [[openwatch]]

## Links

- [Abstract](https://arxiv.org/abs/2605.04791)
- [PDF](https://arxiv.org/pdf/2605.04791)

