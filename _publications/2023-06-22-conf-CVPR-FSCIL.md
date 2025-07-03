---
title: "Few-Shot Class-Incremental Learning via Class-Aware Bilateral Distillation"
collection: publications
category: conferences
permalink: /publication/2023-06-22-conf-CVPR-FSCIL
excerpt: 'Linglan Zhao, Jing Lu, Yunlu Xu, Zhanzhan Cheng*, Dashan Guo, Yi Niu, Xiangzhong Fang'
date: 2023-06-22
venue: 'CVPR'
#slidesurl: 'http://academicpages.github.io/files/slides3.pdf'
paperurl: 'http://openaccess.thecvf.com/content/CVPR2023/papers/Zhao_Few-Shot_Class-Incremental_Learning_via_Class-Aware_Bilateral_Distillation_CVPR_2023_paper.pdf'
#citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---

Authors:
------
Linglan Zhao, Jing Lu, Yunlu Xu, Zhanzhan Cheng*, Dashan Guo, Yi Niu, Xiangzhong Fang

Abstract:
------
Few-Shot Class-Incremental Learning (FSCIL) aims to continually learn novel classes based on only few training samples, which poses a more challenging task than the well-studied Class-Incremental Learning (CIL) due to data scarcity. While knowledge distillation, a prevailing technique in CIL, can alleviate the catastrophic forgetting of older classes by regularizing outputs between current and previous model, it fails to consider the overfitting risk of novel classes in FSCIL. To adapt the powerful distillation technique for FSCIL, we propose a novel distillation structure, by taking the unique challenge of overfitting into account. Concretely, we draw knowledge from two complementary teachers. One is the model trained on abundant data from base classes that carries rich general knowledge, which can be leveraged for easing the overfitting of current novel classes. The other is the updated model from last incremental session that contains the adapted knowledge of previous novel classes, which is used for alleviating their forgetting. To combine the guidances, an adaptive strategy conditioned on the class-wise semantic similarities is introduced. Besides, for better preserving base class knowledge when accommodating novel concepts, we adopt a two-branch network with an attention-based aggregation module to dynamically merge predictions from two complementary branches. Extensive experiments on 3 popular FSCIL datasets: mini-ImageNet, CIFAR100 and CUB200 validate the effectiveness of our method by surpassing existing works by a significant margin.

[Download Paper](http://openaccess.thecvf.com/content/CVPR2023/papers/Zhao_Few-Shot_Class-Incremental_Learning_via_Class-Aware_Bilateral_Distillation_CVPR_2023_paper.pdf)