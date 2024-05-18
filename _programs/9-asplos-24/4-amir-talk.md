---
edition: asplos-24
type: invited_talk
time_start: 2024-04-27 08:30:00
time_end: 2024-04-27 09:00:00
title: "Dense-and-Sparse Quantization Methods for Efficient LLM Serving"
speaker:
    name: Amir Gholami 
    affiliation: UC Berkeley
    avatar: amirg.jpg  
    url: http://amirgholami.org

presentation: 
---
<a href="">Slides</a> <a href="">Video</a><br>The availability of unprecedented unsupervised training data, along with neural scaling laws, has resulted in an unprecedented surge in model size and compute requirements for serving/training LLMs. However, the main performance bottleneck for serving these models is increasingly shifting to memory bandwidth rather than compute. While quantization has emerged as a promising solution by representing model weights with reduced precision, previous efforts have often resulted in notable performance degradation. To address this, I will discuss our on-going work on a new type of quantization scheme called dense-and-sparse quantization which enables lossless compression to ultra-low precisions of up to 2-bit, while achieving state-of-the-art accuracy. Dense-and-sparse quantization allows this by decomposing the parameters and KVCache values into two components: a sparse component that includes outliers and sensitive values in the network, along with a dense component which is amenable to low precision compression. This allows us to achieve lossless compression for model parameters down to 3 bits, as well as down to 2-bits for compressing KV Cache values enabling serving a LLaMA-7B model on a single A100 GPU even with a context length of 1M token length.

