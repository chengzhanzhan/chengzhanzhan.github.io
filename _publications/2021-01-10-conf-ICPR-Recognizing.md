---
title: "Recognizing Multiple Text Sequences from an Image by Pure End-to-End Learning"
collection: publications
category: conferences
permalink: /publication/2021-01-10-conf-ICPR-Recognizing
excerpt: 'Zhenlong Xu, Shuigeng Zhou, Fan Bai, Zhanzhan Cheng*, Yi Niu, Shiliang Pu'
date: 2021-01-10
venue: 'ICPR'
#slidesurl: 'http://academicpages.github.io/files/slides3.pdf'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9412079'
#citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---

Authors:
------
Zhenlong Xu, Shuigeng Zhou, Fan Bai, Zhanzhan Cheng*, Yi Niu, Shiliang Pu

Abstract:
------
We address a challenging problem: recognizing multiple text sequences from an image by pure end-to-end learning. It is twofold: 1) Multiple text sequences recognition. Each image may contain multiple text sequences of different content, location and orientation, we try to recognize all these texts in the image. 2) Pure end-to-end (PEE) learning. We solve the problem in a pure end-to-end learning way where each training image is labeled by only text transcripts of the contained sequences, without any geometric annotations. Most existing works recognize multiple text sequences from an image in a non-end-to-end (NEE) or quasi-end-to-end (QEE) way, in which each image is trained with both text transcripts and text locations. Only recently, a PEE method was proposed to recognize text sequences from an image where the text sequence was split to several lines in the image. However, it cannot be directly applied to recognizing multiple text sequences from an image. So in this paper, we propose a pure end-to-end learning method to recognize multiple text sequences from an image. Our method directly learns the probability distribution of multiple sequences conditioned on each input image, and outputs multiple text transcripts with a well-designed decoding strategy. To evaluate the proposed method, we construct several datasets mainly based on an existing public dataset and two real application scenarios. Experimental results show that the proposed method can effectively recognize multiple text sequences from images, and outperforms CTC-based and attention-based baseline methods.

[Download Paper](https://ieeexplore.ieee.org/abstract/document/9412079)