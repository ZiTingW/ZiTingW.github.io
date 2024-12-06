---
title: "Active self-semi-supervised learning for few labeled samples"
collection: publications
category: manuscripts
permalink: /publication/2024-11-19-paper-title-number-1
excerpt: 'This paper is about how to achieve good performance with rare human annotation (avg. 1~4 labels per class). Prior pseudo-labels transfer information from pre-trained models to semi-supervised training, active learning enhances accuracy of prior pseudo-labels.'
date: 2024-11-01
venue: 'Neurocomputing'
slidesurl: #'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S0925231224015431'
citation: 'Ziting Wen, Oscar Pizarro, and Stefan Williams. "Active self-semi-supervised learning for few labeled samples." Neurocomputing (2024): 128772.'
---

Key observations:

1.  Weight initialization struggles to effectively transfer valuable information obtained from self-supervised training to the semi-supervised model
2.  Label propagation on pre-trained features to construct prior pseudo-labels, serving as an effective intermediary to transfer information from self-supervised learning to semi-supervised models.
3.  Adapt active learning to improve the accuracy of prior pseudo-labels. 

<img src="../images/as3l.png" alt="Alt text for image" style="width:500px;">
