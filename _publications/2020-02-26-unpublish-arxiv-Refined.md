---
title: "Refined Gate: A Simple and Effective Gating Mechanism for Recurrent Units"
collection: publications
category: manuscripts
permalink: /publication/2020-02-26-unpublish-arxiv-Refined
excerpt: 'Zhanzhan Cheng, Yunlu Xu, Mingjian Cheng, Yu Qiao, Shiliang Pu, Yi Niu, Fei Wu'
date: 2020-02-26
venue: 'Arxiv'
#slidesurl: 'http://academicpages.github.io/files/slides3.pdf'
paperurl: 'https://arxiv.org/pdf/2002.11338'
#citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---

Authors:
------
Zhanzhan Cheng, Yunlu Xu, Mingjian Cheng, Yu Qiao, Shiliang Pu, Yi Niu, Fei Wu

Abstract:
------
Recurrent neural network (RNN) has been widely studied in sequence learning tasks, while the mainstream models (e.g., LSTM and GRU) rely on the gating mechanism (in control of how information flows between hidden states). However, the vanilla gates in RNN (e.g., the input gate in LSTM) suffer from the problem of gate undertraining, which can be caused by various factors, such as the saturating activation functions, the gate layouts (e.g., the gate number and gating functions), or even the suboptimal memory state etc.. Those may result in failures of learning gating switch roles and thus the weak performance. In this paper, we propose a new gating mechanism within general gated recurrent neural networks to handle this issue. Specifically, the proposed gates directly short connect the extracted input features to the outputs of vanilla gates, denoted as refined gates. The refining mechanism allows enhancing gradient back-propagation as well as extending the gating activation scope, which can guide RNN to reach possibly deeper minima. We verify the proposed gating mechanism on three popular types of gated RNNs including LSTM, GRU and MGU. Extensive experiments on 3 synthetic tasks, 3 language modeling tasks and 5 scene text recognition benchmarks demonstrate the effectiveness of our method.

[Download Paper](https://arxiv.org/pdf/2002.11338)