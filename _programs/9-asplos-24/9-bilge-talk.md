---
edition: asplos-24
time_start: 2024-04-27 17:15:00
time_end: 2024-04-27 17:45:00
type: invited_talk
title: "CHAI: Clustered Head Attention for Efficient LLM Inference"
speaker:
    name: Bilge Acun
    affiliation: Meta
    avatar: bilge.jpeg 
    url: https://bilgeacun.github.io

presentation: 
---
<a href="">Slides</a> <a href="https://drive.google.com/file/d/1MSr2zbK6_5cd-qS-IieqE9SN3x7pYOn6/view?usp=share_link">Video</a><br>Large Language Models (LLMs) with hundreds of billions of parameters have transformed the field of machine learning. However, serving these models at inference time is both compute and memory intensive, where a single request can require multiple GPUs and tens of Gigabytes of memory. Multi-Head Attention is one of the key components of LLMs, which can account for over 50% of LLMs memory and compute requirement. We observe that there is a high amount of redundancy across heads on which tokens they pay attention to. Based on this insight, we propose Clustered Head Attention (CHAI). CHAI combines heads with a high amount of correlation for self-attention at runtime, thus reducing both memory and compute. In our experiments, we show that CHAI is able to reduce the memory requirements for storing K,V cache by up to 21.4% and inference time latency by up to 1.73x without any fine-tuning required. CHAI achieves this with a maximum 3.2% deviation in accuracy across 3 different models (i.e. OPT-66B, LLAMA-7B, LLAMA-33B) and 5 different evaluation datasets.
