---
title: "VSR: A Unified Framework for Document Layout Analysis combining Vision, Semantics and Relations"
collection: publications
category: conferences
permalink: /publication/2021-09-02-conf-ICDAR-VSR
excerpt: 'Peng Zhang, Can Li, Liang Qiao, Zhanzhan Cheng*, Shiliang Pu, Yi Niu, Fei Wu'
date: 2021-09-02
venue: 'ICDAR'
#slidesurl: 'http://academicpages.github.io/files/slides3.pdf'
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-030-86549-8_8'
#citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---

Authors:
------
Peng Zhang, Can Li, Liang Qiao, Zhanzhan Cheng*, Shiliang Pu, Yi Niu, Fei Wu

Abstract:
------
Document layout analysis is crucial for understanding document structures. On this task, vision and semantics of documents, and relations between layout components contribute to the understanding process. Though many works have been proposed to exploit the above information, they show unsatisfactory results. NLP-based methods model layout analysis as a sequence labeling task and show insufficient capabilities in layout modeling. CV-based methods model layout analysis as a detection or segmentation task, but bear limitations of inefficient modality fusion and lack of relation modeling between layout components. To address the above limitations, we propose a unified framework VSR for document layout analysis, combining vision, semantics and relations. VSR supports both NLP-based and CV-based methods. Specifically, we first introduce vision through document image and semantics through text embedding maps. Then, modality-specific visual and semantic features are extracted using a two-stream network, which are adaptively fused to make full use of complementary information. Finally, given component candidates, a relation module based on graph neural network is incorported to model relations between components and output final results. On three popular benchmarks, VSR outperforms previous models by large margins. 

[Download Paper](https://link.springer.com/chapter/10.1007/978-3-030-86549-8_8)