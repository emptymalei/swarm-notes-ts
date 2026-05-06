---
# CSL-compatible fields
title: "ProPACT: A Proactive AI-Driven Adaptive Collaborative Tutor for Pair Programming"
author:
  - literal: "Anahita Golrang"
  - literal: "Kshitij Sharma"
  - literal: "olga viberg"
issued:
  date-parts:
    - [2026, 5, 4]
url: "https://arxiv.org/abs/2605.02703"

# Custom fields
paper_id: "2605.02703"
paper_source: "arxiv"
domain: "nlp"
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
skill: "TimeSeriesSkill"
processed_at: "2026-05-06T05:14:09Z"
created_at: "2026-05-06T05:14:09Z"
---

# ProPACT: A Proactive AI-Driven Adaptive Collaborative Tutor for Pair Programming

**Authors**: Anahita Golrang, Kshitij Sharma, olga viberg
**Date**: 2026-05-04
**Paper ID**: [arxiv:2605.02703](https://arxiv.org/abs/2605.02703)

## Summary

ProPACT is a proactive adaptive collaborative tutor designed to support pair programming by treating the collaboration process as an instructional target. It utilizes an XGBoost-based forecasting model to predict suboptimal dyadic collaboration states 30 seconds in advance based on multimodal indicators of joint visual attention and mental effort. The system delivers hierarchical, minimally intrusive scaffolds to regulate collaboration, which experimental results show enhances both learning outcomes and collaborative performance.

## Key Contributions

- Introduces ProPACT, a proactive AI-driven tutor that manages collaborative pair programming through real-time regulation.
- Proposes a multimodal dyadic learner model incorporating Joint Visual Attention and Joint Mental Effort to forecast suboptimal collaborative states 30 seconds ahead.
- Demonstrates through a study of 26 dyads that forecast-driven feedback significantly improves debugging success, efficiency, and collaborative metrics.

## Open Questions & Future Work

- [[scaling-multimodal-collaborative-sensing]]
- [[longitudinal-impact-of-collaborative-scaffolding]]

## Archivist Review

The paper proposes a specific implementation of a collaborative tutor; however, the core concepts (multimodal learner models, hierarchical adaptive policies) are too broad or implementation-specific to merit standalone notes. I have approved two open questions regarding the scalability of sensing and the longitudinal effects of scaffolding, as these represent significant, reusable research challenges in the field of intelligent tutoring systems and collaborative learning.

### Approved Open Questions
- Scalable multimodal collaborative sensing: The reliance on specialized sensing is a primary bottleneck for the generalization and industrial/educational adoption of forecast-driven collaborative tutors.
- Longitudinal impact of scaffolding: Assessing long-term impact is critical for determining the educational value of adaptive tutoring interventions versus their potential to mask underlying learner deficiencies.

### Rejected Candidates
- [open_question] Scalable sensing for collaboration (`scaling-multimodal-sensing`) - duplicate_existing: Renamed to be more descriptive and avoid duplicate concepts in the vault.
- [open_question] Long-term impacts of scaffolding (`longitudinal-learning-impact`) - duplicate_existing: Renamed for better specificity and clarity.

## Links

- [Abstract](https://arxiv.org/abs/2605.02703)
- [PDF](https://arxiv.org/pdf/2605.02703)

