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
processed_at: "2026-04-24T05:10:01Z"
created_at: "2026-04-24T05:10:01Z"
---

# OpenWaveLogger v2026 (OWL-v2026): an open source, low cost, easy to build, high performance logger for wave data measurements

**Authors**: Jean Rabault, Joey Voermans, Takuji Waseda, Takehiko Nose, Tsubasa Kodaira, Koya Sato, Alexander Babanin, Gaute Hope, Malte Müller, Lars Willas Dreyer, Øystein Lande, Atle Jensen, Øyvind Breivik
**Date**: 2026-04-22
**Paper ID**: [arxiv:2604.20502](https://arxiv.org/abs/2604.20502)

## Summary

The OpenWaveLogger v2026 (OWL-v2026) is an open-source, low-cost data logger designed to address the scarcity of affordable systems for high-frequency in-situ ocean wave measurements. Constructed from off-the-shelf components, the system enables high-frequency six-axis IMU logging and synchronized GNSS tracking with sub-10ms UTC timestamp accuracy. This hardware platform offers a scalable alternative to expensive commercial systems, facilitating the collection of high-resolution wave physics data necessary for improving ocean wave models.

## Key Contributions

- Introduces OWL-v2026, an open-source, low-cost (~220 USD) hardware platform for high-frequency in-situ wave time series collection.
- Enables high-frequency IMU logging (208/416Hz) and GNSS tracking (10Hz) with PPS synchronization for precise sub-10ms UTC timestamping.
- Demonstrates over 10 days of continuous, stable operation with approximately 20 days of power autonomy on standard D-cell batteries.

## Open Questions & Future Work

- [[sd-card-write-latency-bottleneck]]

## Key Concepts

- [[openwavelogger-v2026]]: An open-source, low-cost (approx. 220 USD) data logger capable of high-frequency (up to 416Hz) inertial and GNSS wave measurement logging.

## Archivist Review

I approved the OpenWaveLogger v2026 as a landmark piece of open-source hardware for the community and included the SD card latency bottleneck as a significant research problem for high-frequency autonomous sensors. Other candidates were not submitted. I followed the constraint to be scarce in approval.

### Approved Concepts
- OpenWaveLogger v2026: This device serves as a foundational open-source hardware solution for high-frequency ocean wave data collection, filling a critical gap left by telemetry-constrained systems.

### Approved Open Questions
- Optimizing high-frequency data storage: This bottleneck is a primary failure point for scaling high-frequency, long-term, autonomous field deployments.

## Links

- [Abstract](https://arxiv.org/abs/2604.20502)
- [PDF](https://arxiv.org/pdf/2604.20502)

