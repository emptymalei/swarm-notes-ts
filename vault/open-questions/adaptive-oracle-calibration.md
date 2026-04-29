---
created_at: '2026-04-29T05:11:00Z'
source_papers:
- '[[arxiv-260425650-using-large-language-models-for-black-box-testing-of-fmu-bas]]'
title: Adaptive Calibration of Testing Oracles
---

**Background:** Large Language Models (LLMs) used for software testing rely on qualitative oracles to evaluate simulation behaviors rather than precise numerical ground truth.

**Question / Future Work:** The reliance on qualitative oracles (e.g., 'settles to', 'bounded') creates a dependency on how accurately these operators map to the underlying dynamics of a simulation model. There is a need for research into adaptive or data-driven methods to automatically calibrate these oracle thresholds and time windows to avoid false failures or missed defects.

**Why It Matters:** Crucial for ensuring the reliability and trustworthiness of automated testing, as improperly configured oracles lead to inaccurate test verdicts.

**Evidence:** Since the LLM generates qualitative oracles (e.g., “settles to” or “bounded”) rather than numerical ground truth, their validity depends on how well these operators map to the system’s actual dynamics. If thresholds or time windows are set too tightly, correct system behaviours may be incorrectly flagged as failures. This limitation highlights the need for adaptive or data-driven oracle calibration, which also remains an open research problem.