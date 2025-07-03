---
title: "Exploiting topic modeling to boost metagenomic reads binning"
collection: publications
category: journal
permalink: /publication/2015-01-16-jour-BMC-BIN
excerpt: 'Ruichang Zhang, Zhanzhan Cheng, Jihong Guan, Shuigeng Zhou'
date: 2015-01-16
venue: 'BMC Bioinformatics'
#slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://link.springer.com/article/10.1186/1471-2105-16-S5-S2'
#bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
#citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
Authors:
------
Ruichang Zhang, Zhanzhan Cheng, Jihong Guan, Shuigeng Zhou

Abstract:
------
Background
With the rapid development of high-throughput technologies, researchers can sequence the whole metagenome of a microbial community sampled directly from the environment. The assignment of these metagenomic reads into different species or taxonomical classes is a vital step for metagenomic analysis, which is referred to as binning of metagenomic data.

Results
In this paper, we propose a new method TM-MCluster for binning metagenomic reads. First, we represent each metagenomic read as a set of "k-mers" with their frequencies occurring in the read. Then, we employ a probabilistic topic model -- the Latent Dirichlet Allocation (LDA) model to the reads, which generates a number of hidden "topics" such that each read can be represented by a distribution vector of the generated topics. Finally, as in the MCluster method, we apply SKWIC -- a variant of the classical K-means algorithm with automatic feature weighting mechanism to cluster these reads represented by topic distributions.

Conclusions
Experiments show that the new method TM-MCluster outperforms major existing methods, including AbundanceBin, MetaCluster 3.0/5.0 and MCluster. This result indicates that the exploitation of topic modeling can effectively improve the binning performance of metagenomic reads.

[Download Paper](https://link.springer.com/article/10.1186/1471-2105-16-S5-S2)