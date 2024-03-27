---
edition: asplos-24
time_start: 2024-04-27 13:30:00
time_end: 2024-04-27 14:30:00
type: keynote
title: "Efficient Multi-modal LLM"
speaker:
    name: Song Han
    affiliation: MIT, NVIDIA
    avatar: songhan.jpeg 
    url: https://songhan.mit.edu/

presentation: 
This talk presents efficient multi-modal LLM innovations and system implementations. I’ll first present VILA, a visual language model pre-training recipe beyond visual instruction tuning, enabling multi-image reasoning and in-context learning. Followed by SmoothQuant and AWQ for LLM quantization, and the TinyChat inference library.  AWQ and TinyChat enable VILA 2.7B deployable on Jetson Orin Nano, bringing new opportunities for mobile vision applications. Second, I’ll present efficient representation learning, including EfficientViT for high-resolution vision, accelerating SAM by 48x without performance loss; and condition-aware neural networks, a novel way to add control to diffusion models. Third, I’ll present StreamingLLM, a KV cache optimization technique for long conversation and LongLoRA, using sparse, shifted attention for long-context LLM. Finally, I’ll present PockEngine for efficient LLM fine-tuning. Many of these techniques have been incorporated into NVIDIA's large language model optimization library, TensorRT-LLM.
---


