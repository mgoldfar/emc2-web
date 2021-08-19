---
edition: virtual-21
type: invited_talk
time_start: 2021-08-28 13:45:00
time_end: 2021-08-28 14:30:00
title: "Towards Best Possible Deep Learning Acceleration on the Edge – A Compression-Compilation Co-Design Framework"
speaker:
    name: Yanzhi Wang 
    affiliation: Northeastern University
    avatar: wang.jpg 
    url: https://web.northeastern.edu/yanzhiwang/
presentation: 
---
Mobile and embedded computing devices have become key carriers of deep learning to facilitate the widespread of machine intelligence. However, there is a widely recognized challenge to achieve real-time DNN inference on edge devices, due to the limited computation/storage resources on such devices. Model compression of DNNs, including weight pruning and weight quantization, has been investigated to overcome this challenge. However, current work on DNN compression suffer from the limitation that accuracy and hardware performance are somewhat conflicting goals difficult to satisfy simultaneously.
 
We present our recent work CoCoPIE, representing Compression-Compilation Codesign, to overcome this limitation towards the best possible DNN acceleration on edge devices. We propose novel fine-grained structured pruning schemes, including pattern-based pruning, block-based pruning, etc. They can simultaneously achieve high hardware performance (similar to filter/channel pruning) while maintaining zero accuracy loss, with the help of compiler, which is beyond the capability of prior work. Similarly, we present novel quantization scheme that achieves ultra-high hardware performance close to 2-bit weight quantization, with almost no accuracy loss. Through the CoCoPIE framework, we are able to achieve real-time on-device execution of a number of DNN tasks, including object detection, pose estimation, activity detection, speech recognition, just using an off-the-shelf mobile device, with up to 180X speedup compared with prior work. Our comprehensive demonstrations are at : https://www.youtube.com/channel/UCCKVDtg2eheRTEuqIJ5cD8A

**Dr. Yanzhi Wang** is currently an assistant professor at Dept. of ECE at Northeastern University, Boston, MA. He received the B.S. degree from Tsinghua University in 2009, and Ph.D. degree from University of Southern California in 2014. His research interests focus on model compression and platform-specific acceleration of deep learning applications. His research maintains the highest model compression rates on representative DNNs since 09/2018. His work on AQFP superconducting based DNN acceleration is by far the highest energy efficiency among all hardware devices. His recent research achievement, CoCoPIE, can achieve real-time performance on almost all deep learning applications using off-the-shelf mobile devices, outperforming competing frameworks by up to 180X acceleration.
 
His work has been published broadly in top conference and journal venues (e.g., ASPLOS, ISCA, MICRO, HPCA, PLDI, DAC, ICCAD, ICS, PACT, Mobicom, ISSCC, AAAI, ICML, CVPR, ICLR, IJCAI, ECCV, ICDM, ACM MM, FPGA, LCTES, CCS, VLDB, PACT, ICDCS, Infocom, C-ACM, JSSC, TComputer, TCAS-I, TCAD, TCAS-I, JSAC, TNNLS, etc.), and has been cited above 9,400 times. He has received six Best Paper and Top Paper Awards, has another 11 Best Paper Nominations and four Popular Paper Awards. He has received the U.S. Army Young Investigator Program Award (YIP), Massachusetts Acorn Innovation Award, IEEE TCSDM Early Career Award, Martin Essigman Excellence in Teaching Award, Ming Hsieh Scholar Award, and other research awards from Google, MathWorks, etc. Four of his former Ph.D./postdoc students become tenure track faculty at Univ. of Connecticut, Clemson University, and Texas A&M University, Corpse Christi, and Cleveland State University.
