---
# CSL-compatible fields
title: "Linking Extreme Discourse to Structural Polarization in Signed Interaction Networks"
author:
  - literal: "Zhijin Guo"
  - literal: "Li Zhang"
  - literal: "Tyler Bonnet"
  - literal: "Janet B. Pierrehumbert"
  - literal: "Xiaowen Dong"
issued:
  date-parts:
    - [2026, 5, 12]
url: "https://arxiv.org/abs/2605.12814"

# Custom fields
paper_id: "2605.12814"
paper_source: "arxiv"
domain: "nlp"
tags:
  - "nlp"
  - "causal-inference-derived-outcomes"
architectures:
  []
datasets:
  []
concept_slugs:
  - "language-grounded-signed-network-pipeline"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-05-14T05:25:31Z"
created_at: "2026-05-14T05:25:31Z"
---

# Linking Extreme Discourse to Structural Polarization in Signed Interaction Networks

**Authors**: Zhijin Guo, Li Zhang, Tyler Bonnet, Janet B. Pierrehumbert, Xiaowen Dong
**Date**: 2026-05-12
**Paper ID**: [arxiv:2605.12814](https://arxiv.org/abs/2605.12814)

## Summary

This paper presents a unified framework that bridges the gap between discourse-based analysis and signed-network topology for studying online polarization. By mapping LLM-derived stance scores to continuous, confidence-weighted signed edge weights, the authors introduce a pipeline that captures structural polarization via spectral Eigen-Sign and partition-based frustration metrics. The framework is evaluated on Reddit Brexit discussions, showing that linguistic features such as toxicity and extremity provide predictive insights into future structural shifts. The results emphasize the importance of using continuous edge intensities over traditional sign-only representations for capturing nuanced polarization dynamics.

## Key Contributions

- Introduces a language-grounded pipeline that generates continuous, confidence-weighted signed edge weights from LLM stance scores.
- Develops two complementary polarization metrics, the spectral Eigen-Sign score and a partition-based frustration score, to capture structural dynamics.
- Demonstrates that lagged linguistic signals (e.g., toxicity, extreme claims) exhibit predictive utility for structural polarization in online communities.

## Open Questions & Future Work

- [[optimal-weight-representation-signed-networks]]
- [[generalizing-language-polarization-dynamics]]

## Key Concepts

- [[language-grounded-signed-network-pipeline]]: A methodology that constructs signed interaction graphs by mapping LLM-derived stance scores into continuous edge weights for network analysis.

## Archivist Review

The paper proposes a novel, reusable methodology for integrating LLM-derived stance scores with signed network structures, which is a significant contribution to the study of social polarization. The approved open questions capture substantial, non-trivial bottlenecks regarding the representation of interaction intensity and the generalizability of discourse-structure dynamics across platforms. I have been selective, approving only the overarching pipeline concept and the two critical research questions.

### Approved Concepts
- Language-Grounded Signed-Network Pipeline: Provides a unified framework to bridge language-based discourse with signed-network structural metrics, enabling more granular polarization analysis.

### Approved Open Questions
- Optimal Weight Representation for Signed-Networks: Understanding the optimal weight representation is critical for the accuracy of downstream structural polarization metrics and their sensitivity to nuanced discourse dynamics.
- Generalizing Language-Polarization Dynamics: Establishing generalizability is necessary to determine if the relationship between linguistic discourse and structural fragmentation is a universal phenomenon in online social networks.

## Links

- [Abstract](https://arxiv.org/abs/2605.12814)
- [PDF](https://arxiv.org/pdf/2605.12814)

