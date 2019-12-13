---
edition: neurips-19
type: invited_talk
time_start: 2019-12-13 16:45:00
time_end: 2019-12-13 17:15:00
title: Adaptive Multi-Task Neural Networks for Efficient Inference
speaker:
    name: Rogerio Feris 
    affiliation: IBM Research
    avatar: feris.jpg
    url: http://rogerioferis.com/
---
Very deep convolutional neural networks have shown remarkable success in many computer vision tasks, yet their computational expense limits their impact in domains where fast inference is essential. While there has been significant progress on model compression and acceleration, most methods rely on a one-size-fits-all network, where the same set of features is extracted for all images or tasks, no matter their complexity. In this talk, I will first describe an approach called BlockDrop, which learns to dynamically choose which layers of a deep network to execute during inference, depending on the image complexity, so as to best reduce total computation without degrading prediction accuracy. Then, I will show how this approach can be extended to design compact multi-task networks, where a different set of layers is executed depending on the task complexity, and the level of feature sharing across tasks is automatically determined to maximize both the accuracy and efficiency of the model. Finally, I will conclude the talk presenting an efficient multi-scale neural network model, which achieves state-of-the art results in terms of accuracy and FLOPS reduction on standard benchmarks such as the ImageNet dataset.

**Rogerio Schmidt Feris** is the head of computer vision and multimedia research at IBM T.J. Watson Research Center. He joined IBM in 2006 after receiving a Ph.D. from the University of California, Santa Barbara. He has also worked as an Affiliate Associate Professor at the University of Washington and as an Adjunct Associate Professor at Columbia University. His work has not only been published in top AI conferences, but has also been integrated into multiple IBM products, including Watson Visual Recognition, Watson Media, and Intelligent Video Analytics. He currently serves as an Associate Editor of TPAMI, has served as a Program Chair of WACV 2017, and as an Area Chair of conferences such as NeurIPS, CVPR, and ICCV. 