---
edition: virtual-20
type: invited_talk
time_start: 2020-12-05 11:35:00
time_end: 2020-12-05 12:10:00
title: "Modular Neural Networks for Low-Power Image Classification on Embedded Devices"
speaker:
    name: Yung-Hsiang Lu 
    affiliation: Purdue University
    avatar: yunglu.jpg 
    url: https://engineering.purdue.edu/HELPS/Faculty/yunglu.html
presentation: 
---
Embedded devices are generally small, battery-powered computers  with limited hardware resources. It is difficult to run Deep Neural Networks (DNNs) on these devices, because DNNs perform millions of operations, and consume significant amounts of energy. Prior research has shown that a considerable number of a DNN's memory accesses and computation is redundant when performing tasks like image classification. To reduce this redundancy and thereby reduce the energy consumption of DNNs, we introduce the Modular Neural Network-Tree (MNN-Tree) architecture. Instead of using one large DNN for the classifier, this architecture uses multiple smaller DNNs (called modules) to progressively classify images into groups of categories based on a novel visual similarity metric. Once a group of categories is selected by a module, another module then continues to distinguish among the similar categories within the selected group. This process is repeated over multiple modules until we are left with a single category. The computation needed to distinguish dissimilar groups is avoided, thus reducing redundant operations, memory accesses, and energy. Experimental results using several image datasets reveal the effectiveness of our proposed solution to reduce memory requirements by 50%-99%, inference time by 55%-95%, energy consumption by 52%-94%, and the number of operations by 15%-99% when compared with existing DNN architectures, running on two different embedded systems: Raspberry Pi 3 and Raspberry Pi Zero.  

**Dr. Yung-Hsiang Lu** is a professor at the School of Electrical and Computer Engineering at Purdue University, West Lafayette, Indiana, USA. He is the inaugural director of Purdue's John Martinson Entrepreneurship Center. He is a Distinguished Scientist of the ACM. He received the PhD. from Stanford University and BS from the National Taiwan University. Computing Reviews said, "If you land on a desert island that has a Linux computer, this is the one book to have with you." about his book "Intermediate C Programming" (CRC Press). 
