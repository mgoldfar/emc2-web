---
edition: asplos-24
time_start: 2024-04-27 14:00:00
time_end: 2024-04-27 15:00:00
type: keynote
title: "Efficient Multi-modal LLM"
speaker:
    name: Song Han
    affiliation: MIT, NVIDIA
    avatar: songhan.jpeg 
    url: https://songhan.mit.edu/

presentation:
---
<a href="https://github.com/NVIDIA/TensorRT-LLM">Slides</a> <a href="https://github.com/NVIDIA/TensorRT-LLM">Video</a> 
This talk presents efficient multi-modal LLM innovations and system implementations. I’ll first present <a href="https://hanlab.mit.edu/projects/vila">VILA</a>, a visual language model pre-training recipe beyond visual instruction tuning, enabling multi-image reasoning and in-context learning. Followed by <a href="https://hanlab.mit.edu/projects/smoothquant">SmoothQuant</a> and <a href="https://hanlab.mit.edu/projects/awq">AWQ</a> for LLM quantization, and the <a href="https://github.com/mit-han-lab/llm-awq/blob/main/tinychat/README.md">TinyChat</a> inference library. AWQ and TinyChat enable VILA 2.7B deployable on Jetson Orin Nano, bringing new opportunities for mobile vision applications. Second, I’ll present efficient representation learning, including <a href="https://hanlab.mit.edu/projects/efficientvit">EfficientViT</a> for high-resolution vision, accelerating SAM by 48x without performance loss; and condition-aware neural networks(<a href="https://hanlab.mit.edu/projects/can">CAN</a>), a novel way to add control to diffusion models. Third, I’ll present <a href="https://hanlab.mit.edu/projects/streamingllm">StreamingLLM</a>, a KV cache optimization technique for long conversation and <a href="https://hanlab.mit.edu/projects/longlora">LongLoRA</a>, using sparse, shifted attention for long-context LLM. Finally, I’ll present <a href="https://hanlab.mit.edu/projects/pockengine">PockEngine</a> for efficient LLM fine-tuning. Many of these techniques have been incorporated into NVIDIA's large language model optimization library, <a href="https://github.com/NVIDIA/TensorRT-LLM">TensorRT-LLM</a>.





