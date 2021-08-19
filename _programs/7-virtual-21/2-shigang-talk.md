---
edition: virtual-21
type: invited_talk
time_start: 2021-08-28 8:15:00
time_end: 2021-08-28 9:00:00
title: "Chimera: Efficiently Training Large-Scale Neural Networks with Bidirectional Pipelines"
speaker:
    name: Shigang Li 
    affiliation: Department of Computer Sc, ETH Zurich
    avatar: shigangl.jpg 
    url: https://shigangli.github.io/

presentation: 
---
Training large deep learning models at scale is very challenging. We proposes Chimera, a novel pipeline parallelism scheme which combines bidirectional pipelines for efficiently training large-scale models. Chimera is a synchronous approach and therefore no loss of accuracy, which is more convergence-friendly than asynchronous approaches. Compared with the latest synchronous pipeline approach, Chimera reduces the number of bubbles by up to 50%; benefiting from the sophisticated scheduling of bidirectional pipelines, Chimera has a more balanced activation memory consumption. Evaluations are conducted on Transformer based language models. For a GPT-2 model with 1.3 billion parameters running on 2,048 GPU nodes of the Piz Daint supercomputer, Chimera improves the training throughput by 1.16x-2.34x over the state-of-the-art synchronous and asynchronous pipeline approaches.

**Dr. Shigang Li** is currently a Postdoctoral Researcher in Department of Computer Science, ETH Zurich. His research interests include parallel computing, high performance computing, and parallel and distributed deep learning systems. He received the Bachelor's degree majored in Computer Science and the Ph.D degree majored in Computer Architecture from University of Science and Technology Beijing, in 2009 and 2014, respectively. He has been a joint Ph.D student in Department of Computer Science, University of Illinois at Urbana-Champaign from Sep. 2011 to Sep. 2013. He has been an Assistant Professor in State Key Laboratory of Computer Architecture, Institute of Computing Technology, Chinese Academy of Sciences from June 2014 to Aug. 2018. He got the Best Paper Nominations in SC'21, PPoPP'20 and HPDC'13, and Outstanding Paper of MLSys'21.
