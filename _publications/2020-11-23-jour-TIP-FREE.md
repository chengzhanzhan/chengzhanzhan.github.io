---
title: "FREE: A Fast and Robust End-to-End Video Text Spotter"
collection: publications
category: journal
permalink: /publication/2020-11-23-jour-TIP-FREE
excerpt: 'Zhanzhan Cheng, Jing Lu, Baorui Zou, Liang Qiao, Yunlu Xu, Shiliang Pu, Yi Niu, Fei Wu, Shuigeng Zhou'
date: 2017-01-16
venue: 'IEEE TIP'
#slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9266586'
#bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
#citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
Authors:
------
Zhanzhan Cheng, Jing Lu, Baorui Zou, Liang Qiao, Yunlu Xu, Shiliang Pu, Yi Niu, Fei Wu, Shuigeng Zhou

Abstract:
------
Currently, video text spotting tasks usually fall into the four-staged pipeline: detecting text regions in individual images, recognizing localized text regions frame-wisely, tracking text streams and post-processing to generate final results. However, they may suffer from the huge computational cost as well as suboptimal results due to the interferences of low-quality text and the none-trainable pipeline strategy. In this paper, we propose a fast and robust end-to-end video text spotting framework named FREE by only recognizing the localized text stream onetime instead of frame-wise recognition. Specifically, FREE first employs a well-designed spatial-temporal detector that learns text locations among video frames. Then a novel text recommender is developed to select the highest-quality text from text streams for recognizing. Here, the recommender is implemented by assembling text tracking, quality scoring and recognition into a trainable module. It not only avoids the interferences from the low-quality text but also dramatically speeds up the video text spotting. FREE unites the detector and recommender into a whole framework, and helps achieve global optimization. Besides, we collect a large scale video text dataset for promoting the video text spotting community, containing 100 videos from 21 real-life scenarios. Extensive experiments on public benchmarks show our method greatly speeds up the text spotting process, and also achieves the remarkable state-of-the-art. 

[Download Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9266586)