---
title: "Divide Rows and Conquer Cells: Towards Structure Recognition for Large Tables"
collection: publications
category: conferences
permalink: /publication/2023-08-19-conf-IJCAI-Table
excerpt: 'Huawen Shen, Xiang Gao, Jin Wei, Liang Qiao, Yu Zhou, Qiang Li, Zhanzhan Cheng'
date: 2023-08-19
venue: 'IJCAI'
#slidesurl: 'http://academicpages.github.io/files/slides3.pdf'
paperurl: 'https://www.researchgate.net/profile/Xiang_Gao54/publication/373077707_Divide_Rows_and_Conquer_Cells_Towards_Structure_Recognition_for_Large_Tables/links/66ac5e5651aa0775f263cf87/Divide-Rows-and-Conquer-Cells-Towards-Structure-Recognition-for-Large-Tables.pdff'
#citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---

Authors:
------
Huawen Shen, Xiang Gao, Jin Wei, Liang Qiao, Yu Zhou, Qiang Li, Zhanzhan Cheng

Abstract:
------
Recent advanced Table Structure Recognition (TSR) models adopt image-to-text solutions to parse table structure. These methods can be formulated as image caption problem, ie, input a singletable image and output table structure description in a specific text format, eg, HTML. With the impressive success of Transformer in text generation tasks, these methods use Transformer architecture to predict HTML table text in an autoregressive manner. However, tables always emerge with a large variety of shapes and sizes. Autoregressive models usually suffer from the error accumulation problem as the length of predicted text increases, which results in unsatisfactory performance for large tables. In this paper, we propose a novel image-to-text based TSR method that relieves error accumulation problems and improves performance noticeably. At the core of our method is a cascaded two-step decoder architecture with the former decoder predicting HTML table row tags non-autoregressively and the latter predicting HTML table cell tags of each row in a semiautoregressive manner. Compared with existing methods that predict HTML text autoregressively, the superiority of our row-to-cell progressive table parsing is twofold:(i) it generates an HTML tag sequence with a vertical-and-horizontal twostep ‘scanning’, which better fits the inherent 2D structure of image data,(ii) it performs substantially better for large tables (long sequence prediction) since it alleviates error accumulation problem specific to autoregressive models. Extensive experiments demonstrate that our method achieves competitive performance on three public benchmarks.

[Download Paper](https://www.researchgate.net/profile/Xiang_Gao54/publication/373077707_Divide_Rows_and_Conquer_Cells_Towards_Structure_Recognition_for_Large_Tables/links/66ac5e5651aa0775f263cf87/Divide-Rows-and-Conquer-Cells-Towards-Structure-Recognition-for-Large-Tables.pdf)