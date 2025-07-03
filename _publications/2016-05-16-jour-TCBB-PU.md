---
title: "Effectively Identifying Compound-Protein Interactions by Learning from Positive and Unlabeled Examples"
collection: publications
category: journal
permalink: /publication/2016-05-16-jour-TCBB-PU
excerpt: 'Zhanzhan Cheng, Shuigeng Zhou, Yang Wang, Hui Liu, Jihong Guan, Yi-Ping Phoebe Chen'
date: 2016-05-16
venue: 'IEEE/ACM TCBB'
#slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/7471459'
#bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
#citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
Authors:
------
Zhanzhan Cheng, Shuigeng Zhou, Yang Wang, Hui Liu, Jihong Guan, Yi-Ping Phoebe Chen

Abstract:
------
Prediction of compound-protein interactions (CPIs) is to find new compound-protein pairs where a protein is targeted by at least a compound, which is a crucial step in new drug design. Currently, a number of machine learning based methods have been developed to predict new CPIs in the literature. However, as there is not yet any publicly available set of validated negative CPIs, most existing machine learning based approaches use the unknown interactions (not validated CPIs) selected randomly as the negative examples to train classifiers for predicting new CPIs. Obviously, this is not quite reasonable and unavoidably impacts the CPI prediction performance. In this paper, we simply take the unknown CPIs as unlabeled examples, and propose a new method called PUCPI (the abbreviation of PU learning for Compound-Protein Interaction identification) that employs biased-SVM (Support Vector Machine) to predict CPIs using only positive and unlabeled examples. PU learning is a class of learning methods that leans from positive and unlabeled (PU) samples. To the best of our knowledge, this is the first work that identifies CPIs using only positive and unlabeled examples. We first collect known CPIs as positive examples and then randomly select compound-protein pairs not in the positive set as unlabeled examples. For each CPI/compound-protein pair, we extract protein domains as protein features and compound substructures as chemical features, then take the tensor product of the corresponding compound features and protein features as the feature vector of the CPI/compound-protein pair. After that, biased-SVM is employed to train classifiers on different datasets of CPIs and compound-protein pairs. Experiments over various datasets show that our method outperforms six typical classifiers, including random forest, L1- and L2-regularized logistic regression, naive Bayes, SVM and k-nearest neighbor (kNN), and three types of existing CPI prediction models. More information can be found at http://admis.fudan.edu.cn/projects/pucpi.html.

[Download Paper](https://ieeexplore.ieee.org/abstract/document/7471459)