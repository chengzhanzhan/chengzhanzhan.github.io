---
title: "Flooding-X: Improving BERT’s Resistance to Adversarial Attacks via Loss-Restricted Fine-Tuning"
collection: publications
category: conferences
permalink: /publication/2022-05-28-conf-ACL-Flood
excerpt: 'Qin Liu, Rui Zheng, Bao Rong, Jingyi Liu, Zhihua Liu, Zhanzhan Cheng+, Liang Qiao, Tao Gui, Qi Zhang, Xuan-Jing Huang'
date: 2022-05-28
venue: 'ACL'
#slidesurl: 'http://academicpages.github.io/files/slides3.pdf'
paperurl: 'https://aclanthology.org/2022.acl-long.386.pdf'
#citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---

Authors:
------
Qin Liu, Rui Zheng, Bao Rong, Jingyi Liu, Zhihua Liu, Zhanzhan Cheng+, Liang Qiao, Tao Gui, Qi Zhang, Xuan-Jing Huang

Abstract:
------
Adversarial robustness has attracted much attention recently, and the mainstream solution is adversarial training. However, the tradition of generating adversarial perturbations for each input embedding (in the settings of NLP) scales up the training computational complexity by the number of gradient steps it takes to obtain the adversarial samples. To address this problem, we leverage Flooding method which primarily aims at better generalization and we find promising in defending adversarial attacks. We further propose an effective criterion to bring hyper-parameter-dependent flooding into effect with a narrowed-down search space by measuring how the gradient steps taken within one epoch affect the loss of each batch. Our approach requires zero adversarial sample for training, and its time consumption is equivalent to fine-tuning, which can be 2-15 times faster than standard adversarial training. We experimentally show that our method improves BERT’s resistance to textual adversarial attacks by a large margin, and achieves state-of-the-art robust accuracy on various text classification and GLUE tasks.

[Download Paper](https://aclanthology.org/2022.acl-long.386.pdf)