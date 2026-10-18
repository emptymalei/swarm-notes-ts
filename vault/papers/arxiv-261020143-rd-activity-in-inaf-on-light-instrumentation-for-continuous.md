---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "R&D activity in INAF on light instrumentation for continuous optical turbulence monitoring"
description: "This paper describes the development of an automated, portable instrumentation station by INAF for continuous monitoring of optical turbulence, a critical factor for ground-based astronomy and Adaptive Optics (AO) optimization. The system integrates multiple sensors—including Cyclope, RINGSS, and scintillometers—to generate the high-resolution, long-term datasets required to train forecasting systems like ALTA and FATE. The authors focus on the real-time acquisition and synchronization capabilities of the platform, enabling on-site testing of forecasting methodologies and the evaluation of low-cost sensors against established profilers. This work serves as a foundation for improving the planning of observational campaigns through more accessible local atmospheric data."
resource: "https://arxiv.org/abs/2610.20143"
tags:
  - "astrophysics"
  - "physics"
  - "environmental-monitoring"
  - "automation"
  - "time-series"
  - "forecasting"
  - "real-time-modeling"
timestamp: "2026-10-18T00:35:32Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "Camilo Weinberger"
  - literal: "Elena Masciadri"
  - literal: "Luca Carbonaro"
  - literal: "Marlene de Sepibus"
  - literal: "Fernando Pedichini"
  - literal: "Ciro Del Vecchio"
  - literal: "Christian Veillet"
  - literal: "Sam Ragland"
issued:
  date-parts:
    - [2026, 10, 14]

# Domain-specific custom fields
paper_id: "2610.20143"
paper_source: "arxiv"
architectures:
  []
concepts:
  []
datasets:
  []
open_questions:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T00:35:32Z"
created_at: "2026-10-18T00:35:32Z"
---

# R&D activity in INAF on light instrumentation for continuous optical turbulence monitoring

**Authors**: Camilo Weinberger, Elena Masciadri, Luca Carbonaro, Marlene de Sepibus, Fernando Pedichini, Ciro Del Vecchio, Christian Veillet, Sam Ragland
**Date**: 2026-10-14
**Paper ID**: [arxiv:2610.20143](https://arxiv.org/abs/2610.20143)

## Summary

This paper describes the development of an automated, portable instrumentation station by INAF for continuous monitoring of optical turbulence, a critical factor for ground-based astronomy and Adaptive Optics (AO) optimization. The system integrates multiple sensors—including Cyclope, RINGSS, and scintillometers—to generate the high-resolution, long-term datasets required to train forecasting systems like ALTA and FATE. The authors focus on the real-time acquisition and synchronization capabilities of the platform, enabling on-site testing of forecasting methodologies and the evaluation of low-cost sensors against established profilers. This work serves as a foundation for improving the planning of observational campaigns through more accessible local atmospheric data.

## Key Contributions

- Development of an automated, portable station integrating multiple sensors (Cyclope, RINGSS, scintillometer) for continuous nighttime optical turbulence monitoring.
- Integration of a real-time on-site monitoring system that manages sensor status, data synchronization, and acquisition for forecasting model training.
- Performance comparison between low-cost sensors (Cyclope, scintillometer) and established turbulence profilers (RINGSS) for 'seeing' measurements.
- Creation of a localized data generation pipeline designed to support the two-year continuous data requirement for high-accuracy optical turbulence forecasting models.

## Limitations

The current system is limited to nighttime measurements; integration of daytime monitoring and long-term validation of the low-cost sensor accuracy against standard benchmarks are still in progress.

## Archivist Review

The paper describes an instrumentation station for astronomical data collection. The proposed candidates are either specific to the field of atmospheric physics or represent existing operational software, lacking the necessary novelty or broad applicability for a machine learning knowledge vault.

### Rejected Candidates
- [concept] ALTA and FATE Forecast Systems (`alta-fate-forecast-systems`) - not_novel: These are existing operational systems mentioned as context, not new concepts introduced in this paper.
- [concept] Optical Turbulence Forecasting (`optical-turbulence-forecasting`) - generic: This is a general field of study rather than a specific technique or architecture introduced by the paper.
- [open_question] Cross-Sensor Calibration for Turbulence Data (`sensor-calibration-for-turbulence-forecasting`) - paper_local: This question is primarily concerned with sensor hardware calibration in astronomical physics rather than a generalizable machine learning research problem.
- [open_question] Diurnal Turbulence Monitoring Integration (`diurnal-optical-turbulence-monitoring`) - paper_local: This is a domain-specific instrumentation challenge for atmospheric science rather than a methodological gap in time-series or ML research.

## Links

- [Abstract](https://arxiv.org/abs/2610.20143)
- [PDF](https://arxiv.org/pdf/2610.20143)

