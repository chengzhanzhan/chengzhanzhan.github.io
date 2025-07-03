---
title: "STEP: Out-of-Distribution Detection in the Presence of Limited In-distribution Labeled Data"
collection: publications
category: conferences
permalink: /publication/2021-12-06-conf-NeurIPS-STEP
excerpt: 'Zhi Zhou, Lan-Zhe Guo, Zhanzhan Cheng+, Yu-Feng Li, Shiliang Pu'
date: 2021-12-06
venue: 'NeurIPS'
#slidesurl: 'http://academicpages.github.io/files/slides3.pdf'
paperurl: 'https://proceedings.neurips.cc/paper/2021/file/f4334c131c781e2a6f0a5e34814c8147-Paper.pdf'
#citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---

Authors:
------
Zhi Zhou, Lan-Zhe Guo, Zhanzhan Cheng+, Yu-Feng Li, Shiliang Pu

Abstract:
------
Existing semi-supervised learning (SSL) studies typically assume that unlabeled and test data are drawn from the same distribution as labeled data. However, in many real-world applications, it is desirable to have SSL algorithms that not only classify the samples drawn from the same distribution of labeled data but also detect out-of-distribution (OOD) samples drawn from an unknown distribution. In this paper, we study a setting called semi-supervised OOD detection. Two main challenges compared with previous OOD detection settings are i) the lack of labeled data and in-distribution data; ii) OOD samples could be unseen during training. Efforts on this direction remain limited. In this paper, we present an approach STEP significantly improving OOD detection performance by introducing a new technique: Structure-Keep Unzipping. It learns a new representation space in which OOD samples could be separated well. An efficient optimization algorithm is derived to solve the objective. Comprehensive experiments across various OOD detection benchmarks clearly show that our STEP approach outperforms other methods by a large margin and achieves remarkable detection performance on several benchmarks.

[Download Paper](https://proceedings.neurips.cc/paper/2021/file/f4334c131c781e2a6f0a5e34814c8147-Paper.pdf)