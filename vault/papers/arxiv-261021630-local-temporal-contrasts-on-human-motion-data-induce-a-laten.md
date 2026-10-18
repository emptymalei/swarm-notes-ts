---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Local Temporal Contrasts on Human Motion Data Induce a Latent Geometry"
description: "This paper introduces SemTAC, a self-supervised representation learning framework designed to preserve the temporal trajectory of human motion data in latent space. By employing a temporal-neighborhood contrastive loss, the model enforces local consistency, which inductively builds a global geometric structure without requiring forecasting targets or explicit labels. Results show that SemTAC provides a significant advantage in early sequence discrimination (F1 of 0.77 on truncated sequences vs. 0.27-0.70 for baselines) and produces more interpretable latent trajectories as measured by a new displacement-smoothness metric."
resource: "https://arxiv.org/abs/2610.21630"
tags:
  - "time-series"
  - "representation-learning"
  - "self-supervised-learning"
  - "contrastive-learning"
  - "human-activity-recognition"
  - "latent-space-modeling"
  - "temporal-modeling"
timestamp: "2026-10-18T00:20:22Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Lourenço A. Rodrigues"
  - literal: "Felix Putze"
issued:
  date-parts:
    - [2026, 10, 15]

# Domain-specific custom fields
paper_id: "2610.21630"
paper_source: "arxiv"
architectures:
  - "transformers"
concepts:
  - name: "temporal-neighborhood-contrastive-loss"
    description: "A self-supervised learning objective for time-series that encourages proximity in representation space for temporally adjacent windows to induce a continuous latent trajectory."
  - name: "displacement-smoothness-metric"
    description: "A metric for assessing the geometric coherence of latent trajectories by measuring the smoothness of displacements between consecutive time-step representations."
datasets:
  []
open_questions:
  - name: "local-to-global-scaling-limits"
    description: "Does the global structure induced by local temporal contrasts scale effectively to extremely long-range dependencies where local neighborhoods may no longer provide sufficient context for global positioning?"
  - name: "non-smooth-latent-geometry"
    description: "How does the displacement-smoothness metric and the neighborhood contrast objective perform on discrete or non-smooth data where 'geometric continuity' is not a physical property of the source signal?"
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T00:20:22Z"
created_at: "2026-10-18T00:20:22Z"
---

# Local Temporal Contrasts on Human Motion Data Induce a Latent Geometry

**Authors**: Lourenço A. Rodrigues, Felix Putze
**Date**: 2026-10-15
**Paper ID**: [arxiv:2610.21630](https://arxiv.org/abs/2610.21630)

## Summary

This paper introduces SemTAC, a self-supervised representation learning framework designed to preserve the temporal trajectory of human motion data in latent space. By employing a temporal-neighborhood contrastive loss, the model enforces local consistency, which inductively builds a global geometric structure without requiring forecasting targets or explicit labels. Results show that SemTAC provides a significant advantage in early sequence discrimination (F1 of 0.77 on truncated sequences vs. 0.27-0.70 for baselines) and produces more interpretable latent trajectories as measured by a new displacement-smoothness metric.

## Key Contributions

- SemTAC achieves a median F1 of 0.77 on truncated motion sequences (one step before completion), significantly outperforming standard contrastive and classification baselines (0.27-0.70).
- Introduces a temporal-neighborhood contrastive loss that induces global latent geometry by enforcing local temporal consistency without forecasting-based objectives.
- Developed the displacement-smoothness metric to quantitatively demonstrate that SemTAC produces genuinely temporally-ordered and smooth trajectories in the latent space.

## Limitations

The approach was primarily validated on human motion data; its performance on highly stochastic or non-continuous time series (e.g., event logs or sparse financial data) remains untested.

## Open Questions & Future Work

- [[local-to-global-scaling-limits]]
- [[non-smooth-latent-geometry]]

## Key Concepts

- [[temporal-neighborhood-contrastive-loss]]: A self-supervised learning objective for time-series that encourages proximity in representation space for temporally adjacent windows to induce a continuous latent trajectory.
- [[displacement-smoothness-metric]]: A metric for assessing the geometric coherence of latent trajectories by measuring the smoothness of displacements between consecutive time-step representations.

## Archivist Review

The approved concepts focus on the primary methodological innovation (Temporal-Neighborhood Contrastive Loss) and the evaluation framework (Displacement-Smoothness Metric) rather than the specific model name (SemTAC). The open questions address the theoretical limits of local-to-global induction and the applicability of smoothness-based assumptions to non-physical time-series data. No specific named datasets were provided for inclusion.

### Approved Concepts
- Temporal-Neighborhood Contrastive Loss: This objective provides a mechanism for learning global structure from local temporal relations without the need for explicit forecasting or classification labels.
- Displacement-Smoothness Metric: Provides a quantitative way to evaluate whether a representation space respects the temporal ordering and continuity of the input data.

### Approved Open Questions
- Scaling Limits of Local-to-Global Induction: Understanding the limits of local-to-global induction is critical for applying these methods to long-form sensor data, genomic sequences, or climate modeling.
- Latent Geometry in Non-Smooth Time-Series: This determines if the benefits of geometric induction are unique to physical/robotic motion or broadly applicable to all time-series data, such as financial logs or event sequences.

### Rejected Candidates
- [concept] SemTAC (`semtac`) - paper_local: SemTAC is the specific model name coined in this paper; the core innovation is the underlying loss function and the geometric induction method which are captured separately.
- [concept] Motion Sequence Discrimination Task (`motion-sequence-discrimination-task`) - paper_local: This is a specific evaluation setup for the paper rather than a reusable technical concept or methodology.
- [concept] Attention-based Encoders (`attention-based-encoders`) - duplicate_existing: This refers to the broad, existing category of Transformers and similar models already well-established in the field.

## Links

- [Abstract](https://arxiv.org/abs/2610.21630)
- [PDF](https://arxiv.org/pdf/2610.21630)

