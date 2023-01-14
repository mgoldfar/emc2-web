---
edition: aaai-23
type: invited_talk
time_start: 2023-02-14 15:00:00
time_end: 2023-02-14 15:30:00
title: "Hardware/Software Codesign to Accelerate Vision Transformers on FPGAs"
speaker:
    name: Zhenman Fang 
    affiliation: Simon Fraser University
    avatar: zhenman.jpg  
    url: http://www.sfu.ca/~zhenman/
presentation:
---
Recently, vision transformers (ViTs) are emerging with significantly improved accuracy in computer vision tasks, surpassing state-of-the-art convolutional neural networks. However, their sophisticated network architectures with high computation and memory costs have impeded their deployment on resource-constrained edge devices. In this talk, I will present hardware-efficient quantization and pruning techniques to accelerate ViTs on embedded FPGAs. First, I will present Auto-ViT-Acc [FPL 2022], an FPGA-aware ViT acceleration framework that automatically explores a mix of fixed-point and power-of-two quantization schemes to fully leverage heterogeneous FPGA on-chip resources while maximally retaining the model accuracy. Compared with the baseline floating-point FPGA accelerator, our accelerator achieves around 5.6× improvement on the frame rate on the AMD-Xilinx ZCU102 FPGA with 0.71% accuracy drop on ImageNet dataset for DeiT-base. Second, I will present HeatViT [HPCA 2023], a hardware-efficient image-adaptive token pruning framework (together with 8-bit quantization) for efficient yet accurate ViT acceleration on FPGAs. In HeatViT, we adopt an effective, hardware-efficient, and learnable head-evaluation token selector, which can be progressively inserted before transformer blocks to dynamically identify and consolidate the non-informative tokens from input images. Compared to existing ViT pruning studies, under a similar computation cost, HeatViT can achieve 0.7%∼8.9% higher accuracy for various widely used ViTs on the ImageNet dataset. Compared to the baseline hardware accelerator, our implementations of HeatViT on the AMD-Xilinx ZCU102 FPGA achieve 3.46×∼4.89× speedup with a trivial resource utilization overhead of 8%∼11% more DSPs and 5%∼8% more LUTs.

