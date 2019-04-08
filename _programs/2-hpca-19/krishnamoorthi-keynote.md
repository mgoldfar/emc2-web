---
edition: hpca-19
type: keynote
time_start: 9:00
time_end: 10:00
title: Quantizing Deep Convolutional Networks for Efficient Inference
speaker:
    name: Raghuraman Krishnamoorthi
    affiliation: Facebook
    avatar: krishnamoorthi.jpg
---
Abstract

We present an overview of techniques for quantizing convolutional neural networks for inference with integer weights and activations. We discuss different quantization schemes and show that simple techniques provide very good performance (4x reduction in model size, 2x speed up in CPUs) for classification use cases, with 1-2% accuracy drop.

Modeling quantization during training can provide further improvements, reducing the gap to floating point to 1% at 8-bit precision. Quantization-aware training also allows for reducing the precision of weights to four bits with accuracy losses ranging from 2% to 10%, with higher accuracy drop for smaller networks.

We recommend that per-channel quantization of weights and per-layer quantization of activations be the preferred quantization scheme for hardware acceleration and kernel optimization. We also propose that future processors and hardware accelerators for optimized inference support:

   a) precisions of 4, 8 and 16 bits for computation
   b) Per-channel quantization of weights
   c) Per layer selection of bitwidths for weights and activations
   d) Support for on the fly weight compression techniques for memory bandwidth efficiency.

Speaker Bio

Raghuraman Krishnamoorthi is a software engineer in the Pytorch team at Facebook, where he leads the effort to develop and optimize quantized deep networks for inference. Prior to that he was part of the Tensorflow team at google working on quantization for mobile inference as part of TensorflowLite.

From 2001 to 2017, Raghu was at Qualcomm Research, working on several generations of wireless technologies. His work experience also includes computer vision for AR, ultra-low power always on vision and hardware/software co-design for inference on mobile platforms. He is an inventor in more than 90 issued and filed patents. Raghu has a masters in EE from University of Illinois,Urbana Champaign and a Bachelor degree from Indian Institute of Technology, Madras.