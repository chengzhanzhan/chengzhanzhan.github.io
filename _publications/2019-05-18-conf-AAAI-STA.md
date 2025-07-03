---
title: "Segregated Temporal Assembly Recurrent Networks for Weakly Supervised Multiple Action Detection"
collection: publications
category: conferences
permalink: /publication/2019-05-18-conf-AAAI-STA
excerpt: 'Yunlu Xu, Chengwei Zhang, Zhanzhan Cheng*, Jianwen Xie, Yi Niu, Shiliang Pu, Fei Wu'
date: 2019-05-18
venue: 'AAAI'
#slidesurl: 'http://academicpages.github.io/files/slides3.pdf'
paperurl: 'https://aaai.org/ojs/index.php/AAAI/article/download/4939/4812'
#citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---

Authors:
------
Yunlu Xu, Chengwei Zhang, Zhanzhan Cheng*, Jianwen Xie, Yi Niu, Shiliang Pu, Fei Wu

Abstract:
------
This paper proposes a segregated temporal assembly recurrent (STAR) network for weakly-supervised multiple action detection. The model learns from untrimmed videos with only supervision of video-level labels and makes prediction of intervals of multiple actions. Specifically, we first assemble video clips according to class labels by an attention mechanism that learns class-variable attention weights and thus helps the noise relieving from background or other actions. Secondly, we build temporal relationship between actions by feeding the assembled features into an enhanced recurrent neural network. Finally, we transform the output of recurrent neural network into the corresponding action distribution. In order to generate more precise temporal proposals, we design a score term called segregated temporal gradient-weighted class activation mapping (ST-GradCAM) fused with attention weights. Experiments on THUMOS’14 and ActivityNet1. 3 datasets show that our approach outperforms the state-of-theart weakly-supervised method, and performs at par with the fully-supervised counterparts.

[Download Paper](https://aaai.org/ojs/index.php/AAAI/article/download/4939/4812)