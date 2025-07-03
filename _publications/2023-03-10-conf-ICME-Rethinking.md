---
title: "Rethinking Self-Supervision for Few-Shot Class-Incremental Learning"
collection: publications
category: conferences
permalink: /publication/2023-03-10-conf-ICME-Rethinking
excerpt: 'Linglan Zhao, Jing Lu, Zhanzhan Cheng*, Duo Liu, Xiangzhong Fang'
date: 2023-07-10
venue: 'CVPR'
#slidesurl: 'http://academicpages.github.io/files/slides3.pdf'
paperurl: 'https://davar-lab.github.io/files/icme2023_fscil/ICME_2023_Camera_Ready.pdf'
#citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---

Authors:
------
Linglan Zhao, Jing Lu, Zhanzhan Cheng*, Duo Liu, Xiangzhong Fang

Abstract:
------
Few-Shot Class-Incremental Learning (FSCIL) focuses on progressively absorbing new concepts given only limited training data. For tackling this challenge, several recent FS-CIL works resort to pre-training models with Self-Supervised Learning (SSL) to obtain features that can generalize well to new classes. However, to avoid overfitting and catastrophic forgetting, previous works only leverage SSL in the base session and keep all or most parameters fixed in incremental sessions, resulting in inadequate adaptation to novel classes. Thus, in this paper, we explore the setting where more parameters can be updated for adapting to novel concepts, and discover that the model pre-trained with SSL leads to degraded performance even compared to that without SSL. It can be attributed to the severer forgetting of base class knowledge. To address this issue, we propose an imprinting-based distillation module for effectively regularizing the adaption process, and a mathematically provable routing strategy for further improved results. The effectiveness of our approach is verified on 3 popular FSCIL benchmarks by significantly outperforming previous methods.

[Download Paper](https://davar-lab.github.io/files/icme2023_fscil/ICME_2023_Camera_Ready.pdf)