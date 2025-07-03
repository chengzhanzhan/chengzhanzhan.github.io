---
title: "Edit Probability for Scene Text Recognition"
collection: publications
category: conferences
permalink: /publication/2018-06-22-conf-CVPR-AON
excerpt: 'Fan Bai, Zhanzhan Cheng*, Yi Niu, Shiliang Pu, Shuigeng Zhou'
date: 2018-06-22
venue: 'CVPR'
#slidesurl: 'http://academicpages.github.io/files/slides3.pdf'
paperurl: 'https://openaccess.thecvf.com/content_cvpr_2018/papers/Bai_Edit_Probability_for_CVPR_2018_paper.pdf'
#citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---

Authors:
------
Fan Bai, Zhanzhan Cheng*, Yi Niu, Shiliang Pu, Shuigeng Zhou

Abstract:
------
We consider the scene text recognition problem under the attention-based encoder-decoder framework, which is the state of the art. The existing methods usually employ a frame-wise maximal likelihood loss to optimize the models. When we train the model, the misalignment between the ground truth strings and the attention's output sequences of probability distribution, which is caused by missing or superfluous characters, will confuse and mislead the training process, and consequently make the training costly and degrade the recognition accuracy. To handle this problem, we propose a novel method called edit probability (EP) for scene text recognition. EP tries to effectively estimate the probability of generating a string from the output sequence of probability distribution conditioned on the input image, while considering the possible occurrences of missing/superfluous characters. The advantage lies in that the training process can focus on the missing, superfluous and unrecognized characters, and thus the impact of the misalignment problem can be alleviated or even overcome. We conduct extensive experiments on standard benchmarks, including the IIIT-5K, Street View Text and ICDAR datasets. Experimental results show that the EP can substantially boost scene text recognition performance.

[Download Paper](https://openaccess.thecvf.com/content_cvpr_2018/papers/Bai_Edit_Probability_for_CVPR_2018_paper.pdf)