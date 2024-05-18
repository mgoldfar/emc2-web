---
edition: asplos-24
type: invited_talk
time_start: 2024-04-27 09:00:00
time_end: 2024-04-27 09:30:00
title: "Hardware-aware Algorithms for Language Modeling"
speaker:
    name: Tri Dao 
    affiliation: Princeton University
    avatar: tridao.jpeg  
    url: https://tridao.me

presentation: 
---
<a href="">Slides</a> <a href="https://drive.google.com/file/d/19y9IXSWy_7Kk-HgntmM-NBG4Gu-OdjMW/view?usp=share_link">Video</a><br>Transformers are slow and memory-hungry on long sequences, since the time and memory complexity of self-attention are quadratic in sequence length. In the first half, we describe FlashAttention, a fast and memory-efficient exact attention algorithm. By making attention algorithms IO-aware (accounting for reads and writes between levels of GPU memory) FlashAttention is 4-8x faster than optimized baselines, enabling 4-16x longer context in Transformers and yielding higher quality models. We will also describe optimizations for long-context LLM inference, leading to 2-8x faster end-to-end inference time. In the second half, we focus on subquadratic-time architectures such structured state space models (SSMs). We identify that a key weakness of such models is their inability to perform content-based reasoning, and propose a selection mechanism to address this shortcoming. Though this change prevents the use of efficient convolutions, we design a hardware-aware parallel algorithm in recurrent mode. We integrate these selective SSMs into a simplified end-to-end neural network architecture without attention or even MLP blocks. The resulting Mamba architecture matches or exceeds the performance of strong modern Transformers on language modeling, validated at 1B and 3B scales on both pretraining and downstream evaluation, while enjoying 5x higher inference throughput and linear scaling in sequence length.
