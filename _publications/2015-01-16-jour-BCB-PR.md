---
title: "Computationally predicting protein-RNA interactions using only positive and unlabeled examples"
collection: publications
category: journal
permalink: /publication/2015-01-16-jour-BCB-PR
excerpt: 'Zhanzhan Cheng, Shuigeng Zhou, and Jihong Guan'
date: 2015-01-16
venue: 'J. Bioinformatics and Computational Biology'
#slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://www.worldscientific.com/doi/abs/10.1142/S021972001541005X'
#bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
#citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
Authors:
------
Zhanzhan Cheng, Shuigeng Zhou, and Jihong Guan

Abstract:
------
Protein–RNA interactions (PRIs) are considerably important in a wide variety of cellular processes, ranging from transcriptional and post-transcriptional regulations of gene expression to the active defense of host against virus. With the development of high throughput technology, large amounts of PRI information is available for computationally predicting unknown PRIs. In recent years, a number of computational methods for predicting PRIs have been developed in the literature, which usually artificially construct negative samples based on verified nonredundant datasets of PRIs to train classifiers. However, such negative samples are not real negative samples, some even may be unknown positive samples. Consequently, the classifiers trained with such training datasets cannot achieve satisfactory prediction performance. In this paper, we propose a novel method PRIPU that employs biased-support vector machine (SVM) for predicting Protein-RNA Interactions using only Positive and Unlabeled examples. To the best of our knowledge, this is the first work that predicts PRIs using only positive and unlabeled samples. We first collect known PRIs as our benchmark datasets and extract sequence-based features to represent each PRI. To reduce the dimension of feature vectors for lowering computational cost, we select a subset of features by a filter-based feature selection method. Then, biased-SVM is employed to train prediction models with different PRI datasets. To evaluate the new method, we also propose a new performance measure called explicit positive recall (EPR), which is specifically suitable for the task of learning positive and unlabeled data. Experimental results over three datasets show that our method not only outperforms four existing methods, but also is able to predict unknown PRIs. Source code, datasets and related documents of PRIPU are available at: http://admis.fudan.edu.cn/projects/pripu.htm.

[Download Paper](https://www.worldscientific.com/doi/abs/10.1142/S021972001541005X)