---
title: "Selecting high-quality negative samples for effectively predicting protein-RNA interactions"
collection: publications
category: journal
permalink: /publication/2017-01-16-jour-BMC-PR
excerpt: 'Zhanzhan Cheng, Kai Huang, Yang Wang, Hui Liu, Jihong Guan, Shuigeng Zhou'
date: 2017-01-16
venue: 'BMC Systems Biology'
#slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://link.springer.com/content/pdf/10.1186/s12918-017-0390-8.pdf'
#bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
#citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
Authors:
------
Zhanzhan Cheng, Kai Huang, Yang Wang, Hui Liu, Jihong Guan, Shuigeng Zhou

Abstract:
------
 Background: The identification of Protein-RNA Interactions (PRIs) is important to understanding cell activities.
 Recently, several machine learning-based methods have been developed for identifying PRIs. However, the
 performance of these methods is unsatisfactory. One major reason is that they usually use unreliable negative
 samples in the training process.

 Methods: For boosting the performance of PRI prediction, we propose a novel method to generate reliable negative
 samples. Concretely, we firstly collect the known PRIs as positive samples for generating positive sets. For each
 positive set, we construct two corresponding negative sets, one is by our method and the other by random method.
 Each positive set is combined with a negative set to form a dataset for model training and performance evaluation.
 Consequently, we get 18 datasets of different species and different ratios of negative samples to positive samples.
 Secondly, sequence-based features are extracted to represent each of PRIs and protein-RNA pairs in the datasets. A
 filter-based method is employed to cut down the dimensionality of feature vectors for reducing computational cost.
 Finally, the performance of support vector machine (SVM), random forest (RF) and naive Bayes (NB) is evaluated on the
 generated 18 datasets.

 Results: Extensive experiments show that comparing to using randomly-generated negative samples, all classifiers
 achieve substantial performance improvement by using negative samples selected by our method. The
 improvements on accuracy and geometric mean for the SVM classifier, the RF classifier and the NB classifier are as
 high as 204.5 and 68.7%, 174.5 and 53.9%, 80.9 and 54.3%, respectively.
 
 Conclusion: Our method is useful to the identification of PRIs.

[Download Paper](https://link.springer.com/content/pdf/10.1186/s12918-017-0390-8.pdf)