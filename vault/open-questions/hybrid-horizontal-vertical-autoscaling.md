---
created_at: '2026-04-14T05:04:18Z'
source_papers:
- '[[arxiv-260411017-nimbusguard-a-novel-framework-for-proactive-kubernetes-autos]]'
title: Hybrid Horizontal and Vertical Autoscaling
---

**Background:** Kubernetes autoscaling currently relies on reactive mechanisms that adjust resources after demand spikes are detected, often leading to either resource under-provisioning or over-provisioning. While proactive Reinforcement Learning (RL) approaches have been proposed, they often lack sophisticated, closed-loop mechanisms to handle complex infrastructure events or interpret unstructured data.

**Question / Future Work:** Research is needed to develop a hybrid autoscaling framework that integrates Vertical Pod Autoscaling (VPA) with existing proactive horizontal scaling models. The goal is to allow the system to intelligently choose between adding more pod replicas or dynamically resizing the resource limits of existing pods to optimize both performance and cost-efficiency.

**Why It Matters:** The current focus on horizontal scaling alone limits the flexibility and cost-optimization potential of Kubernetes autoscalers. A hybrid approach combining horizontal and vertical scaling could significantly improve resource utilization efficiency.