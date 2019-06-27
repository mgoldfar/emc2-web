---
edition: cvpr-19
type: invited_talk
time_start: 2019-06-16 10:00:00
time_end: 2019-06-16 10:50:00
title: Hardware Efficiency Aware Neural Architecture Search
speaker:
    name: Song Han
    affiliation: MIT
    avatar: han.jpg
    url: https://songhan.mit.edu
presentation: han-talk.pdf
---
Efficient deep learning computing requires algorithm and hardware co-design to enable specialization: we usually need to change the algorithm to reduce memory footprint and improve energy efficiency. However, the extra degree of freedom from the algorithm creates a much larger design space: it’s not only about designing the hardware but also about how to change the algorithm to best fit the hardware. Human engineers can hardly exhaust the design space by heuristics. It’s labor consuming and sub-optimal. We propose design automation techniques for efficient neural networks. We investigate automatically designing small and fast models (ProxylessNAS), auto channel pruning (AMC), and auto mixed-precision quantization (HAQ). We demonstrate such learning-based, automated design achieves superior performance and efficiency than rule-based human design. Moreover, we shorten the design cycle by 200× than previous work, so that we can afford to design specialized neural network models for different hardware platforms.

**Song Han** is an assistant professor at MIT EECS. Dr. Han received the Ph.D. degree in Electrical Engineering from Stanford advised by Prof. Bill Dally. Dr. Han's research focuses on efficient deep learning computing. He proposed “Deep Compression” and “EIE Accelerator" that impacted the industry. His work received the best paper award in ICLR'16 and FPGA’17. He is the co-founder and chief scientist of DeePhi Tech (a leading efficient deep learning solution provider), which was acquired by Xilinx in 2018. 
