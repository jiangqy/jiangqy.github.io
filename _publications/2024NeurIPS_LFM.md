---
layout: publication
sitemap: false
title: "Facilitating Multimodal Classification via Dynamically Learning Modality Gap"
authors: Yang Yang, Fengqiang Wan, Qing-Yuan Jiang&#9768;, Yi Xu.
pdf: NeurIPS2024_LFM
image: NeurIPS2024_LFM.jpg
slide: NeurIPS2024_LFM_slide.pdf
display: Proceedings of the 38th Conference on Neural Information Processing Systems
display_short: NeurIPS
poster: NeurIPS2024_LFM_Poster.pdf
year: 2024
multimodal: true
video: https://www.bilibili.com/video/BV16GmfYdEWT/?spm_id_from=333.999.0.0&vd_source=4bf56fd239e8e4bb57f149a83770f878
github: https://github.com/njustkmg/NeurIPS24-LFM
abstract: "Multimodal learning falls into the trap of the optimization dilemma due to the modality imbalance phenomenon, leading to unsatisfactory performance in real applications. A core reason for modality imbalance is that the models of each modality converge at different rates. Many attempts naturally focus on adjusting learning procedures adaptively. Essentially, the reason why models converge at different rates is because the difficulty of fitting category labels is inconsistent for each modality during learning. From the perspective of fitting labels, we find that appropriate positive intervention label fitting can correct this difference in learning ability. By exploiting the ability of contrastive learning to intervene in the learning of category label fitting, we propose a novel multimodal learning approach that dynamically integrates unsupervised contrastive learning and supervised multimodal learning to address the modality imbalance problem. We find that a simple yet heuristic integration strategy can significantly alleviate the modality imbalance phenomenon. Moreover, we design a learning-based integration strategy to integrate two losses dynamically, further improving the performance. Experiments on widely used datasets demonstrate the superiority of our method compared with state-of-the-art (SOTA) multimodal learning approaches. The code is available at https://github.com/njustkmg/NeurIPS24-LFM."
---
