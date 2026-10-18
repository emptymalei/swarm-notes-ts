---
# OKF Required Field
type: "paper"

# OKF Recommended Core Fields
title: "Neural networks applied to forecasting the astroclimatic and meteorological parameters in an operational context"
description: "This paper investigates the application of neural networks to forecast astroclimatic and meteorological parameters, such as seeing and wind speed, for ground-based telescopes (ELT/VLT) and free-space optical communication. The authors compare various neural architectures against the current state-of-the-art AutoRegressive (AR) models, focusing on a 1-hour forecasting horizon where AR traditionally excels. A key finding is that 24-hour continuous data availability significantly improves forecast performance, highlighting the challenges posed by daytime gaps in optical turbulence measurements. The work is validated within the operational frameworks of the ALTA Center (LBT) and the FATE project (VLT)."
resource: "https://arxiv.org/abs/2610.19070"
tags:
  - "astrophysics"
  - "time-series-forecasting"
  - "meteorological-forecasting"
  - "operational-forecasting"
  - "machine-learning"
  - "deep-learning"
  - "atmospheric-parameters"
timestamp: "2026-10-18T00:48:55Z"

# CSL-compatible fields (Retained as custom)
author:
  - literal: "C. Weinberger"
  - literal: "E. Masciadri"
  - literal: "M. De Sepibus"
  - literal: "A. Otarola"
  - literal: "S. Miesske"
  - literal: "C. Veillet"
  - literal: "S. Ragland"
issued:
  date-parts:
    - [2026, 10, 13]

# Domain-specific custom fields
paper_id: "2610.19070"
paper_source: "arxiv"
architectures:
  []
concepts:
  - name: "astroclimatic-forecasting"
    description: "The prediction of atmospheric optical turbulence and meteorological variables to optimize ground-based astronomical observations and free-space optical communications."
datasets:
  []
open_questions:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-10-18T00:48:55Z"
created_at: "2026-10-18T00:48:55Z"
---

# Neural networks applied to forecasting the astroclimatic and meteorological parameters in an operational context

**Authors**: C. Weinberger, E. Masciadri, M. De Sepibus, A. Otarola, S. Miesske, C. Veillet, S. Ragland
**Date**: 2026-10-13
**Paper ID**: [arxiv:2610.19070](https://arxiv.org/abs/2610.19070)

## Summary

This paper investigates the application of neural networks to forecast astroclimatic and meteorological parameters, such as seeing and wind speed, for ground-based telescopes (ELT/VLT) and free-space optical communication. The authors compare various neural architectures against the current state-of-the-art AutoRegressive (AR) models, focusing on a 1-hour forecasting horizon where AR traditionally excels. A key finding is that 24-hour continuous data availability significantly improves forecast performance, highlighting the challenges posed by daytime gaps in optical turbulence measurements. The work is validated within the operational frameworks of the ALTA Center (LBT) and the FATE project (VLT).

## Key Contributions

- Demonstrated that neural network architectures can compete with or exceed the performance of state-of-the-art AutoRegressive (AR) models for 1-hour ahead seeing and wind speed forecasts.
- Identified and quantified the negative impact of daytime measurement gaps in optical turbulence data on model training and performance.
- Provided evidence that 24-hour continuous meteorological measurements (using wind speed as a proxy) significantly improve forecast accuracy in operational astronomical settings.

## Limitations

The study primarily tests wind speed as a proxy for performance improvements and notes that lack of daytime optical turbulence measurements remains a significant bottleneck.

## Key Concepts

- [[astroclimatic-forecasting]]: The prediction of atmospheric optical turbulence and meteorological variables to optimize ground-based astronomical observations and free-space optical communications.

## Archivist Review

I approved 'Astroclimatic Forecasting' as it defines a distinct and growing domain within time-series forecasting that involves unique physical constraints (optical turbulence). I rejected the open question regarding daytime data gaps as it is a specific instance of the general missing data problem in time-series analysis. Operational systems and internal frameworks were rejected as datasets per the policy of prioritizing reusable benchmarks.

### Approved Concepts
- Astroclimatic Forecasting: This specialized domain of forecasting is critical for the next generation of ground-based astronomy (ELTs) and high-bandwidth optical communications, requiring the integration of meteorological and optical physics models.

### Rejected Candidates
- [open_question] Mitigating Daytime Astroclimatic Data Gaps (`daytime-turbulence-data-gaps`) - not_reusable: The issue of periodic missing data is a well-known time-series challenge; the diurnal gap in turbulence measurements is a domain-specific instance of this broader problem rather than a unique research direction.
- [concept] Optical Turbulence Prediction (`optical-turbulence-prediction`) - subcomponent_of_broader_mechanism: This is a sub-component of the broader Astroclimatic Forecasting concept and does not merit a separate entry in this context.
- [dataset] ALTA Center Dataset (`alta-center-dataset`) - paper_local: The paper refers to operational frameworks and systems rather than a standardized, publicly accessible dataset for machine learning benchmarking.

## Links

- [Abstract](https://arxiv.org/abs/2610.19070)
- [PDF](https://arxiv.org/pdf/2610.19070)

