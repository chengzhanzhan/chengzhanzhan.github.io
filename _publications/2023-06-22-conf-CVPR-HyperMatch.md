---
title: " HyperMatch: Noise-Tolerant Semi-Supervised Learning via Relaxed Contrastive Constraint"
collection: publications
category: conferences
permalink: /publication/2023-06-22-conf-CVPR-HyperMatch
excerpt: 'Beitong Zhou, Jing Lu, Kerui Liu, Yunlu Xu, Zhanzhan Cheng*, Yi Niu'
date: 2023-06-22
venue: 'CVPR'
#slidesurl: 'http://academicpages.github.io/files/slides3.pdf'
paperurl: 'http://openaccess.thecvf.com/content/CVPR2023/papers/Zhou_HyperMatch_Noise-Tolerant_Semi-Supervised_Learning_via_Relaxed_Contrastive_Constraint_CVPR_2023_paper.pdf'
#citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---

Authors:
------
Beitong Zhou, Jing Lu, Kerui Liu, Yunlu Xu, Zhanzhan Cheng*, Yi Niu

Abstract:
------
Recent developments of the application of Contrastive Learning in Semi-Supervised Learning (SSL) have demonstrated significant advancements, as a result of its exceptional ability to learn class-aware cluster representations and the full exploitation of massive unlabeled data. However, mismatched instance pairs caused by inaccurate pseudo labels would assign an unlabeled instance to the incorrect class in feature space, hence exacerbating SSL's renowned confirmation bias. To address this issue, we introduced a novel SSL approach, HyperMatch, which is a plug-in to several SSL designs enabling noise-tolerant utilization of unlabeled data. In particular, confidence predictions are combined with semantic similarities to generate a more objective class distribution, followed by a Gaussian Mixture Model to divide pseudo labels into a'confident'and a'less confident'subset. Then, we introduce Relaxed Contrastive Loss by assigning the'less-confident'samples to a hyper-class, ie the union of top-K nearest classes, which effectively regularizes the interference of incorrect pseudo labels and even increases the probability of pulling a'less confident'sample close to its true class. Experiments and in-depth studies demonstrate that HyperMatch delivers remarkable state-of-the-art performance, outperforming FixMatch on CIFAR100 with 400 and 2500 labeled samples by 11.86% and 4.88%, respectively.

[Download Paper](http://openaccess.thecvf.com/content/CVPR2023/papers/Zhou_HyperMatch_Noise-Tolerant_Semi-Supervised_Learning_via_Relaxed_Contrastive_Constraint_CVPR_2023_paper.pdf)