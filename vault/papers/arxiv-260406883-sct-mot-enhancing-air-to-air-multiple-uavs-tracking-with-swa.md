---
# CSL-compatible fields
title: "SCT-MOT: Enhancing Air-to-Air Multiple UAVs Tracking with Swarm-Coupled Motion and Trajectory Guidance"
author:
  - literal: "Zhaochen Chu"
  - literal: "Tao Song"
  - literal: "Ren Jin"
  - literal: "Shaoming He"
  - literal: "Defu Lin"
  - literal: "Siqing Cheng"
issued:
  date-parts:
    - [2026, 4, 8]
url: "https://arxiv.org/abs/2604.06883"

# Custom fields
paper_id: "2604.06883"
paper_source: "arxiv"
domain: "computer-vision"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "swarm-motion-aware-trajectory-prediction"
  - "trajectory-guided-feature-fusion"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-09T04:55:15Z"
created_at: "2026-04-09T04:55:15Z"
---

# SCT-MOT: Enhancing Air-to-Air Multiple UAVs Tracking with Swarm-Coupled Motion and Trajectory Guidance

**Authors**: Zhaochen Chu, Tao Song, Ren Jin, Shaoming He, Defu Lin, Siqing Cheng
**Date**: 2026-04-08
**Paper ID**: [arxiv:2604.06883](https://arxiv.org/abs/2604.06883)

## Summary

SCT-MOT is a novel tracking framework designed to address the difficulties of tracking small, swarm-based UAVs in air-to-air scenarios. By introducing swarm-level motion dependencies and trajectory-guided feature fusion, the framework overcomes issues related to nonlinear group movement and weak visual cues. Experiments on three standard datasets demonstrate that the proposed SMTP and TG-STFF modules effectively improve tracking robustness and identity consistency compared to existing state-of-the-art methods.

## Key Contributions

- Proposed SCT-MOT, a tracking framework that incorporates swarm-coupled motion dependencies and trajectory-guided feature fusion to mitigate identity switches and trajectory fragmentation in air-to-air UAV tracking.
- Introduced the Swarm Motion-Aware Trajectory Prediction (SMTP) module, which outperforms the state-of-the-art EqMotion module by 1.21% in IDF1.
- Designed the Trajectory-Guided Spatio-Temporal Feature Fusion (TG-STFF) module to enhance temporal consistency and spatial discriminability for small, visually ambiguous objects.

## Open Questions & Future Work

- [[motion-appearance-fusion-bottleneck-mot]]

## Key Concepts

- [[swarm-motion-aware-trajectory-prediction]]: A trajectory prediction framework that captures swarm-level motion dependencies and posture-aware features rather than modeling agents independently.
- [[trajectory-guided-feature-fusion]]: A fusion mechanism that integrates predicted motion trajectories with historical and current visual features to maintain tracking consistency.

## Archivist Review

I approved two concepts focusing on the novel swarm-level motion modeling and the trajectory-guided feature fusion, as these represent transferable strategies for improving tracking in multi-agent environments. I also approved the open question regarding the motion-appearance fusion bottleneck, as it captures the fundamental tension between kinematic prediction and visual recognition that persists across many MOT architectures. Dataset candidates were rejected as they are domain-specific benchmarks rather than canonical datasets with broader significance.

### Approved Concepts
- Swarm Motion-Aware Trajectory Prediction: The module addresses multi-agent dependency modeling in tracking, a critical requirement for group behavior analysis.
- Trajectory-Guided Spatio-Temporal Feature Fusion: This approach addresses the challenge of weak visual cues by anchoring features to motion predictions, a core requirement for small-object MOT.

### Approved Open Questions
- Motion-Appearance Fusion Bottleneck: The coupling of motion and appearance is a primary failure point for MOT in cluttered or visually ambiguous environments.

### Rejected Candidates
- [dataset] AIRMOT (`AIRMOT`) - low_impact: Routine evaluation benchmark for UAV tracking; not a unique or widely critical resource for general vault utility.
- [dataset] MOT-FLY (`MOT-FLY`) - low_impact: Routine evaluation benchmark; lacks the broad utility required for a permanent standalone note.
- [dataset] UAVSwarm (`UAVSwarm`) - low_impact: Routine evaluation benchmark; not a unique or widely critical dataset.

## Links

- [Abstract](https://arxiv.org/abs/2604.06883)
- [PDF](https://arxiv.org/pdf/2604.06883)

