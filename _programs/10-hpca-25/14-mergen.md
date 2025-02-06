---
edition: hpca-25
type: invited_talk
time_start: 2025-03-02 09:30:00
time_end: 2025-03-02 10:00:00
title: "Inference at the Edge: Tackling the challenges of deploying large-scale models on-device."
speaker:
    name: Kimish Patel 
    affiliation: Meta
    avatar: kimish.jpg  
    url: https://www.linkedin.com/in/kimishpatel/

presentation: 
---
Advent of generative AI has resulted in increased engagement of AI capabilities ranging from use of diffusion models for creative work to leveraging mult-modal models for AI assistants. Form factors such as smart phones and wearables make privacy, latency, power and cost aware deployment of such capabilities possible, by leveraging on-chip AI accelerators for low-latency, energy efficient inference. However black-box nature of such accelerators makes them harder to leverage without significantly affecting developer efficiency of ML and production engineers. By providing native integration points to such accelerators, ExecuTorch framework enables deployment of PyTorch models on these platforms, while preserving ease of authoring, profiling and debugging that is native to PyTorch. In this talk, we provide an overview of the ExecuTorch stack and how it brings both ML developers and silicon vendors together to enable on-device AI, within the PyTorch native ecosystem.
