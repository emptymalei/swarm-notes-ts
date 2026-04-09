---
created_at: '2026-04-09T04:55:15Z'
source_papers:
- '[[arxiv-260406883-sct-mot-enhancing-air-to-air-multiple-uavs-tracking-with-swa]]'
title: Motion-Appearance Fusion Bottleneck
---

**Background:** Multi-object tracking systems often treat motion prediction and appearance-based classification as decoupled processes, which frequently leads to identity switches and fragmented tracks.

**Question / Future Work:** How to achieve a seamless, deep integration between predictive motion cues and visual appearance features that remains robust when motion predictions are slightly misaligned or visual cues are extremely weak? Future work must explore how to dynamically weight or adapt these fusion mechanisms based on the confidence of the individual prediction and detection streams.

**Why It Matters:** The coupling of motion and appearance is a primary failure point for MOT in cluttered or visually ambiguous environments.

**Evidence:** Existing methods treat motion prediction as a separate process, without deeply integrating with visual cues.