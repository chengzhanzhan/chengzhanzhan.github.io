---
title: "LGPMA: Complicated Table Structure Recognition with Local and Global Pyramid Mask Alignment (Best Industry Paper)"
collection: publications
category: conferences
permalink: /publication/2021-09-02-conf-ICDAR-LGPMA
excerpt: 'Liang Qiao, Zaisheng Li, Zhanzhan Cheng*, Peng Zhang, Shiliang Pu, Yi Niu, Wenqi Ren, Wenming Tan, Fei Wu'
date: 2021-09-02
venue: 'ICDAR'
#slidesurl: 'http://academicpages.github.io/files/slides3.pdf'
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-030-86549-8_7'
#citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---

Authors:
------
Liang Qiao, Zaisheng Li, Zhanzhan Cheng*, Peng Zhang, Shiliang Pu, Yi Niu, Wenqi Ren, Wenming Tan, Fei Wu

Abstract:
------
Table structure recognition is a challenging task due to the various structures and complicated cell spanning relations. Previous methods handled the problem starting from elements in different granularities (rows/columns, text regions), which somehow fell into the issues like lossy heuristic rules or neglect of empty cell division. Based on table structure characteristics, we find that obtaining the aligned bounding boxes of text region can effectively maintain the entire relevant range of different cells. However, the aligned bounding boxes are hard to be accurately predicted due to the visual ambiguities. In this paper, we aim to obtain more reliable aligned bounding boxes by fully utilizing the visual information from both text regions in proposed local features and cell relations in global features. Specifically, we propose the framework of Local and Global Pyramid Mask Alignment, which adopts the soft pyramid mask learning mechanism in both the local and global feature maps. It allows the predicted boundaries of bounding boxes to break through the limitation of original proposals. A pyramid mask re-scoring module is then integrated to compromise the local and global information and refine the predicted boundaries. Finally, we propose a robust table structure recovery pipeline to obtain the final structure, in which we also effectively solve the problems of empty cells locating and division. Experimental results show that the proposed method achieves competitive and even new state-of-the-art performance on several public benchmarks.

[Download Paper](https://link.springer.com/chapter/10.1007/978-3-030-86549-8_7)