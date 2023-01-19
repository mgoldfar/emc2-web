---
edition: aaai-23
type: invited_talk
time_start: 2023-02-14 09:45:00
time_end: 2023-02-14 10:15:00
title: "Efficient transformers - From supercomputers to smartphones"
speaker:
    name: Torsten Hoefler 
    affiliation: ETH Zurich
    avatar: toersten.jpg  
    url: https://htor.inf.ethz.ch/

presentation: 
---

Billion-parameter artificial intelligence models have proven to show exceptional performance in a large variety of tasks ranging from natural language processing, computer vision, and image generation to mathematical reasoning and algorithm generation. Those models usually require large parallel computing systems, often called 'AI Supercomputers', to be trained initially. We will outline several techniques ranging from data ingestion, parallelization, to accelerator optimization that improve the efficiency of such training systems. Yet, training large models is only a small fraction of practical artificial intelligence computations. Efficient inference is even more challenging - models with hundreds-of-billions of parameters are expensive to use. We continue by discussing model compression and optimization techniques such as fine-grained sparsity as well as quantization to reduce model size and significantly improve efficiency during inference. These techniques may eventually enable inference with powerful models on hand-held devices.
