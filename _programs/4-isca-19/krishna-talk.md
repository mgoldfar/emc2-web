---
edition: isca-19
type: invited_talk
time_start: 2019-06-23 11:10:00
time_end: 2019-06-23 12:00:00
title: Enabling Continuous Learning through Synaptic Plasticity in Hardware
speaker:
    name: Tushar Krishna
    affiliation: Georgia Institue of Technology
    url: https://tusharkrishna.ece.gatech.edu
    avatar: krishna.jpg
---
Ever since modern computers were invented, the dream of creating artificial intelligence (AI) has captivated humanity. We are fortunate to live in an era when, thanks to deep learning (DL), computer programs have paralleled, and in many cases even surpassed human level accuracy in tasks like visual perception and speech synthesis. However, we are still far away from realizing general-purpose AI. The problem lies in the fact that the development of supervised learning based DL solutions today is mostly open loop.  A typical DL model is created by hand-tuning the deep neural network (DNN) topology by a team of experts over multiple iterations, followed by training over petabytes of labeled data. Once trained, the DNN provides high accuracy for the task at hand; if the task changes, however, the DNN model needs to be re-designed and re-trained before it can be deployed. A general-purpose AI system, in contrast, needs to have the ability to constantly interact with the environment and learn by adding and removing connections within the DNN autonomously, just like our brain does. This is known as synaptic plasticity.

In this talk we present our research efforts towards enabling general-purpose AI. First, we present GeneSys (MICRO 2018), a HW-SW prototype of a closed loop learning system for continuously evolving the structure and weights of a DNN for the task at hand using genetic algorithms, providing 100-10000x higher performance and energy-efficiency over state-of-the-art embedded and desktop CPU and GPU systems. Next, we present a DNN accelerator substrate called MAERI (ASPLOS 2018), built using light-weight, non-blocking, reconfigurable interconnects, that supports efficient mapping of regular and irregular DNNs with arbitrary dataflows, providing ~100% utilization of all compute units, resulting in 3X speedup and energy-efficiency over state-of-the-art DNN accelerators.

**Tushar Krishna** is an Assistant Professor in the School of Electrical and Computer Engineering at Georgia Tech. He has a Ph.D. in Electrical Engineering and Computer Science from MIT (2014), a M.S.E in Electrical Engineering from Princeton University (2009), and a B.Tech in Electrical Engineering from the Indian Institute of Technology (IIT) Delhi (2007). Before joining Georgia Tech in 2015, Dr. Krishna spent a year as a post-doctoral researcher at Intel, Massachusetts.

Dr. Krishna’s research spans computer architecture, interconnection networks, networks-on-chip (NoC) and deep learning accelerators - with a focus on optimizing data movement in modern computing systems. He has 42 publications in leading conferences and journals, which have amassed over 5000 citations to date. Three of his papers have been selected for IEEE Micro’s Top Picks from Computer Architecture, one more received an honorable mention, and two have won best paper awards. He has received the National Science Foundation (NSF) CRII award, a Google Faculty Award, and a Facebook Faculty Award.
