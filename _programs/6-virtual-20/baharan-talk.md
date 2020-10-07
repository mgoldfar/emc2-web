---
edition: virtual-20
type: invited_talk
time_start: 2020-12-05 11:00:00
time_end: 2020-12-05 12:00:00
title: Efficient Machine Learning via Data Summarization
speaker:
    name: Baharan Mirzasoleiman 
    affiliation: Computer Science, University of California, Los Angeles
    avatar: baharan.jpg
    url: http://web.cs.ucla.edu/~baharan/
presentation: 
---
Large datasets have been crucial to the success of modern machine learning models. However, training on massive data has two major limitations. First, it is contingent on exceptionally large and expensive computational resources, and incurs a substantial cost due to the significant energy consumption. Second, in many real-world applications such as medical diagnosis, self-driving cars, and fraud detection, big data contains highly imbalanced classes and noisy labels. In such cases, training on the entire data does not result in a high-quality model.  

In this talk, I will argue that we can address the above limitations by developing techniques that can identify and extract the representative subsets from massive datasets. Training on representative subsets not only reduces the substantial costs of learning from big data, but also improves their accuracy and robustness against noisy labels. I will present two key aspects to achieve this goal: (1) extracting the representative data points by summarizing massive datasets; and (2) developing efficient optimization methods to learn from the extracted summaries. I will discuss how we can develop theoretically rigorous techniques that provide strong guarantees for the quality of the extracted summaries, and the learned models’ quality and robustness against noisy labels. I will also show the applications of these techniques to several problems, including summarizing massive image collections, online video summarization, and speeding up training machine learning models.

**Baharan Mirzasoleiman** is Assistant Professor in Computer Science Department at UCLA. Her research focuses on developing new methods that enable efficient machine learning from massive datasets. More specifically, I am interested in designing techniques that can gain insights from the underlying data structure by utilizing complex and higher-order interactions between data points. The extracted information can be used to efficiently explore and robustly learn from datasets that are too large to be dealt with by traditional approaches. My methods have immediate application to high-impact problems where massive data volumes prohibit efficient learning and inference, such as huge image collections, recommender systems, Web and social services, video and other large data streams. Before joining UCLA, she was a postdoctoral research fellow in Computer Science at Stanford University working with Jure Leskovec. I received my Ph.D. in Computer Science from ETH Zurich advised by Andreas Krause. I received an ETH medal for Outstanding Doctoral Thesis, and was selected as a Rising Star in EECS by MIT. 