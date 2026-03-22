---
edition: asplos-26
type: invited_talk
time_start: 2026-03-22 10:30:00
time_end: 2026-03-22 11:00:00
title: "Memory-Centric Computing: Solving Computing's Memory Problem"
speaker:
    name: Onur Mutlu
    affiliation: ETH Zurich
    avatar: onur.jpg
    url: https://people.inf.ethz.ch/omutlu/
presentation:
---
Computing is bottlenecked by data. Large amounts of application data overwhelm the storage capability, communication capability, and computation capability of the modern machines we design today. As a result, many key applications' performance, efficiency, and scalability are bottlenecked by data movement. In this talk, we describe three major shortcomings of modern computers in terms of 1) dealing with data, 2) taking advantage of vast amounts of data, and 3) exploiting different semantic properties of application data. We argue that an intelligent computing architecture should be designed to handle data well. We posit that handling data well requires designing architectures based on three key principles: 1) data-centric, 2) data-driven, 3) data-aware. We give examples of how to exploit these principles to design a much more efficient and higher performance computing system. We especially discuss recent research that aims to fundamentally reduce memory latency and energy, and practically enable computation close to data, with at least two promising directions: 1) processing using memory, which exploits the fundamental operational properties of memory chips to perform massively-parallel computation in memory, with low-cost changes, 2) processing near memory, which integrates sophisticated additional processing capability in memory chips, the logic layer of 3D-stacked technologies, or memory controllers to enable near-memory computation with high memory bandwidth and low memory latency. We show both types of architectures can enable order(s) of magnitude improvements in performance and energy consumption of many important workloads, such as artificial intelligence, machine learning, graph analytics, database systems, video processing, climate modeling, genome analysis. We discuss how to enable adoption of such fundamentally more intelligent architectures, which are key to efficiency, performance, and sustainability. We conclude with some research opportunities in and guiding principles for future computing architecture and system designs.

An accompanying overview of modern memory-centric computing ideas & systems can be found at [A Modern Primer on Processing in Memory](https://arxiv.org/pdf/2012.03112) (updated February 2025).

A shorter invited paper from IMW 2025 is at [Memory-Centric Computing: Solving Computing's Memory Problem](https://arxiv.org/pdf/2505.00458) (May 2025).
