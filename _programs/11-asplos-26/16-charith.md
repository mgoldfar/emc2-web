---
edition: asplos-26
type: invited_talk
time_start: 2026-03-22 17:00:00
time_end: 2026-03-22 17:30:00
title: "Agile and evolvable software construction in the era of rapidly evolving hardware accelerator designs"
speaker:
    name: Charith Mendis
    affiliation: UIUC
    avatar: charith.jpg
    url: https://charithmendis.com/
presentation:
---
Modern AI workloads have become exceedingly abundant and important in the current computing landscape. As a result, there have been numerous software and hardware innovations aimed at accelerating these workloads. However, we observe a subtle disconnect between the software and hardware communities. Most software innovations target well-established hardware platforms such as CPUs (e.g., x86, ARM) and GPUs (e.g., NVidia GPUs), while hardware innovations produce plenty of other tensor accelerator designs (e.g., Gemmini, Feather, Trainium) each year.

We asked the question, why aren't the software community using these accelerators or even evaluating on them? The simple yet undeniable reason is the lack of standardized software tooling compared to CPUs and GPUs. For an architecture to be used, properly designed compiler backends, correctness, and performance testing tools should be abundant (e.g., CUDA ecosystem).

In this talk, I will describe how we bridge this gap by automatically generating the necessary software tools for a large class of accelerators through the Accelerator Compiler Toolkit (ACT) ecosystem. Central to ACT is an ISA definition language, TAIDL, that for the first time standardizes the hardware-software interfaces for a large class of accelerators. Departing from the traditional approach of manually constructing test oracles, performance models, or retargetable compiler backends, we instead introduce agile and evolvable methodologies to automatically generate such necessary tooling using both formal methods and machine learning techniques for any TAIDL-defined accelerator interface. I will show how such automation enables rapid software prototyping, making rapidly evolving accelerator designs usable by the software community.
