---
# CSL-compatible fields
title: "Multimodal Large Language Model Enabled Robust Beamforming for HAP Downlink Communications"
author:
  - literal: "Xiaoyu Xing"
  - literal: "Peng Yang"
  - literal: "Guoquan Tao"
  - literal: "Dingyi Lu"
  - literal: "Zehui Xiong"
  - literal: "Xianbin Cao"
issued:
  date-parts:
    - [2026, 4, 10]
url: "https://arxiv.org/abs/2604.09017"

# Custom fields
paper_id: "2604.09017"
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
skill: "GeneralMLSkill"
processed_at: "2026-04-13T05:10:20Z"
created_at: "2026-04-13T05:10:20Z"
---

# Multimodal Large Language Model Enabled Robust Beamforming for HAP Downlink Communications

**Authors**: Xiaoyu Xing, Peng Yang, Guoquan Tao, Dingyi Lu, Zehui Xiong, Xianbin Cao
**Date**: 2026-04-10
**Paper ID**: [arxiv:2604.09017](https://arxiv.org/abs/2604.09017)

## Summary

This paper introduces a vision-language LLM (VL-LLM) framework to enhance the robustness of High Altitude Platform (HAP) downlink communications against platform attitude fluctuations. By forecasting short-term attitude changes from multivariate telemetry data, the model enables proactive beam steering. The approach incorporates an offline error calibration method and a QoS-aware beamforming policy, significantly improving user service ratios and sum-rates in real-time, delay-sensitive scenarios.

## Key Contributions

- Proposes a vision-language LLM (VL-LLM) framework that utilizes multivariate flight telemetry for short-term HAP attitude forecasting.
- Develops an offline forecast-error calibration procedure to establish performance bounds for reliable proactive analog beam steering.
- Introduces a QoS-driven beamforming and admission strategy with a feasibility-enforcement step, achieving a 22.1% increase in user service ratio and a 12.5% increase in sum-rate compared to baselines.

## Open Questions & Future Work

- [[robust-beamforming-hap-attitude-uncertainty]]

## Archivist Review

I approved the open question regarding robust HAP beamforming because it identifies a substantial and well-defined research challenge at the intersection of predictive modeling and robust control. I rejected the proposed concepts because they represent domain-specific application techniques (HAP attitude forecasting and beam steering) rather than reusable general-purpose ML methods or architectural patterns.

### Approved Open Questions
- Robust HAP Downlink Beamforming: Reliable non-terrestrial network performance depends on maintaining precise beam alignment despite turbulence; addressing the coupling between predictive models and robust optimization is critical for practical 6G deployments.

### Rejected Candidates
- [concept] VL-LLM for HAP Attitude Forecasting (`vision-language-llm-hap-forecasting`) - paper_local: The application of a general architecture (VL-LLM) to a specific domain (HAP attitude forecasting) does not constitute a reusable general-purpose methodological concept.
- [concept] Offline Forecast-Error Calibration (`offline-forecast-error-calibration`) - paper_local: This is a domain-specific implementation detail for ensuring beam steering reliability rather than a generally applicable machine learning paradigm.
- [concept] QoS-Driven Beamforming and Admission (`qos-driven-beamforming-admission`) - paper_local: This is a specific control policy for HAP communications rather than a transferable algorithmic contribution.

## Links

- [Abstract](https://arxiv.org/abs/2604.09017)
- [PDF](https://arxiv.org/pdf/2604.09017)

