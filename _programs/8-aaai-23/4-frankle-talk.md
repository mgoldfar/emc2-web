---
edition: aaai-23
type: invited_talk
time_start: 2023-02-14 10:20:00
time_end: 2023-02-14 10:55:00
title: "Faster Neural Network Training, Algorithmically"
speaker:
    name: Jonathan Frankle 
    affiliation: Mosaic ML
    avatar: frankle.jpg  
    url: http://www.jfrankle.com/

presentation: 
---

Training modern neural networks is time-consuming, expensive, and energy-intensive. As neural network architectures double in size every few months, it is difficult for researchers and businesses without immense budgets to keep up, especially as hardware improvements stagnate. In this talk, I will describe one approach for managing this challenge: changing the training algorithm itself. I will discuss how we have put this approach into practice at MosaicML, including the dozens of algorithmic changes we have studied (which are freely available open source), the science behind how these changes interact with each other (the composition problem), and how we evaluate whether these changes have been effective. I will also detail several surprises we have encountered and lessons we have learned along the way. In the months since we began this work, we have reduced the training times of standard computer vision models by 5-7x and standard language models by 2-3x on publicly available cloud instances, and we're just scratching the surface.