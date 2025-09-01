---
layout: publication
sitemap: false
title: "Balance-aware Sequence Sampling Makes Multimodal Learning Better"
authors: Zhihao Guan, Qing-Yuan Jiang&#9768;, and Yang Yang.
pdf: IJCAI2025_BSS
image: IJCAI2025_BSS.jpg
slide: IJCAI2025_BSS_slide.pdf
display: Proceedings of the 34rd International Joint Conference on Artificial Intelligence
display_short: IJCAI
poster: IJCAI2025_BSS_Poster.pdf
year: 2025
multimodal: true
video: 
github: https://github.com/njustkmg/IJCAI25-BSS
abstract: "Multimodal learning (MML) is frequently hindered by modality imbalance, leading to suboptimal performance in real-world applications. To address this issue, existing approaches primarily focus on rebalancing MML from the perspective of optimization or architecture design. However, almost all existing methods ignore the impact of sample sequences, i.e., an inappropriate training order tends to trigger learning bias in the model, further exacerbating modality imbalance. In this paper, we propose Balance-aware Sequence Sampling (BSS) to enhance the robustness of MML. Specifically, we first define a multi-perspective measurer to evaluate the balance degree of each sample in terms of correlation and information criteria. Via this evaluation, we employ a heuristic scheduler based on curriculum learning (CL) that incrementally provides training subsets, progressing from balanced to imbalanced samples to alleviate the imbalance. Moreover, we propose a learning-based probabilistic sampling method to dynamically update the training sequence in a more fine-grained manner, further improving MML performance. Extensive experiments on widely used datasets demonstrate the superiority of our method compared with state-of-the-art (SOTA) baselines. The code is available at https://github.com/njustkmg/IJCAI25-BSS."
---
