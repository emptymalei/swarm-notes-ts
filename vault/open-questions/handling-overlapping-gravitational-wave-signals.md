---
created_at: '2026-04-28T05:14:33Z'
source_papers:
- '[[arxiv-260424330-pre-localization-of-massive-black-hole-binaries-in-the-milli]]'
title: Handling overlapping GW signals
---

**Background:** Massive black hole binary (MBHB) signals in the millihertz gravitational-wave band exhibit complex parameter degeneracies and multimodal posterior distributions, particularly when analyzed over short time windows near coalescence.

**Question / Future Work:** Future work must address how the performance of normalizing flow-based inference pipelines degrades in the presence of overlapping gravitational-wave signals from multiple sources, as current approaches typically assume isolated single-event analysis. Investigating whether source-separation decoders can be integrated with existing rapid-inference modules is essential for scaling these pipelines to realistic detector data streams.

**Why It Matters:** As space-based detectors will observe signals from numerous overlapping sources, developing techniques to perform robust parameter estimation and deblending in high-density data is a fundamental requirement for operational pipeline scalability.