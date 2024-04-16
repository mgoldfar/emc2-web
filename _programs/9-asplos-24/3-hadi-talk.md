---
edition: asplos-24
type: invited_talk
time_start: 2024-04-27 16:15:00
time_end: 2024-04-27 16:45:00
title: "Neural Networks are not Matrix Multiplications"
speaker:
    name: Hadi S. Esmaeilzadeh 
    affiliation: UCSD
    avatar: hadi.jpg  
    url: https://cseweb.ucsd.edu/~hadi/

presentation: 
---
With the ever-increasing prevalence of neural networks and language models, it is time to rethink neural acceleration. Past research has focused disproportionately on General Matrix Multiplication (GEMM) operations, assuming they dominate neural computations. However, non-GEMM operations have grown in diversity and complexity, interweaving with GEMM. Conventional Neural Processing Units (NPUs) have taken simplistic approaches to handling these operations. In this talk, I will discuss our most recent work that challenges the conventional wisdom in neural accelerator design and explores the architecture of a specialized "Tandem Processor" that complements the GEMM unit. The Tandem Processor is specialized for memory access logic with a novel Instruction Set Architecture (ISA) and microarchitecture that alleviates the register file, while offering programmability at the mathematical level for non-GEMM layers. This balances specialization and programmability, sustaining the throughput and utilization of the neural accelerator. We provide the Register Transfer Level (RTL) code that is synthesizable both for Field-Programmable Gate Array (FPGA) and Application-Specific Integrated Circuit (ASIC) implementations in addition to the associated compiler as part of the open-source GeneSys initiative (https://actlab-genesys.github.io/). Tandem and GeneSys are the result of more than a decade of pioneering work in NPU design and open-sourcing accelerators.

