---
edition: virtual-21
type: invited_talk
time_start: 2021-08-28 16:00:00
time_end: 2021-08-28 16:45:00
title: "Project Fiddle: Fast and Efficient Infrastructure for Distributed Deep Learning "
speaker:
    name: Amar Phanisayee
    affiliation: Microsoft Research
    avatar: amarp.jpg 
    url: https://www.linkedin.com/in/amar-phanishayee-a955673/

presentation: 
---
The goal of Project Fiddle is to build efficient systems infrastructure for fast distributed DNN training. Our goal is to support 100x more efficient training. To achieve this goal, we take a broad view of training: from a single GPU, to multiple GPUs on a machine, all the way to training on large clusters. Our innovations cut across the systems stack: memory management, structuring parallel computation across GPUs and machines, speeding up communication between accelerators and across machines, optimizing the data ingest and output pipelines, and schedulers for DNN training on large multi-tenant clusters.  In this talk, I'll give you an overview of Project Fiddle and focus on a couple of recent ideas to speed up data loading (input) and checkpointing (output).

**Dr. Amar Phanisayee** is Sr. Principal Researcher at Microsoft Research in Redmond. The goal of his research is to enable the creation of high-performance and efficient networked systems for large-scale data-intensive computing. His research efforts center around radically rethinking the design of datacenter-based systems: from infrastructure for compute, storage, and networking to distributed systems and protocols that are scalable, robust to failures, and use resources efficiently. His recent focus has been on leading Project Fiddle at MSR (Project Fiddle - Microsoft Research).  Amar received his Ph.D. in Computer Science from Carnegie Mellon University in 2012. His research work has been recognized by awards such as the ACM SOSP Best Paper Award and Carnegie Mellon's Allen Newell Award for Research Excellence.
