---
edition: aaai-23
time_start: 2023-02-14 8:45:00
time_end: 2023-02-14 9:45:00
type: keynote
title: "Efficient Learning in Single- and Multi-Modal Vision Transformers"
speaker:
    name: Diana Marculescu
    affiliation: UT Austin 
    avatar: diana.png 
    url: https://www.ece.utexas.edu/people/faculty/diana-marculescu

presentation: 
---
Transformers have revolutionized the way we approach reasoning and learning tasks in the field of computer vision, both in single and multi-modal settings. Self-supervised pre-training methods, such as the Masked Autoencoder (MAE), have emerged as a solution to maximize the potential of vision transformers, although MAE requires a large number of epochs to pre-train, making it expensive in practice. Our work introduces a supervised pre-training approach called SupMAE, which is more efficient, robust, and effective in transfer learning than MAE and other supervised pre-training methods. SupMAE achieves similar performance to MAE on ImageNet with the ViTB/16 model while using only 30% of the compute cost, and outperforms MAE on ImageNet variants. In addition, techniques have been developed to reduce the computational cost of vision transformers through post-training quantization, often using mixed precision schemes or partitioning the model. We propose CPT-V, a contrastive loss-based approach using block-based evolutionary search for quantization scales that results in 1.5% better accuracy for 3, 4, and 8-bit models in less time than existing methods. In the case of multi-modal tasks such as audio-video event localization, effective multi-modal feature correspondence is necessary to understand the various temporal interactions. Existing approaches struggle in this regard due to ineffective multi-modal training strategies. We introduce AVE-CLIP, a framework that combines AudioCLIP, a model pre-trained on large-scale audio-visual data, with a multi-window temporal transformer to effectively handle different temporal scales of video frames. AVE-CLIP improves performance on the AVE dataset by 5.9% compared to previous work, demonstrating its effectiveness in practice. Taken together, SupMAE, CPT-V, and AVE-CLIP demonstrate how to improve the efficiency and effectiveness of vision transformers in a variety of tasks.
