---
edition: asplos-26
type: invited_talk
time_start: 2026-03-22 11:00:00
time_end: 2026-03-22 11:30:00
title: "Efficient and Scalable Agentic AI With Heterogeneous Systems"
speaker:
    name: Zain Asgar
    affiliation: Gimlet AI
    avatar: zain.jpg
    url: https://gimletlabs.ai/
presentation:
---
AI agents are dynamic, multi-stage systems composed of diverse operations with very different resource characteristics, ranging from compute- and memory-intensive model execution to bandwidth- and IO-bound data processing. Yet most deployments today run on homogeneous infrastructure, despite inference itself being inherently heterogeneous across its phases. In this talk, we present a system for orchestrating agent workloads across a mix of CPUs, GPUs, and accelerators spanning vendors and hardware tiers. The system automatically decomposes agentic workloads into fine-grained execution graphs, compiles them into hardware-specific fragments, and dynamically places and stitches them across distributed infrastructure to meet latency and performance goals. By mapping each stage of execution to the hardware best suited for it, we show how we can achieve step-function performance gains and significant improvements in cost efficiency. We highlight results showing how emerging hardware like SRAM-centric chips, combined with existing GPU infrastructure, can outperform traditional homogeneous deployments.
