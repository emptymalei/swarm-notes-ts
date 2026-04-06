---
created_at: '2026-04-06T05:03:26Z'
source_papers:
- '[[arxiv-260402711-foundation-models-defining-a-new-era-in-sensor-based-human-a]]'
title: Scaling HAR Pretraining Under Fragmentation
---

**Background:** Sensor-based human activity recognition (HAR) systems often rely on small, fragmented, and non-IID datasets, which hinders the development of robust, generalizable foundation models. Scaling pretraining for these models remains challenging due to modality heterogeneity, privacy constraints, and the lack of web-scale, standardized data similar to those available in vision or language domains.

**Question / Future Work:** It remains unclear how to effectively scale foundation model pretraining using fragmented, non-IID, and privacy-sensitive sensor data. Future research needs to establish frameworks for learning transferable representations from partially observed streams across diverse device placements and populations, as well as methods to incorporate synthetic or simulated data without compromising downstream model performance.

**Why It Matters:** This is a fundamental bottleneck for HAR foundation models, as their ability to generalize across real-world deployments is strictly limited by the current data landscape. Addressing this is necessary for moving from small, task-specific models to true foundation models.