---
title: "Active Model Adaptation Under Unknown Shift"
collection: publications
category: conferences
permalink: /publication/2022-08-14-conf-KDD-Active
excerpt: 'Jie-Jing Shao, Yunlu Xu, Zhanzhan Cheng+, Yu-Feng Li'
date: 2022-08-14
venue: 'KDD'
#slidesurl: 'http://academicpages.github.io/files/slides3.pdf'
paperurl: 'https://arxiv.org/pdf/2207.06694'
#citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---

Authors:
------
Jie-Jing Shao, Yunlu Xu, Zhanzhan Cheng+, Yu-Feng Li

Abstract:
------
Successful machine learning typically relies on fixed data distribution. However, due to unforeseen situations in the open world, distribution shift often occurs in applications. For instance, in the image recognition task, an unpredictable distributional shift may occur due to changes in background or lighting. Furthermore, to alleviate the harm of distribution shift, the resource budget is not infinite and often constrained. To cope with such a novel problem Resource Constrained Adaptation under Unknown Shift, in this paper we study active model adaptation both theoretically and empirically. First, we present a generalization analysis of active model adaptation for distribution shift. In theory, we show that active model adaptation could improve the generalization error from O(1/N) to O(1/N), with only a few queried samples. Second, based on the theoretical analysis, we present a systemic solution Auto, consisting of three sub-steps, that is, distribution tracking, sample selection and model adaptation. Specifically, we design a shifted distribution detection module to locate the distributional shifted samples. To fit the labeling budget, we employ a core-set algorithm to enhance the informativeness of the selected samples. Finally, we update the model through the newly queried labeled data. We conduct empirical studies of nine existing active strategies on diverse real world data sets and the results show that Auto could remarkably outperform all the baselines.

[Download Paper](https://arxiv.org/pdf/2207.06694)