---
# CSL-compatible fields
title: "Empowering Power Outage Prediction with Spatially Aware Hybrid Graph Neural Networks and Contrastive Learning"
author:
  - literal: "Xuyang Shen"
  - literal: "Zijie Pan"
  - literal: "Diego Cerrai"
  - literal: "Xinxuan Zhang"
  - literal: "Christopher Colorio"
  - literal: "Emmanouil N. Anagnostou"
  - literal: "Dongjin Song"
issued:
  date-parts:
    - [2026, 4, 6]
url: "https://arxiv.org/abs/2604.04916"

# Custom fields
paper_id: "2604.04916"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-04-07T04:52:44Z"
created_at: "2026-04-07T04:52:44Z"
---

# Empowering Power Outage Prediction with Spatially Aware Hybrid Graph Neural Networks and Contrastive Learning

**Authors**: Xuyang Shen, Zijie Pan, Diego Cerrai, Xinxuan Zhang, Christopher Colorio, Emmanouil N. Anagnostou, Dongjin Song
**Date**: 2026-04-06
**Paper ID**: [arxiv:2604.04916](https://arxiv.org/abs/2604.04916)

## Summary

The paper presents the Spatially Aware Hybrid Graph Neural Network (SA-HGNN) to improve power outage forecasting during extreme weather events. By encoding both static infrastructure and dynamic environmental features, the model captures complex spatial dependencies within electric distribution networks. Furthermore, the approach utilizes contrastive learning to mitigate data imbalances, enabling more robust location-specific predictions across varying storm conditions.

## Key Contributions

- Introduces SA-HGNN, a graph neural network architecture that integrates static infrastructure and dynamic weather features to model spatial dependencies in power grid failures.
- Applies a contrastive learning objective to address class imbalance and data sparsity across different extreme weather event types by optimizing location-specific embeddings.
- Demonstrates state-of-the-art predictive performance for power outage forecasting across four diverse utility service territories in the Northeastern United States.

## Open Questions & Future Work

- [[cross-region-infrastructure-generalization]]
- [[spatiotemporal-graph-outage-dynamics]]

## Archivist Review

The paper proposes a specific application of GNNs and contrastive learning for power outages. I have rejected the specific SA-HGNN architecture as it is a standard application of GNNs in a specific domain, and approved two open questions that capture the fundamental bottlenecks in infrastructure modeling: geographic generalization and the transition from static snapshots to continuous spatio-temporal dynamics.

### Approved Open Questions
- Cross-Region Infrastructure Generalization: This is a fundamental challenge for scaling predictive infrastructure models across diverse geographic regions with varying characteristics.
- Spatio-Temporal Outage Dynamics Modeling: Modeling the dynamic, time-dependent nature of storms is critical for accurate, real-time outage forecasting.

### Rejected Candidates
- [open_question] Cross-region generalization in outages (`cross-region-outage-prediction-generalization`) - other: Renamed for broader applicability as a general infrastructure modeling problem rather than just outage-specific.

## Links

- [Abstract](https://arxiv.org/abs/2604.04916)
- [PDF](https://arxiv.org/pdf/2604.04916)

