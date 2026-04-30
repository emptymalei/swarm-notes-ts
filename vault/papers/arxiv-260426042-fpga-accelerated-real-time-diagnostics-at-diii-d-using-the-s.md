---
# CSL-compatible fields
title: "FPGA-Accelerated Real-Time Diagnostics at DIII-D Using the SLAC Neural Network Library for ML Inference"
author:
  - literal: "Abhilasha Dave"
  - literal: "Semin Joung"
  - literal: "SangKyeun Kim"
  - literal: "Ramon Reed"
  - literal: "Keith Erickson"
  - literal: "Jalal Butt"
  - literal: "Azarakhsh Jalalvand"
  - literal: "Mudit Mishra"
  - literal: "James Russell"
  - literal: "Larry Ruckman"
  - literal: "Ryan Herbst"
  - literal: "Egemen Kolemen"
  - literal: "David Smith"
  - literal: "Ryan Coffee"
issued:
  date-parts:
    - [2026, 4, 28]
url: "https://arxiv.org/abs/2604.26042"

# Custom fields
paper_id: "2604.26042"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "slac-neural-network-library-snl"
dataset_slugs:
  []
skill: "TimeSeriesSkill"
processed_at: "2026-04-30T05:15:00Z"
created_at: "2026-04-30T05:15:00Z"
---

# FPGA-Accelerated Real-Time Diagnostics at DIII-D Using the SLAC Neural Network Library for ML Inference

**Authors**: Abhilasha Dave, Semin Joung, SangKyeun Kim, Ramon Reed, Keith Erickson, Jalal Butt, Azarakhsh Jalalvand, Mudit Mishra, James Russell, Larry Ruckman, Ryan Herbst, Egemen Kolemen, David Smith, Ryan Coffee
**Date**: 2026-04-28
**Paper ID**: [arxiv:2604.26042](https://arxiv.org/abs/2604.26042)

## Summary

This paper presents a hardware-accelerated machine learning inference system deployed at the DIII-D tokamak fusion reactor for real-time Edge Localized Mode (ELM) forecasting. Using the SLAC Neural Network Library (SNL), the authors implemented a dense neural network on an FPGA that integrates directly into the plasma control loop to suppress disruptive conditions via magnetic coils. The framework significantly enhances operational flexibility by allowing dynamic model weight updates and task switching during live experiments without necessitating hardware resynthesis. This approach provides a scalable template for integrating adaptive ML diagnostics into future high-rate, continuous-operation fusion control systems.

## Key Contributions

- Demonstrated real-time ELM disruption forecasting using a dense neural network on an AMD/Xilinx KCU1500 FPGA within the DIII-D Plasma Control System.
- Introduced the SLAC Neural Network Library (SNL) for FPGAs, enabling on-the-fly weight updates and task hot-swapping without hardware resynthesis.
- Developed a context-aware control framework for reactor diagnostics that facilitates active suppression of disruptive plasma conditions using RMP coils.

## Key Concepts

- [[slac-neural-network-library-snl]]: A software library for FPGA-based neural network inference that supports dynamic, on-the-fly weight updates and task switching without hardware resynthesis.

## Archivist Review

The paper presents a clear application of FPGA acceleration for real-time diagnostic and control in a fusion environment. The SLAC Neural Network Library (SNL) is identified as a novel, reusable concept due to its specific architectural benefit of allowing runtime parameter updates without hardware resynthesis, which is a significant bottleneck in edge-based hardware deployment. No other candidates were proposed, and no specific datasets were identified as central contributions.

### Approved Concepts
- SLAC Neural Network Library (SNL): It enables on-the-fly updates of neural network weights on FPGA hardware without requiring full resynthesis, which is critical for real-time control systems.

## Links

- [Abstract](https://arxiv.org/abs/2604.26042)
- [PDF](https://arxiv.org/pdf/2604.26042)

