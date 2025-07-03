---
title: "You Only Recognize Once: Towards Fast Video Text Spotting"
collection: publications
category: conferences
permalink: /publication/2019-10-12-conf-ACMMM-YORO
excerpt: 'Zhanzhan Cheng, Jing Lu, Yi Niu, Shiliang Pu, Fei Wu, Shuigeng Zhou'
date: 2019-10-12
venue: 'ACM MM'
#slidesurl: 'http://academicpages.github.io/files/slides3.pdf'
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3343031.3351093'
#citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---

Authors:
------
Zhanzhan Cheng, Jing Lu, Yi Niu, Shiliang Pu, Fei Wu, Shuigeng Zhou

Abstract:
------
Video text spotting is still an important research topic due to its various real-applications. Previous approaches usually fall into the four-staged pipeline: text detection in individual images, framewisely recognizing localized text regions, tracking text streams and generating final results with complicated post-processing skills, which might suffer from the huge computational cost as well as the interferences of low-quality text. In this paper, we propose a fast and robust video text spotting framework by only recognizing the localized text one-time instead of frame-wisely recognition. Specifically, we first obtain text regions in videos with a well-designed spatial-temporal detector. Then we concentrate on developing a novel text recommender for selecting the highest-quality text from text streams and only recognizing the selected ones. Here, the recommender assembles text tracking, quality scoring and recognition into an end-to-end trainable module, which not only avoids the interferences from low-quality text but also dramatically speeds up the video text spotting process. In addition, we collect a larger scale video text dataset (LSVTD) for promoting the video text spotting community, which contains 100 text videos from 22 different real-life scenarios. Extensive experiments on two public benchmarks show that our method greatly speeds up the recognition process averagely by 71 times compared with the frame-wise manner, and also achieves the remarkable state-of-the-art.

[Download Paper](https://dl.acm.org/doi/abs/10.1145/3343031.3351093)