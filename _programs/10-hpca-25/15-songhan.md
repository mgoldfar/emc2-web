---
edition: hpca-25
type: invited_talk
time_start: 2025-03-02 10:15:00
time_end: 2025-03-02 11:00:00
title: "Efficient Large Language Models and Generative AI"
speaker:
    name: Song Han 
    affiliation: MIT
    avatar: songhan.jpg  
    url: https://hanlab.mit.edu/songhan

presentation: 
---
The rapid advancement of generative AI, particularly large language models (LLMs), presents unprecedented computational challenges. The autoregressive nature of LLMs makes inference memory bounded. Generating long sequences further compounds the memory demand. I will present efficiency optimization techniques including quantization (SmoothQuant, AWQ, SVDQuant) and KV cache optimization (StreamingLLM, QUEST, DuoAttention), followed by efficient model architectures—HART, a hybrid autoregressive transformer for efficient visual generation, and SANA, an efficient diffusion model deployable on the edge.
