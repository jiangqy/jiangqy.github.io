---
layout: publication
sitemap: false
title: "Learning to Rebalance Multi-Modal Optimization by Adaptively Masking Subnetworks"
authors: Yang Yang, Hongpeng Pan, Qing-Yuan Jiang, Yi Xu, and Jinhui Tang.
pdf: TPAMI2025_AMSS
image: TPAMI2025_AMSS.jpg
slide: 
display: IEEE Transactions on Pattern Analysis and Machine Intelligence
display_short: TPAMI
poster: 
year: 2025
multimodal: true
video: 
github: https://github.com/njustkmg/TPAMI-AMSS
abstract: "Multi-modal learning aims to enhance performance by unifying models from various modalities but often faces the “modality imbalance” problem in real data, leading to a bias towards dominant modalities and neglecting others, thereby limiting its overall effectiveness. To address this challenge, the core idea is to balance the optimization of each modality to achieve a joint optimum. Existing approaches often employ a modal-level control mechanism for adjusting the update of each modal parameter. However, such a global-wise updating mechanism ignores the different importance of each parameter. Inspired by subnetwork optimization, we explore a uniform sampling-based optimization strategy and find it more effective than global-wise updating. According to the findings, we further propose a novel importance sampling-based, element-wise joint optimization method, called Adaptively Mask Subnetworks Considering Modal Significance (AMSS). Specifically, we incorporate mutual information rates to determine the modal significance and employ non-uniform adaptive sampling to select foreground subnetworks from each modality for parameter updates, thereby rebalancing multi-modal learning. Additionally, we demonstrate the reliability of the AMSS strategy through convergence analysis. Building upon theoretical insights, we further enhance the multi-modal mask subnetwork strategy using unbiased estimation, referred to as AMSS+. Extensive experiments reveal the superiority of our approach over comparison methods."
---
