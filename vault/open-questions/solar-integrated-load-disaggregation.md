---
created_at: '2026-04-15T05:04:31Z'
source_papers:
- '[[arxiv-260412304-beyond-weather-correlation-a-comparative-study-of-static-and]]'
title: Solar-Integrated Load Disaggregation
---

**Background:** In residential load forecasting at high temporal resolutions, the integration of distributed energy resources like rooftop solar photovoltaic systems complicates target consumption signals by introducing net-metering effects.

**Question / Future Work:** There is a need to develop and evaluate architectures capable of explicitly separating grid-level consumption and solar generation streams, as current net-metering data often conflate household load with weather-dependent generation signals. This conflation limits the interpretability and accuracy of load-specific forecasting models.

**Why It Matters:** Separating these signals is critical for enabling precise demand response, battery optimization, and grid management in solar-dense residential areas.

**Evidence:** Separate forecasting of Cgrid and Gsolar using a dual-output architecture, eliminating the confound identified in Section 8.2.