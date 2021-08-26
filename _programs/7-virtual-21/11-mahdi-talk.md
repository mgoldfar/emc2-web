---
edition: virtual-21
type: invited_talk
time_start: 2021-08-28 15:15:00
time_end: 2021-08-28 16:00:00
title: "Memory Bandwidth Optimizations -- from Data Structure to Memory Array"
speaker:
    name: Mahdi Nazm Bojnordi 
    affiliation: Qualcomm Inc.
    avatar: mahdin.jpg 
    url: https://www.linkedin.com/in/mahdi-nazm-bojnordi-92776633/

presentation: 
---
As the demand for video and machine learning workloads increases, the memory bandwidth wall, and data movement problems escalate in all forms of computing systems--from edge devices and mobile nodes to data centers. Despite the recent technological enhancements in memory systems, the emerging data-intensive applications (e.g., point clouds and ML workloads) are still bottlenecked by the limited bandwidth and energy-efficiency of today's memory hierarchies. This talk examines a few examples of our architectural solutions to efficient data processing. First, we introduce a novel data structure based on geometric arrays (G-Arrays) that allow fast and energy-efficient point cloud processing in a compressed format. In addition to a 50% reduction in memory footprint, the proposed G-Arrays format achieves a significant speedup over the state-of-the-art PCL and MPEG libraries for point operations such as kNN search, point merge, and projection. Next, we examine a novel mechanism for index-independent data ranking in memory. The proposed algorithm is capable of eliminating all pairwise comparisons for data ranking, thereby reducing the memory bandwidth significantly. When applied to off-chip non-volatile memory arrays, the proposed mechanism achieves two orders of magnitude performance gains, and 90% energy reduction compared to the existing methods.

**Dr. Mahdi Nazm Bojnordi** is an Assistant Professor of the School of Computing at the University of Utah. He received his Ph.D. degree from the University of Rochester, Rochester, NY, USA, in 2016 in electrical and computer engineering. Currently, he leads the Unconventional Computer Architecture Laboratory (UCAL) at the School of Computing, University of Utah. Recently, his research interests have included energy-efficient architectures, low-power memory systems, and the application of emerging memory technologies to computer systems. Professor Bojnordi’s research has been recognized by two IEEE Micro Top Picks Awards, an HPCA 2016 Distinguished Paper Award, and a Samsung Best Paper Award.

