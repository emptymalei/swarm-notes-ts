---
# CSL-compatible fields
title: "CityOS: Privacy Architecture for Urban Sensing"
author:
  - literal: "Giorgio Cavicchioli"
  - literal: "Mark Chen"
  - literal: "Navid Salami Pargoo"
  - literal: "Shuren Xia"
  - literal: "Xiaotian Zhou"
  - literal: "Roxana Geambasu"
  - literal: "Jason Nieh"
  - literal: "Jorge Ortiz"
issued:
  date-parts:
    - [2026, 5, 4]
url: "https://arxiv.org/abs/2605.02886"

# Custom fields
paper_id: "2605.02886"
paper_source: "arxiv"
domain: "nlp"
tags:
  []
architectures:
  []
datasets:
  []
concept_slugs:
  - "cityos-architecture"
dataset_slugs:
  []
skill: "GeneralMLSkill"
processed_at: "2026-05-06T05:13:28Z"
created_at: "2026-05-06T05:13:28Z"
---

# CityOS: Privacy Architecture for Urban Sensing

**Authors**: Giorgio Cavicchioli, Mark Chen, Navid Salami Pargoo, Shuren Xia, Xiaotian Zhou, Roxana Geambasu, Jason Nieh, Jorge Ortiz
**Date**: 2026-05-04
**Paper ID**: [arxiv:2605.02886](https://arxiv.org/abs/2605.02886)

## Summary

CityOS is an operating system architecture designed to manage privacy-conscious access to pervasive urban sensing infrastructure. It utilizes a three-tier API structure—ranging from localized raw data processing to citywide differential privacy—to govern how applications access and retain sensitive public space information. By running applications in ephemeral edge containers, the system enforces consistent privacy policies and provides transparency regarding differential privacy budget consumption.

## Key Contributions

- CityOS introduces a three-tier API architecture that mediates urban sensor access with escalating privacy constraints: On-Scene, Single-Locality Aggregation, and Cross-Locality Aggregation.
- Implements an edge runtime environment that executes untrusted sensing applications in ephemeral containers with verifiable differential privacy budget enforcement.
- Demonstrates practical feasibility across diverse urban applications, including pedestrian safety, parking, traffic, and subway monitoring, while maintaining strict policy enforcement.

## Open Questions & Future Work

- [[formal-tracking-error-dp]]

## Key Concepts

- [[cityos-architecture]]: A tiered API architecture for mediating application access to urban sensor data through progressively stronger, policy-enforced privacy constraints.

## Archivist Review

The CityOS architecture provides a clear, reusable framework for edge-based privacy management in sensor networks. I approved the architecture as a concept due to its potential for broader application in IoT and urban infrastructure, and I approved the proposed open question as it addresses a fundamental theoretical bottleneck in bridging computer vision tracking with formal differential privacy guarantees. No other candidates were provided.

### Approved Concepts
- CityOS Architecture: This represents a reusable framework for managing privacy in distributed edge sensing environments, decoupling application logic from raw data access via tiered policy enforcement.

### Approved Open Questions
- Formalizing Tracking-DP Error Bounds: This is critical for transitioning DP applications in computer vision from empirical, heuristic-based sensitivity bounds to theoretically sound, verifiable privacy guarantees.

## Links

- [Abstract](https://arxiv.org/abs/2605.02886)
- [PDF](https://arxiv.org/pdf/2605.02886)

