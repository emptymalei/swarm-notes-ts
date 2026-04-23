---
# CSL-compatible fields
title: "OpenWaveLogger v2026 (OWL-v2026): an open source, low cost, easy to build, high performance logger for wave data measurements"
author:
  - literal: "Jean Rabault"
  - literal: "Joey Voermans"
  - literal: "Takuji Waseda"
  - literal: "Takehiko Nose"
  - literal: "Tsubasa Kodaira"
  - literal: "Koya Sato"
  - literal: "Alexander Babanin"
  - literal: "Gaute Hope"
  - literal: "Malte Müller"
  - literal: "Lars Willas Dreyer"
  - literal: "Øystein Lande"
  - literal: "Atle Jensen"
  - literal: "Øyvind Breivik"
issued:
  date-parts:
    - [2026, 4, 22]
url: "https://arxiv.org/abs/2604.20502"

# Custom fields
paper_id: "2604.20502"
paper_source: "arxiv"
domain: "time-series"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "openwavelogger-v2026"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-23T05:06:12Z"
created_at: "2026-04-23T05:06:12Z"
---

# OpenWaveLogger v2026 (OWL-v2026): an open source, low cost, easy to build, high performance logger for wave data measurements

**Authors**: Jean Rabault, Joey Voermans, Takuji Waseda, Takehiko Nose, Tsubasa Kodaira, Koya Sato, Alexander Babanin, Gaute Hope, Malte Müller, Lars Willas Dreyer, Øystein Lande, Atle Jensen, Øyvind Breivik
**Date**: 2026-04-22
**Paper ID**: [arxiv:2604.20502](https://arxiv.org/abs/2604.20502)

## Summary

This paper presents the OpenWaveLogger v2026 (OWL-v2026), an open-source and low-cost hardware solution designed for high-frequency, in-situ wave data acquisition. Unlike telemetry-limited buoys, the OWL-v2026 enables long-term, high-fidelity logging of six-axis IMU and GNSS data, facilitating detailed research into wave physics. The device utilizes accessible off-the-shelf components, supports low-jitter sampling at up to 416Hz, and ensures high temporal precision through PPS GNSS synchronization. Validated in long-term deployments, it provides a scalable, affordable framework to expand the global availability of high-frequency wave time series.

## Key Contributions

- Introduces OWL-v2026, a $220 open-source, easy-to-assemble data logger for high-frequency wave measurements.
- Achieves low-jitter IMU logging at up to 416Hz with absolute UTC timestamp accuracy better than 10ms via GNSS PPS synchronization.
- Demonstrates 20-day autonomy on D-cell batteries with continuous 208Hz logging, significantly lowering the barrier for high-fidelity oceanographic data collection.

## Open Questions & Future Work

- [[sd-card-write-latency-bottleneck]]

## Key Concepts

- [[openwavelogger-v2026]]: A low-cost, open-source data logger for high-frequency six-axis IMU and GNSS-based wave measurements with PPS synchronization.

## Archivist Review

The paper provides a significant technical contribution to open-source instrumentation for high-frequency time series collection. I approved the logger as a foundational platform and the open question regarding write-latency as it represents a persistent hardware-software bottleneck for edge sensing applications. Other candidates were rejected to maintain the required scarcity.

### Approved Concepts
- OpenWaveLogger v2026 (OWL-v2026): The device provides a standardized, affordable, and open-source platform for high-frequency in-situ wave data acquisition, enabling community-scale oceanographic time series collection.

### Approved Open Questions
- SD Card Write Latency: This identifies a fundamental technical bottleneck for scientific sensor logging at higher sampling frequencies in edge/embedded environments.

### Rejected Candidates
- [concept] OpenWaveLogger v2026 (OWL-v2026) (`openwavelogger-v2026-concept`) - duplicate_existing: The candidate is approved under a cleaner slug.

## Links

- [Abstract](https://arxiv.org/abs/2604.20502)
- [PDF](https://arxiv.org/pdf/2604.20502)

