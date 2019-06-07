---
edition: cvpr-19
type: invited_talk
time_start: 2019-06-16 10:50:00
time_end: 2019-06-16 11:40:00
title: What Can In-memory Computing Deliver, and What Are the Barriers?
speaker:
    name: Naveen Verma
    affiliation: Princeton University
    avatar: verma.jpg
    url: http://ee.princeton.edu/people/faculty/naveen-verma
---
Inference based on deep-learning models is being employed pervasively in applications today. In many such applications, state-of-the-art models can easily push the platforms to their limits of performance and energy efficiency. To address this, digital acceleration has been widely exploited. But, deep-learning computations exhibit critical attributes that limit the gains achievable by traditional digital acceleration. In particular, computations are dominated by high-dimensionality matrix-vector multiplications (MVMs), where the precision requirements of elements have been reducing (from FP32 a few years ago, to INT8/4/2 now and in the future). In this scenario, in-memory computing (IMC) offers distinct advantages, which have been demonstrated through recent prototypes leading to roughly 10x higher energy efficiency and area-normalized throughput, compared to optimized digital accelerators. This arises from the structural alignment of dense 2D memory arrays with the dataflow of MVMs. While digital spatial architectures (e.g., systolic arrays) also exploit such alignment, IMC can do so more aggressively, minimizing data movement and amortizing compute into highly-efficient, highly-parallel analog operations. But, IMC also raises critical challenges, at each level (need for analog compute at circuit level, need for high bandwidth hardware infrastructure at architectural level, constrained configurability/virtualization at the software-mapping level). Recent research advances have shown remarkable promise in addressing many of these challenges, making IMC more of a reality than ever. These advances, their potential implications, and key questions remaining will be reviewed.

**Naveen Verma** received the B.A.Sc. degree in Electrical and Computer Engineering from the UBC, Vancouver, Canada in 2003, and the M.S. and Ph.D. degrees in Electrical Engineering from MIT in 2005 and 2009 respectively. Since July 2009 he has been a faculty member at Princeton University. His research focuses on advanced sensing systems, exploring how systems for learning, inference, and action planning can be enhanced by algorithms that exploit new sensing and computing technologies. This includes research on large-area, flexible sensors, energy-efficient statistical-computing architectures and circuits, and machine-learning and statistical-signal-processing algorithms. Prof. Verma has served as a Distinguished Lecturer of the IEEE Solid-State Circuits Society, and currently serves on the technical program committees for ISSCC, VLSI Symp., DATE, and IEEE Signal-Processing Society (DISPS).
