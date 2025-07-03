---
title: "E2-AEN: End-to-End Incremental Learning with Adaptively Expandable Network"
collection: publications
category: manuscripts
permalink: /publication/2022-07-14-unpublish-arxiv-E2
excerpt: 'Guimei Cao, Zhanzhan Cheng*, Yunlu Xu, Duo Li, Shiliang Pu, Yi Niu, Fei Wu'
date: 2022-07-14
venue: 'Arxiv'
#slidesurl: 'http://academicpages.github.io/files/slides3.pdf'
paperurl: 'https://arxiv.org/pdf/2207.06754'
#citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---

Authors:
------
Guimei Cao, Zhanzhan Cheng*, Yunlu Xu, Duo Li, Shiliang Pu, Yi Niu, Fei Wu

Abstract:
------
Expandable networks have demonstrated their advantages in dealing with catastrophic forgetting problem in incremental learning. Considering that different tasks may need different structures, recent methods design dynamic structures adapted to different tasks via sophisticated skills. Their routine is to search expandable structures first and then train on the new tasks, which, however, breaks tasks into multiple training stages, leading to suboptimal or overmuch computational cost. In this paper, we propose an end-to-end trainable adaptively expandable network named E2-AEN, which dynamically generates lightweight structures for new tasks without any accuracy drop in previous tasks. Specifically, the network contains a serial of powerful feature adapters for augmenting the previously learned representations to new tasks, and avoiding task interference. These adapters are controlled via an adaptive gate-based pruning strategy which decides whether the expanded structures can be pruned, making the network structure dynamically changeable according to the complexity of the new tasks. Moreover, we introduce a novel sparsity-activation regularization to encourage the model to learn discriminative features with limited parameters. E2-AEN reduces cost and can be built upon any feed-forward architectures in an end-to-end manner. Extensive experiments on both classification (i.e., CIFAR and VDD) and detection (i.e., COCO, VOC and ICCV2021 SSLAD challenge) benchmarks demonstrate the effectiveness of the proposed method, which achieves the new remarkable results.

[Download Paper](https://arxiv.org/pdf/2207.06754)