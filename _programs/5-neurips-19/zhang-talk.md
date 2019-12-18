---
edition: neurips-19
type: invited_talk
time_start: 2019-12-13 15:15:00
time_end: 2019-12-13 15:45:00
title: Algorithm-Accelerator Co-Design for Neural Network Specialization
speaker:
    name: Zhiru Zhang
    affiliation: Cornell University
    avatar: zhang.jpg
    url: https://zhang.ece.cornell.edu
presentation: emc2-neurips19-zhang-talk.pdf
---
In recent years, machine learning (ML) with deep neural networks (DNNs) has been widely deployed in diverse application domains. However, the growing complexity of DNN models, the slowdown of technology scaling, and the proliferation of edge devices are driving a demand for higher DNN performance and energy efficiency. ML applications have shifted from general-purpose processors to dedicated hardware accelerators in both academic and commercial settings. In line with this trend, there has been an active body of research on both algorithms and hardware architectures for neural network specialization.

This talk presents our recent investigation into DNN optimization and low-precision quantization, using a co-design approach featuring contributions to both algorithms and hardware accelerators. First, we review static network pruning techniques and show a fundamental link between group convolutions and circulant matrices -- two previously disparate lines of research in DNN compression. Then we discuss channel gating, a dynamic, fine-grained, and trainable technique for DNN acceleration. Unlike static approaches, channel gating exploits input-dependent dynamic sparsity at run time. This results in a significant reduction in compute cost with a minimal impact on accuracy. Finally, we present outlier channel splitting, a technique to improve DNN weight quantization by removing outliers from the weight distribution without retraining.

**Zhiru Zhang** is an Associate Professor in the School of ECE at Cornell University. His current research investigates new algorithms, design methodologies, and automation tools for heterogeneous computing. His research has been recognized with a Google Faculty Research Award (2018), the DAC Under-40 Innovators Award (2018), the Rising Professional Achievement Award from the UCLA Henry Samueli School of Engineering and Applied Science (2018), a DARPA Young Faculty Award (2015), and the IEEE CEDA Ernest S. Kuh Early Career Award (2015), an NSF CAREER Award (2015), the Ross Freeman Award for Technical Innovation from Xilinx (2012), and multiple best paper awards and nominations. Prior to joining Cornell, he was a co-founder of AutoESL, a high-level synthesis start-up later acquired by Xilinx.