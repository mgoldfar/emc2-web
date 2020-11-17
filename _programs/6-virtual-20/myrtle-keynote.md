---
edition: virtual-20
type: keynote
time_start: 2020-12-05 08:40:00
time_end: 2020-12-05 09:40:00
title: "Achieving Low-latency Speech Synthesis at Scale"
speaker:
    name: Sam Davis 
    affiliation: Myrtle.ai
    avatar: sam.jpg   
    url: https://myrtle.ai/company/#keystaff
presentation: 
---
Real-time text-to-speech models are widely deployed in interactive voice services such as voice assistants and smart speakers. However, deploying these models at scale is challenging due to the strict latency requirements that they face: one pass through the model must complete once every 62.5 microseconds to generate 16kHz audio. This talk will introduce these challenges through the WaveNet model, a state-of-the-art speech synthesis vocoder. It then discusses how this class of models can achieve high-throughput, low-latency inference at scale through the combination of three components: model compression, more suitable programming paradigms, and more efficient compute platforms.  

**Sam Davis**, Head of Machine Learning leads Myrtle.ai’s machine learning team to understand and develop efficient, state-of-the-art machine learning models. His interest and work focuses on the intersection of Conversational AI, model compression, and hardware design for machine learning inference. He chaired the MLPerf.org working group to develop the speech recognition benchmark that was released as part of the recent v0.7 inference round.  
