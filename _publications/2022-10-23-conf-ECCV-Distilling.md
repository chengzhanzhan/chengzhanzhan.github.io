---
title: "Distilling Object Detectors with Global Knowledge"
collection: publications
category: conferences
permalink: /publication/2022-10-23-conf-ECCV-Distilling
excerpt: 'Sanli Tang, Zhongyu Zhang, Zhanzhan Cheng*, Jing Lu, Yunlu Xu, Yi Niu, Fan He'
date: 2022-10-23
venue: 'ECCV'
#slidesurl: 'http://academicpages.github.io/files/slides3.pdf'
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-031-20077-9_25'
#citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---

Authors:
------
Sanli Tang, Zhongyu Zhang, Zhanzhan Cheng*, Jing Lu, Yunlu Xu, Yi Niu, Fan He

Abstract:
------
Knowledge distillation learns a lightweight student model that mimics a cumbersome teacher. Existing methods regard the knowledge as the feature of each instance or their relations, which is the instance-level knowledge only from the teacher model, i.e., the local knowledge. However, the empirical studies show that the local knowledge is much noisy in object detection tasks, especially on the blurred, occluded, or small instances. Thus, a more intrinsic approach is to measure the representations of instances w.r.t. a group of common basis vectors in the two feature spaces of the teacher and the student detectors, i.e., global knowledge. Then, the distilling algorithm can be applied as space alignment. To this end, a novel prototype generation module (PGM) is proposed to find the common basis vectors, dubbed prototypes, in the two feature spaces. Then, a robust distilling module (RDM) is applied to construct the global knowledge based on the prototypes and filtrate noisy local knowledge by measuring the discrepancy of the representations in two feature spaces. Experiments with Faster-RCNN and RetinaNet on PASCAL and COCO datasets show that our method achieves the best performance for distilling object detectors with various backbones, which even surpasses the performance of the teacher model. We also show that the existing methods can be easily combined with global knowledge and obtain further improvement. Code is available: https://github.com/hikvision-research/DAVAR-Lab-ML.

[Download Paper](https://link.springer.com/chapter/10.1007/978-3-031-20077-9_25)