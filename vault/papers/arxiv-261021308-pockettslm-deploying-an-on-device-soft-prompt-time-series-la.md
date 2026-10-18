---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "PocketTSLM: Deploying an On-Device Soft-Prompt Time-Series Language Model for Privacy-Preserving Smartphone Reasoning"
description: "PocketTSLM is a mobile-native deployment of the OpenTSLM SoftPrompt model designed for privacy-preserving reasoning on physiological time-series data directly on smartphones. By utilizing soft-prompting—injecting encoded time-series windows as embeddings rather than text-serialized tokens—it achieves a 12x reduction in token usage, allowing it to process long sequences such as 30-second EEG clips that exceed standard on-device context budgets. Implemented in Swift using Apple's MLX framework, the system ensures numerical parity with reference Python models and performs all inference locally, ensuring that sensitive health data never leaves the device."
resource: "https://arxiv.org/abs/2610.21308"
tags:
  - "time-series"
  - "edge-ai"
  - "privacy-preserving-ml"
  - "healthcare-ai"
  - "transformer"
  - "inference-optimization"
  - "efficiency"
timestamp: "2026-10-18T00:22:12Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Max Rosenblattl"
  - literal: "Nikhil Krishnaswamy"
  - literal: "Leon Nissen"
  - literal: "Manuel Milling"
  - literal: "Nicolas Zumarraga"
  - literal: "Ning Wang"
  - literal: "Thomas Kaar"
  - literal: "Robert Jakob"
  - literal: "Björn W. Schuller"
  - literal: "Elgar Fleisch"
  - literal: "Patrick Langer"
  - literal: "Paul Schmiedmayer"
issued:
  date-parts:
    - [2026, 10, 15]

# Domain-specific custom fields
paper_id: "2610.21308"
paper_source: "arxiv"
architectures:
  - "transformer"
concepts:
  - name: "time-series-soft-prompting"
    description: "A technique for mapping time-series segments directly into a language model's latent space as continuous embeddings to bypass the overhead of text-based tokenization."
datasets:
  []
open_questions:
  - name: "multimodal-soft-prompt-fusion"
    description: "How can soft-prompted embeddings be designed to effectively fuse multi-modal, multi-rate sensor data (e.g., combining high-frequency ECG with low-frequency activity logs) within a single latent space for holistic health reasoning?"
  - name: "on-device-tslm-energy-impact"
    description: "What are the architectural and hardware-level optimizations required to maintain continuous TSLM inference for passive physiological monitoring without exceeding thermal limits or significantly degrading smartphone battery life?"
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T00:22:12Z"
created_at: "2026-10-18T00:22:12Z"
---

# PocketTSLM: Deploying an On-Device Soft-Prompt Time-Series Language Model for Privacy-Preserving Smartphone Reasoning

**Authors**: Max Rosenblattl, Nikhil Krishnaswamy, Leon Nissen, Manuel Milling, Nicolas Zumarraga, Ning Wang, Thomas Kaar, Robert Jakob, Björn W. Schuller, Elgar Fleisch, Patrick Langer, Paul Schmiedmayer
**Date**: 2026-10-15
**Paper ID**: [arxiv:2610.21308](https://arxiv.org/abs/2610.21308)

## Summary

PocketTSLM is a mobile-native deployment of the OpenTSLM SoftPrompt model designed for privacy-preserving reasoning on physiological time-series data directly on smartphones. By utilizing soft-prompting—injecting encoded time-series windows as embeddings rather than text-serialized tokens—it achieves a 12x reduction in token usage, allowing it to process long sequences such as 30-second EEG clips that exceed standard on-device context budgets. Implemented in Swift using Apple's MLX framework, the system ensures numerical parity with reference Python models and performs all inference locally, ensuring that sensitive health data never leaves the device.

## Key Contributions

- Developed PocketTSLM, an on-device time-series language model that avoids text-serialization overhead by using soft-prompt embeddings.
- Achieved a 12x reduction in token consumption compared to text-serialized baselines, enabling inference on long temporal windows (e.g., 30s EEG) within smartphone memory limits.
- Established a numerical parity protocol using Apple's MLX framework to ensure consistent greedy-decoded outputs between mobile Swift ports and Python references.
- Demonstrated privacy-preserving reasoning for physiological signals (EEG, ECG) without transmitting health data to the cloud.

## Limitations

The paper notes that while greedy token sequences match the Python reference, rationale wording in natural language outputs can differ between PyTorch and MLX implementations.

## Open Questions & Future Work

- [[multimodal-soft-prompt-fusion]]
- [[on-device-tslm-energy-impact]]

## Key Concepts

- [[time-series-soft-prompting]]: A technique for mapping time-series segments directly into a language model's latent space as continuous embeddings to bypass the overhead of text-based tokenization.

## Archivist Review

The approved concept 'Time-Series Soft-Prompting' captures the critical architectural shift from inefficient text-serialization to embedding-based injection, which is essential for mobile-native time-series reasoning. The datasets were rejected as they are routine benchmarks in the medical AI community. Open questions were approved as they address the substantial future challenges of sensor fusion and power efficiency for continuous on-device monitoring.

### Approved Concepts
- Time-Series Soft-Prompting: This technique directly addresses the context window and memory bottlenecks of traditional LLMs when applied to high-frequency or long-duration time-series data.

### Approved Open Questions
- Multi-Modal Soft-Prompt Fusion: Clinical reasoning often depends on the intersection of multiple physiological signals, but current embedding-based LLM architectures struggle with cross-modal temporal alignment.
- Sustainability of Continuous On-Device TSLM Inference: Real-world deployment of TSLMs for chronic condition monitoring requires balancing high-frequency inference with the strict power constraints of mobile devices.

### Rejected Candidates
- [concept] PocketTSLM (`pocket-tslm`) - paper_local: This is a specific software implementation/port name rather than a reusable architectural concept. The underlying mechanism is better captured by 'Time-Series Soft-Prompting'.
- [dataset] Sleep-EDF (`Sleep-EDF`) - not_novel: This is a routine, well-established benchmark in the sleep study domain and does not require a new standalone note within the context of this paper's contributions.
- [dataset] ECG-QA (`ECG-QA`) - not_novel: This is a standard existing benchmark for electrocardiogram question-answering used here for evaluation rather than being a core contribution of the paper.

## Links

- [Abstract](https://arxiv.org/abs/2610.21308)
- [PDF](https://arxiv.org/pdf/2610.21308)

