---
edition: hpca-25
type: invited_talk
time_start: 2025-03-02 11:00:00
time_end: 2025-03-02 11:30:00
title: "ML Workloads in AR/VR and Their Implications to the ML System Design"
speaker:
    name: Hyoukjun Kwon 
    affiliation: UC Irvine
    avatar: hyoukjun.jpg  
    url: https://hyoukjunkwon.com

presentation: 
---
Augmented and virtual reality (AR/VR) combines many machine learning (ML) models to implement complex applications. Unlike traditional ML workloads, those in AR/VR involve (1) multiple concurrent ML pipelines (cascaded ML models with control/data dependencies), (2) highly heterogeneous modality and corresponding model structures, and (3) heavy dynamic behavior based on the user context and inputs. In addition, AR/VR requires a (4) real-time execution of those ML workloads on (5) energy-constrained wearable form-factor devices. All together, it creates significant challenges to the ML system design targeting for AR/VR.
In this talk, I will first demystify the ML workloads in AR/VR via a recent open benchmark, XRBench, which was developed with industry collaborators at Meta to reflect real use cases. Using the workloads, I will list the challenges and implications of the AR/VR ML workloads to ML system designs. Based on that, I will present hardware and software system design examples tailored for AR/VR ML workloads. Finally, I will discuss research opportunities in the AR/VR ML system design domain.
