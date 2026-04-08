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
  - "graph-neural-networks"
  - "contrastive-learning"
  - "spatiotemporal-forecasting"
  - "extreme-weather-forecasting"
architectures:
  []
datasets:
  []
concept_slugs:
  []
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-04-08T04:58:15Z"
created_at: "2026-04-08T04:58:15Z"
---

# Empowering Power Outage Prediction with Spatially Aware Hybrid Graph Neural Networks and Contrastive Learning

**Authors**: Xuyang Shen, Zijie Pan, Diego Cerrai, Xinxuan Zhang, Christopher Colorio, Emmanouil N. Anagnostou, Dongjin Song
**Date**: 2026-04-06
**Paper ID**: [arxiv:2604.04916](https://arxiv.org/abs/2604.04916)

## Summary

This paper presents the Spatially Aware Hybrid Graph Neural Network (SA-HGNN) to improve power outage forecasting during extreme weather events. By encoding both static land-cover data and dynamic meteorological features, the model captures complex spatial dependencies within electric distribution networks. Additionally, the framework incorporates contrastive learning to generate robust, location-specific embeddings, effectively addressing the challenges posed by imbalanced event datasets. Extensive validation across multiple utility service territories confirms that this approach significantly enhances predictive accuracy over existing methods.

## Key Contributions

- Introduces Spatially Aware Hybrid Graph Neural Networks (SA-HGNN) to integrate static infrastructure and dynamic weather features for outage prediction.
- Employs contrastive learning to mitigate data imbalances between extreme weather event types by optimizing location-specific embedding spaces.
- Demonstrates state-of-the-art predictive performance on power outage datasets across four distinct New England utility territories.

## Open Questions & Future Work

- [[cross-region-infrastructure-generalization]]
- [[spatiotemporal-graph-outage-dynamics]]

## Archivist Review

The paper proposes a specific graph neural network architecture (SA-HGNN) and a contrastive learning approach for power outage prediction. Since these are standard applications of GNNs and contrastive learning rather than novel paradigms, no new concepts were approved. The identified open questions were mapped to existing, more generalized vault entries to avoid duplication.

### Approved Open Questions
- Cross-region infrastructure generalization: This is critical for scaling predictive outage systems to new utility providers or territories without the need for extensive retraining and to improve the overall resilience of the forecasting models.
- Spatiotemporal graph outage dynamics: Improving temporal resolution is essential for real-time monitoring and better-informed disaster response planning, as it would enable the modeling of causal mechanisms like cascading infrastructure failures.

### Rejected Candidates
- [open_question] Cross-region power outage generalization (`cross-region-outage-generalization`) - duplicate_existing: This is a semantic duplicate of existing vault entry 'cross-region-infrastructure-generalization'.
- [open_question] Continuous spatio-temporal graph modeling (`spatio-temporal-graph-evolution`) - duplicate_existing: This is a semantic duplicate of existing vault entry 'spatiotemporal-graph-outage-dynamics'.

## Links

- [Abstract](https://arxiv.org/abs/2604.04916)
- [PDF](https://arxiv.org/pdf/2604.04916)

