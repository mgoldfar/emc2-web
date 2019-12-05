---
edition: neurips-19
type: invited_talk
time_start: 2019-12-13 11:00:00
time_end: 2019-12-13 11:30:00
title: 'Hardware-aware Neural Architecture Design for Small and Fast Models: from 2D to 3D'
speaker:
    name: Song Han
    affiliation: MIT
    avatar: han.jpg
    url: https://songhan.mit.edu
---
Efficient deep learning computing requires algorithm and hardware co-design to enable specialization. However, the extra degree of freedom creates a much larger design space. We propose AutoML techniques to architect efficient neural networks. We investigate automatically designing small and fast models ([ProxylessNAS](https://arxiv.org/pdf/1812.00332.pdf)), auto channel pruning ([AMC](https://arxiv.org/pdf/1802.03494.pdf)), and auto mixed-precision quantization ([HAQ](https://arxiv.org/pdf/1811.08886.pdf)). We demonstrate such learning-based, automated design achieves superior performance and efficiency than rule-based human design. Moreover, we shorten the design cycle by 200× than previous work to efficiently search efficient models, so that we can afford to design specialized neural network models for different hardware platforms. We accelerate computation-intensive AI applications including ([TSM](https://arxiv.org/pdf/1811.08383.pdf)) for efficient video recognition and [PVCNN](https://arxiv.org/pdf/1907.03739.pdf) for efficient 3D recognition on point clouds. Finally, we’ll describe scalable distributed training and the potential security issues of efficient deep learning [[1]](https://arxiv.org/pdf/1906.08935.pdf) [[2]](https://arxiv.org/pdf/1904.08444.pdf)

**Song Han** is an assistant professor at MIT EECS. Dr. Han received the Ph.D. degree in Electrical Engineering from Stanford advised by Prof. Bill Dally. Dr. Han's research focuses on efficient deep learning computing. He proposed “Deep Compression” and “ EIE Accelerator" that impacted the industry. His work received the best paper award in ICLR'16 and FPGA’17. He was the co-founder and chief scientist of DeePhi Tech which was acquired by Xilinx.