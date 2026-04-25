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
processed_at: "2026-04-25T04:56:17Z"
created_at: "2026-04-25T04:56:17Z"
---

# OpenWaveLogger v2026 (OWL-v2026): an open source, low cost, easy to build, high performance logger for wave data measurements

**Authors**: Jean Rabault, Joey Voermans, Takuji Waseda, Takehiko Nose, Tsubasa Kodaira, Koya Sato, Alexander Babanin, Gaute Hope, Malte Müller, Lars Willas Dreyer, Øystein Lande, Atle Jensen, Øyvind Breivik
**Date**: 2026-04-22
**Paper ID**: [arxiv:2604.20502](https://arxiv.org/abs/2604.20502)

## Summary

The OpenWaveLogger v2026 (OWL-v2026) is an open-source, low-cost hardware solution designed to capture high-frequency in-situ wave data that telemetry-limited buoys often miss. By leveraging off-the-shelf components and custom firmware, the logger achieves high-frequency, low-jitter six-axis IMU sampling and precise GNSS timestamping for under 220 USD. The system provides a scalable, community-accessible platform for collecting the full wave time series required for advanced ocean wave physics research.

## Key Contributions

- Introduces OWL-v2026, an open-source, 220 USD high-performance data logger for high-frequency in-situ wave measurements.
- Enables high-frequency IMU logging at up to 416Hz with GNSS-based PPS synchronization for absolute UTC timestamping accurate to <10ms.
- Demonstrates over 10 days of continuous operation with low power consumption of 80mA, supporting 20+ days of autonomy on three D-cell batteries.

## Open Questions & Future Work

- [[sd-card-write-latency-bottleneck]]

## Key Concepts

- [[openwavelogger-v2026]]: An open-source, low-cost data logger for high-frequency ocean wave measurements using off-the-shelf components.

## Archivist Review

The paper presents a significant hardware contribution to time-series collection in oceanography. I approved the concept for the logger itself as it serves as a reusable template for future sensing, and the open question regarding storage latency as it highlights a fundamental limitation of current embedded data logging architectures. No other candidates were proposed.

### Approved Concepts
- OpenWaveLogger v2026: This device provides a low-cost, open-source hardware solution for high-frequency in-situ ocean wave measurements, filling a gap left by telemetry-only systems.

### Approved Open Questions
- High-frequency SD logging constraints: Data storage bottleneck limits the maximum sampling frequency and reliability of low-cost, open-source embedded loggers.

## Links

- [Abstract](https://arxiv.org/abs/2604.20502)
- [PDF](https://arxiv.org/pdf/2604.20502)

