---
edition: aaai-23
type: invited_talk
time_start: 2023-02-14 14:00:00
time_end: 2023-02-14 14:30:00
title: "Neural Network Design and Training for Efficient On-Device Learning"
speaker:
    name: Tien-Ju Yang 
    affiliation: Google Research
    avatar: tienju.jpeg  
    url: https://www.linkedin.com/in/tienju

presentation: 
---

Edge devices generate a large amount of data that can be used to improve the performance of neural networks. However, the private nature of such data prevents them from being uploaded to servers and requires on-device learning. This presents a challenge pertaining to the tight resource budget associated with edge devices. To address this challenge, we will present approaches to neural network design and training in this talk. To design efficient network architectures that require low resources to train, we propose the hardware-aware neural architecture search algorithm, NetAdaptV2. NetAdaptV2 automatically and rapidly discovers an efficient network architecture in terms of the given metrics on the target hardware. It uses empirical measurements to guide the search so that no hardware knowledge is required. According to our experiments, NetAdaptV2 discovers network architectures with better accuracy-latency/accuracy-MAC trade-offs than related works and reduces the total search time by up to 5.8x on ImageNet. To improve the efficiency of training under the setting of federated learning, we propose the efficient training algorithm, Partial Variable Training (PVT). PVT reduces memory usage and communication cost by training only a small subset of variables on edge devices. With PVT, we show that network accuracy can be maintained by utilizing more local training steps and devices, which is favorable for federated learning involving a large population of devices. According to our experiments on state-of-the-art neural networks for speech recognition and two different datasets, PVT can reduce memory usage by up to 1.9x and communication cost by up to 593x while attaining comparable accuracy when compared with full network training.
