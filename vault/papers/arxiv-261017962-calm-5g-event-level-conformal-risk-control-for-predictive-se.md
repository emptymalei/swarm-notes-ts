---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "CALM-5G: Event-Level Conformal Risk Control for Predictive Service-Assurance Alarms"
description: "The paper introduces CALM-5G, an assurance framework designed to convert KPI forecasts into reliable service-level alarms with distribution-free, finite-sample guarantees. By utilizing Conformal Risk Control (CRC) and targeting violation onsets specifically, the system significantly reduces the alarm duty cycle—lowering false alarm durations by over 50% across multiple testbeds—without compromising on the certified miss rate. The authors demonstrate the framework's effectiveness on production 5G traces and O-RAN testbeds, showing that online calibration is essential for maintaining compliance under the label shifts typical of real-world cellular networks."
resource: "https://arxiv.org/abs/2610.17962"
tags:
  - "conformal-prediction"
  - "time-series-forecasting"
  - "anomaly-detection"
  - "calibration"
  - "distribution-shift"
  - "online-learning"
  - "reliability"
  - "spatio-temporal-modeling"
timestamp: "2026-10-18T01:00:44Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Ömer Faruk İşcanlı"
  - literal: "Yağmur Sabucu Sandal"
issued:
  date-parts:
    - [2026, 10, 13]

# Domain-specific custom fields
paper_id: "2610.17962"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "event-level-conformal-risk-control"
    description: "A variation of conformal risk control that calibrates thresholds based on the onset of temporal events rather than individual time-steps to optimize alarm duty cycles."
datasets:
  []
open_questions:
  - name: "conformal-risk-control-non-stationarity"
    description: "How can conformal risk control be optimally adapted for highly non-stationary environments where label shifts occur frequently, and how can calibration schemes be updated online to maintain valid coverage without excessive lag?"
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T01:00:44Z"
created_at: "2026-10-18T01:00:44Z"
---

# CALM-5G: Event-Level Conformal Risk Control for Predictive Service-Assurance Alarms

**Authors**: Ömer Faruk İşcanlı, Yağmur Sabucu Sandal
**Date**: 2026-10-13
**Paper ID**: [arxiv:2610.17962](https://arxiv.org/abs/2610.17962)

## Summary

The paper introduces CALM-5G, an assurance framework designed to convert KPI forecasts into reliable service-level alarms with distribution-free, finite-sample guarantees. By utilizing Conformal Risk Control (CRC) and targeting violation onsets specifically, the system significantly reduces the alarm duty cycle—lowering false alarm durations by over 50% across multiple testbeds—without compromising on the certified miss rate. The authors demonstrate the framework's effectiveness on production 5G traces and O-RAN testbeds, showing that online calibration is essential for maintaining compliance under the label shifts typical of real-world cellular networks.

## Key Contributions

- Introduced CALM-5G, a distribution-free assurance layer that applies Conformal Risk Control (CRC) to KPI forecasts to generate certified service-assurance alarms.
- Proposed an onset-targeting scoring mechanism with cross-validated calibration that reduces the alarm duty cycle (time-in-alarm) by 56.3% to 89.7% while maintaining statistical miss rate guarantees.
- Demonstrated that online calibration successfully mitigates label shift in production cellular networks, where batch calibration fails by up to 10.9 standard errors.
- Validated joint certification of miss rate and duty cycle across four distinct 5G corpora, including production and O-RAN testbeds.

## Limitations

The paper notes that joint certification of miss rate and duty cycle requires sufficient calibration units, which may be limited by within-entity dependence in certain environments.

## Open Questions & Future Work

- [[conformal-risk-control-non-stationarity]]

## Key Concepts

- [[event-level-conformal-risk-control]]: A variation of conformal risk control that calibrates thresholds based on the onset of temporal events rather than individual time-steps to optimize alarm duty cycles.

## Archivist Review

The selection prioritizes the methodological innovation of 'Event-Level Conformal Risk Control' over the specific framework name 'CALM-5G', as the former represents a reusable mathematical approach to temporal monitoring. The approved open question addresses the fundamental challenge of applying statistical guarantees to non-stationary time-series, which is a significant research gap in the field. No datasets were approved as the paper relies on proprietary cellular traces and specific testbed measurements.

### Approved Concepts
- Event-Level Conformal Risk Control: Traditional conformal prediction/risk control often treats every time-step as an independent instance. Calibrating specifically on 'events' or 'onsets' allows for optimizing operational metrics like duty cycle (false alarm duration) while maintaining statistical guarantees on the miss rate.

### Approved Open Questions
- Conformal Risk Control under Non-Stationarity: Maintaining reliability guarantees in mission-critical systems like 5G networks requires robustness to rapid shifts in traffic patterns and network topology that batch calibration cannot handle.

### Rejected Candidates
- [concept] CALM-5G (`calm-5g`) - paper_local: This is the specific name of the framework presented in the paper rather than a generalizable concept or mechanism. The underlying innovation is better captured by Event-Level Conformal Risk Control.

## Links

- [Abstract](https://arxiv.org/abs/2610.17962)
- [PDF](https://arxiv.org/pdf/2610.17962)

