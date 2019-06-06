---
edition: isca-19
type: invited_talk
time_start: 2019-06-23 15:30:00
time_end: 2019-06-23 16:30:00
title: Structured and Systematic Approach for Energy Efficient DNN Acceleration
speaker:
    name: Xuehai Qian
    affiliation: University of Southern California
    avatar: qian.jpg
    url: http://alchem.usc.edu/portal/index.html
---
Large-scale deep neural networks (DNNs) are both compute and memory internsive. As the size of DNNs continues to grow, it is critical to improve the energy efficiency and performance while maintaining accuracy. In this talk, I first present our principled approaches to performing model compression and acceleration using structured matrices. Compared to unstructured pruning, our methods (CirCNN and PermDNN) achieve significant model storage and computation reduction while maintaining accuracy. Thanks to the regular structure, the accelerators can achieve better performance and energy efficiency compared to the state-of-the-art designs. I will also present a unified solution framework for both unstructured and structured pruning and quantization based on Alternating Direction Method of Multipliers (ADMM). It ensures high solution quality while guaranteeing solution feasibility, consistently outperforming previous results. Finally, I will present HyPar, a systematic approach to search the best tensor partition for a given multi-layer DNN with an accelerator array. It optimizes performance and energy efficiency by reducing data movement between accelerators. We believe that the structured and systematic approach and algorithm/hardware co-design are crucial for designing energy efficient DNN accelerators.

**Xuehai Qian** is an assistnat professor at University of Southern California. His research interests include domain-specific system and architecture with focuses on machine learning and graph processing, performance tuning and resource management of Cloud systems, and parallel computer architecture. He got his Ph.D from University of Illinois Urbana Champaign and was a postdoc at UC Berkeley. He is the recipient of W.J Poppelbaum Memorial Award at UIUC, NSF CRII and CAREER Award, and the inaugural ACSIC (American Chinese Scholar In Computing) Rising Star Award.
