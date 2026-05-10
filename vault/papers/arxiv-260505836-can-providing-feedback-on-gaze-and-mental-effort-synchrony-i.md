---
# CSL-compatible fields
title: "Can providing feedback on gaze and mental-effort synchrony improve pair programming performance?"
author:
  - literal: "Anahita Golrang"
  - literal: "Kshitij Sharma"
issued:
  date-parts:
    - [2026, 5, 7]
url: "https://arxiv.org/abs/2605.05836"

# Custom fields
paper_id: "2605.05836"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "gaze-and-mental-effort-synchrony"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-05-10T05:20:20Z"
created_at: "2026-05-10T05:20:20Z"
---

# Can providing feedback on gaze and mental-effort synchrony improve pair programming performance?

**Authors**: Anahita Golrang, Kshitij Sharma
**Date**: 2026-05-07
**Paper ID**: [arxiv:2605.05836](https://arxiv.org/abs/2605.05836)

## Summary

This paper explores the efficacy of AI-supported feedback in improving pair programming through the monitoring of joint visual attention and mental effort. Through two experiments involving dual eye-tracking, the authors compare reactive interventions triggered by regulatory thresholds against proactive interventions based on machine learning forecasts of future breakdowns. The results indicate that both feedback modalities significantly improve collaborative performance, with proactive models being particularly effective at increasing feedback uptake while minimizing intrusive disruptions.

## Key Contributions

- Proposed a multimodal feedback framework for pair programming that utilizes gaze and mental-effort synchrony as regulatory triggers.
- Demonstrated that reactive feedback based on joint visual attention and mental effort thresholds improves debugging success and efficiency.
- Validated that proactive forecast-based feedback reduces time-on-task and increases constructive feedback uptake while better preserving learner agency compared to reactive interventions.

## Open Questions & Future Work

- [[balancing-intervention-timing-and-user-agency]]

## Key Concepts

- [[gaze-and-mental-effort-synchrony]]: A multimodal framework using dual eye-tracking gaze and physiological/cognitive load data to quantify synchronization in collaborative pairs.

## Archivist Review

I have approved the core concept of 'gaze and mental-effort synchrony' as a representative framework for studying human team coordination via multimodal telemetry. I also approved an open question regarding the fundamental trade-off between intervention timing and user agency, which is a known challenge in proactive human-AI collaboration research. Other specific implementation strategies were rejected as sub-components of these broader frameworks.

### Approved Concepts
- Gaze and mental-effort synchrony: Establishes a measurable proxy for collaborative regulation using dual-stream multimodal sensor data, which is central to investigating AI-driven intervention strategies.

### Approved Open Questions
- Intervention timing vs agency: This is a critical bottleneck in the design of collaborative AI agents that aim to act as seamless teammates rather than intrusive monitors.

### Rejected Candidates
- [concept] Reactive threshold-based feedback (`reactive-threshold-feedback`) - subcomponent_of_broader_mechanism: This is a specific instance of a feedback mechanism that is less generalizable than the core synchrony metric identified.
- [concept] Proactive forecast-based feedback (`proactive-forecast-based-feedback`) - subcomponent_of_broader_mechanism: This is a sub-implementation strategy for the broader proactive intervention research area.

## Links

- [Abstract](https://arxiv.org/abs/2605.05836)
- [PDF](https://arxiv.org/pdf/2605.05836)

