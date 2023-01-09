---
edition: aaai-23
time_start: 2023-02-14 14:00:00
time_end: 2023-02-14 15:00:00
type: keynote
title: "On-Device Training under 256KB Memory"
speaker:
    name: Song Han
    affiliation: MIT
    avatar: songhan.jpeg 
    url: https://songhan.mit.edu/

presentation: 
---
 On-device training enables the model to adapt to new data collected from the sensors. Users can benefit from customized AI models without having to transfer the data to the cloud, preserving privacy. However, the training memory footprint is prohibitive for IoT devices. I’ll present "Tiny Transfer Learning”(NeurIPS’20) and "On-Device Training Under 256KB Memory” (NeurIPS’22) to solve this issue.  I’ll first analyze the memory bottleneck, showing that we should reduce the activations, not just trainable parameters for efficient on-device learning. I’ll then introduce Quantization-Aware Scaling (QAS) to calibrate the gradient scales and stabilize 8-bit quantized training, and "sparse update" to skip the gradient computation of less important layers and sub-tensors to save activation memory. The algorithm innovation is implemented by a lightweight training system, Tiny Training Engine, which prunes the backward computation graph to support sparse updates and offload the runtime auto-differentiation to compile time. Deployed on STM32H746 microcontroller, our framework uses less than 1/1000 of the training memory of Tensorflow and Pytorch while matching the accuracy. Our study enables IoT devices to not only perform inference but also continuously adapt to new data for on-device lifelong learning.

