---
title: "Dynamic Low-Resolution Distillation for Cost-Efficient End-to-End Text Spotting"
collection: publications
category: conferences
permalink: /publication/2022-10-23-conf-ECCV-Dynamic
excerpt: 'Ying Chen, Liang Qiao, Zhanzhan Cheng*, Shiliang Pu, Yi Niu, Xi Li'
date: 2022-10-23
venue: 'ECCV'
#slidesurl: 'http://academicpages.github.io/files/slides3.pdf'
paperurl: 'https://arxiv.org/pdf/2207.06694'
#citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---

Authors:
------
Ying Chen, Liang Qiao, Zhanzhan Cheng*, Shiliang Pu, Yi Niu, Xi Li

Abstract:
------
End-to-end text spotting has attached great attention recently due to its benefits on global optimization and high maintainability for real applications. However, the input scale has always been a tough trade-off since recognizing a small text instance usually requires enlarging the whole image, which brings high computational costs. In this paper, to address this problem, we propose a novel cost-efficient Dynamic Low-resolution Distillation (DLD) text spotting framework, which aims to infer images in different small but recognizable resolutions and achieve a better balance between accuracy and efficiency. Concretely, we adopt a resolution selector to dynamically decide the input resolutions for different images, which is constraint by both inference accuracy and computational cost. Another sequential knowledge distillation strategy is conducted on the text recognition branch, making the low-res input obtains comparable performance to a high-res image. The proposed method can be optimized end-to-end and adopted in any current text spotting framework to improve the practicability. Extensive experiments on several text spotting benchmarks show that the proposed method vastly improves the usability of low-res models. 

[Download Paper](https://arxiv.org/pdf/2207.06694)