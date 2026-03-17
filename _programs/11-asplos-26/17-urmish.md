---
edition: asplos-26
type: invited_talk
time_start: 2026-03-22 17:30:00
time_end: 2026-03-22 18:00:00
title: "Making Long-Context LLM Inference Practical: Leveraging Token Importance for Efficient Inference"
speaker:
    name: Urmish Thakker
    affiliation: Ex-SambaNova Systems
    avatar: urmish.jpg
    url: https://urmish.github.io/
presentation:
---
As LLM context windows scale to hundreds of thousands or even millions of tokens, inference efficiency is increasingly limited by KV-cache memory growth and the high cost of prompt prefilling. Prior approaches attempt to mitigate these costs through heuristic cache eviction or prompt compression techniques, but often rely on architecture-specific assumptions or require retraining to recover accuracy. In this talk, I show that LLMs implicitly encode token importance signals that reveal which parts of context matter most for downstream computation. By exploiting these signals, it is possible to selectively retain or process only the most relevant tokens, significantly improving both decoding throughput and prefill throughput while preserving model quality in long-context inference.
