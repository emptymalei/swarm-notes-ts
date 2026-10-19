---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "An Embedded Industrial Irrigation System with Weather-Integrated Intelligent Scheduling"
description: "This paper presents an embedded industrial irrigation system designed to optimize water usage by fusing local soil moisture sensor data with short-term weather forecasts. The hardware architecture employs a dual-tier approach, using an STM32 microcontroller for precise sensor data acquisition and a BTT Pi platform for edge-based decision-making and local data management. By calculating 'effective precipitation' from forecasts, the system intelligently reduces planned irrigation volumes, maintaining soil moisture within optimal ranges during a one-month cultivation trial. The results demonstrate a technically feasible, scalable platform for precision agriculture that functions independently of cloud infrastructure."
resource: "https://arxiv.org/abs/2610.23179"
tags:
  - "edge-computing"
  - "industrial-applications"
  - "environmental-monitoring"
  - "decision-making"
  - "control-systems"
  - "data-driven-control"
  - "time-series"
timestamp: "2026-10-19T04:32:45Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Kiarash Zangooei"
  - literal: "Arya Masoodpay"
  - literal: "Hamid Reza Ghaeini"
issued:
  date-parts:
    - [2026, 10, 16]

# Domain-specific custom fields
paper_id: "2610.23179"
paper_source: "arxiv"
architectures:
  []
concepts:
  []
datasets:
  []
open_questions:
  - name: "probabilistic-weather-forecast-irrigation"
    description: "Current decision-making logic in smart irrigation often assumes forecasted precipitation and evapotranspiration values are certain, ignoring the inherent variance and uncertainty in meteorological data. Integrating forecast reliability metrics or probabilistic modeling into edge-based controllers is necessary to prevent under-irrigation resulting from unfulfilled rain predictions and to enhance the robustness of autonomous water management systems in variable climates."
skill: "GeneralMLSkill"
processed_at: "2026-10-19T04:32:45Z"
created_at: "2026-10-19T04:32:45Z"
---

# An Embedded Industrial Irrigation System with Weather-Integrated Intelligent Scheduling

**Authors**: Kiarash Zangooei, Arya Masoodpay, Hamid Reza Ghaeini
**Date**: 2026-10-16
**Paper ID**: [arxiv:2610.23179](https://arxiv.org/abs/2610.23179)

## Summary

This paper presents an embedded industrial irrigation system designed to optimize water usage by fusing local soil moisture sensor data with short-term weather forecasts. The hardware architecture employs a dual-tier approach, using an STM32 microcontroller for precise sensor data acquisition and a BTT Pi platform for edge-based decision-making and local data management. By calculating 'effective precipitation' from forecasts, the system intelligently reduces planned irrigation volumes, maintaining soil moisture within optimal ranges during a one-month cultivation trial. The results demonstrate a technically feasible, scalable platform for precision agriculture that functions independently of cloud infrastructure.

## Key Contributions

- Proposed an embedded edge-computing architecture for precision irrigation that integrates STM32 microcontrollers for data acquisition with a BTT Pi platform for local processing and control.
- Developed an intelligent scheduling algorithm that incorporates forecasted 'effective precipitation' to dynamically offset irrigation requirements based on predicted weather events.
- Validated system reliability through a one-month cultivation trial with radishes, maintaining normalized soil moisture consistently within a target control range around 47.93%.
- Demonstrated a decentralized data management strategy capable of logging and processing high-frequency sensor data (38,000+ points) entirely on-device.

## Limitations

The current evaluation is limited to a small-scale radish cultivation trial over one month; performance in large-scale industrial fields or with more complex crop types remains to be tested.

## Open Questions & Future Work

- [[probabilistic-weather-forecast-irrigation]]

## Archivist Review

The paper presents a solid engineering implementation of an embedded irrigation system. The open question regarding the integration of probabilistic weather forecasts is approved, as it addresses a critical robustness bottleneck in applying meteorological models to autonomous control. Other candidates were rejected because they described standard agronomic principles or routine experimental validation requirements.

### Approved Open Questions
- Probabilistic Weather Forecast Integration: Relying on deterministic forecasts without considering confidence levels can lead to significant crop stress if predicted rainfall does not materialize, particularly in water-scarce regions.

### Rejected Candidates
- [concept] Effective Precipitation Scheduling (`effective-precipitation-scheduling`) - not_novel: The concept of effective precipitation is a standard agronomic principle rather than a novel machine learning or architectural contribution.
- [open_question] Empirical Validation of Irrigation Efficiency (`empirical-validation-of-irrigation-efficiency`) - generic: This identifies a standard need for control groups and precise measurement in experimental design rather than a specific unresolved technical mechanism in ML or IoT.

## Links

- [Abstract](https://arxiv.org/abs/2610.23179)
- [PDF](https://arxiv.org/pdf/2610.23179)

