---
# CSL-compatible fields
title: "Enwar 3.0: An Agentic Multi-Modal LLM Orchestrator for Situation-Aware Beamforming, Blockage Prediction, and Handover Management"
author:
  - literal: "Ahmad M. Nazar"
  - literal: "Abdulkadir Celik"
  - literal: "Asmaa Abdallah"
  - literal: "Mohamed Y. Selim"
  - literal: "Daji Qiao"
  - literal: "Ahmed M. Eltawil"
issued:
  date-parts:
    - [2026, 5, 4]
url: "https://arxiv.org/abs/2605.03215"

# Custom fields
paper_id: "2605.03215"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "enwar-3-0"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-06T05:13:00Z"
created_at: "2026-05-06T05:13:00Z"
---

# Enwar 3.0: An Agentic Multi-Modal LLM Orchestrator for Situation-Aware Beamforming, Blockage Prediction, and Handover Management

**Authors**: Ahmad M. Nazar, Abdulkadir Celik, Asmaa Abdallah, Mohamed Y. Selim, Daji Qiao, Ahmed M. Eltawil
**Date**: 2026-05-04
**Paper ID**: [arxiv:2605.03215](https://arxiv.org/abs/2605.03215)

## Summary

Enwar 3.0 is an agentic framework that leverages multi-modal sensing and large language models to manage mmWave connectivity in vehicular networks. The system employs a classifier-driven assessment of sensor health combined with CoT-primed agents to dynamically select models based on environmental context. Extensive evaluations confirm that this approach achieves high predictive accuracy and interpretability for beamforming, blockage detection, and handover tasks.

## Key Contributions

- Introduces Enwar 3.0, an agentic multi-modal LLM architecture for coordinating beamforming, blockage prediction, and handover management.
- Develops a sensor degradation classification pipeline achieving >99% accuracy across camera, radar, LiDAR, and GPS inputs.
- Demonstrates state-of-the-art performance with >88% beam selection accuracy and >98% blockage F1-scores in complex vehicular environments.

## Open Questions & Future Work

- [[dynamic-agent-architecture-synthesis]]

## Key Concepts

- [[enwar-3-0]]: An agentic multi-modal LLM orchestration framework for real-time decision-making in wireless vehicular networks.

## Archivist Review

The paper presents an agentic framework for wireless resource management. I have approved 'Enwar 3.0' as the primary architecture and 'Dynamic Agent Architecture Synthesis' as the core research bottleneck regarding the limitations of fixed model selection. Other candidates were rejected for being specific subcomponents of the system.

### Approved Concepts
- Enwar 3.0: Provides a unified agentic architecture for orchestrating task-specific models in dynamic wireless communication environments.

### Approved Open Questions
- Dynamic Agent Architecture Synthesis: Static repositories restrict system flexibility and optimality when encountered with scenarios outside the original training scope of the modality combinations.

### Rejected Candidates
- [concept] Sensor degradation classification pipeline (`sensor-degradation-classification-pipeline`) - subcomponent_of_broader_mechanism: This is a specific component for handling sensor health and is not a generalized forecasting or modeling architecture.

## Links

- [Abstract](https://arxiv.org/abs/2605.03215)
- [PDF](https://arxiv.org/pdf/2605.03215)

