---
layout: publication
sitemap: false
title: "Towards Equilibrium: An Instantaneous Probe-and-Rebalance Multimodal Learning Approach"
authors: Yang Yang, Xixian Wu, and Qing-Yuan Jiang&#9768;.
pdf: IJCAI2025_IPRM
image: IJCAI2025_IPRM.jpg
slide: 
display: Proceedings of the 34rd International Joint Conference on Artificial Intelligence
display_short: IJCAI
poster: 
year: 2025
multimodal: true
video: 
github: https://github.com/njustkmg/IJCAI25-IPRM
abstract: "The multimodal imbalance problem has been extensively studied to prevent the undesirable scenario where multimodal performance falls below that of unimodal models. However, existing methods typically assess the strength of modalities and perform learning simultaneously under the imbalanced status. This deferred strategy fails to rebalance multimodal learning instantaneously, leading to performance degeneration. To address this, we propose a novel multimodal learning approach, termed instantaneous probe-and-rebalance multimodal learning (IPRM), which employs a two-pass forward method to first probe (but not learn) and then perform rebalanced learning under the balanced status. Concretely, we first employ the geodesic multimodal mixup (GMM) to incorporate fusion representation and probe modality strength in the first forward phase. Then the weights are instantaneously recalibrated based on the probed strength, facilitating balanced training via the second forward pass. This process is applied dynamically throughout the entire training process. Extensive experiments reveal that our proposed IPRM outperforms all baselines, achieving state-of-the-art (SOTA) performance on numerous widely used datasets. The code is available at https://github.com/njustkmg/IJCAI25-IPRM."
---
