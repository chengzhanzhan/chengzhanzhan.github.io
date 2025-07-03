---
title: "Learning a Domain Classifier Bank for Unsupervised Adaptive Object Detection"
collection: publications
category: manuscripts
permalink: /publication/2020-07-06-unpublish-arxiv-Learning
excerpt: 'Sanli Tang, Zhanzhan Cheng*, Shiliang Pu, Dashan Guo, Yi Niu, Fei Wu'
date: 2020-07-06
venue: 'Arxiv'
#slidesurl: 'http://academicpages.github.io/files/slides3.pdf'
paperurl: 'https://arxiv.org/pdf/2207.06754'
#citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---

Authors:
------
Sanli Tang, Zhanzhan Cheng*, Shiliang Pu, Dashan Guo, Yi Niu, Fei Wu

Abstract:
------
In real applications, object detectors based on deep networks still face challenges of the large domain gap between the labeled training data and unlabeled testing data. To reduce the gap, recent techniques are proposed by aligning the image/instance-level features between source and unlabeled target domains. However, these methods suffer from the suboptimal problem mainly because of ignoring the category information of object instances. To tackle this issue, we develop a fine-grained domain alignment approach with a well-designed domain classifier bank that achieves the instance-level alignment respecting to their categories. Specifically, we first employ the mean teacher paradigm to generate pseudo labels for unlabeled samples. Then we implement the class-level domain classifiers and group them together, called domain classifier bank, in which each domain classifier is responsible for aligning features of a specific class. We assemble the bare object detector with the proposed fine-grained domain alignment mechanism as the adaptive detector, and optimize it with a developed crossed adaptive weighting mechanism. Extensive experiments on three popular transferring benchmarks demonstrate the effectiveness of our method and achieve the new remarkable state-of-the-arts.

[Download Paper](https://arxiv.org/pdf/2207.06754)