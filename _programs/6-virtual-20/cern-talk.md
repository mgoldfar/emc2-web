---
edition: virtual-20
type: invited_talk
time_start: 2020-12-05 14:35:00
time_end: 2020-12-05 15:15:00
title: "Designing Nanosecond Inference Engines for the Particle Collider"
speaker:
    name: Clauidonor N. Coelho Jr (Palo Alto Networks),
          Thea Aarrestad (CERN),
          Vladimir Loncar (CERN),
          Maurizio Pierini (CERN),
          Adrian Alan Pol (CERN),
          Sioni Summers (CERN),
          Jennifer Ngadiuba 
    affiliation: (Caltech)
    avatar: coelhoc.jpg
    url: 
presentation: 
---
While the quest for more accurate solutions is pushing deep learning research towards larger and more complex algorithms, edge devices with hard real-time constraints demand very efficient inference engines, e.g. with the reduction in model size, speed and energy consumption.  In this talk, we introduce a novel method for designing heterogeneously quantized versions of deep neural network models for minimum-energy, high-accuracy, nanosecond inference and fully automated deployment on chip. Our technique combines AutoML and QKeras (which is called AutoQKeras), combining layer hyperparameter selection and quantization optimization.  Users can select among several optimization strategies, such as global optimization of network hyperparameters and quantizers, or splitting the optimization problems into smaller search problems to cope with search complexity. We have applied this design technique for the event selection procedure in proton-proton collisions at the CERN Large Hadron Collider, where resources are strictly limited and latency of O(1) us is required. Nanosecond inference and a resource consumption reduced by a factor of 50 when implemented on FPGA hardware are achieved.  

 
