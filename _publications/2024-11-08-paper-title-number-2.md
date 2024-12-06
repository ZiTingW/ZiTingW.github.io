---
title: "Feature Alignment: Rethinking Efficient Active Learning via Proxy in the Context of Pre-trained Models"
collection: publications
category: manuscripts
permalink: /publication/2024-11-08-paper-title-number-2
excerpt: 'This paper is about balancing overall cost (labeling cost and training cost) and active learning sampling time. Some intriguing empirical analysis on which part of sample selection difference between the proxy model (used in efficient AL) and the fine-tuned model (used in standard AL) contribute to AL performance drops and why.'
date: 2024-11-08
venue: 'TMLR'
slidesurl: #'http://academicpages.github.io/files/slides2.pdf'
paperurl: 'https://openreview.net/pdf?id=PNcgJMJcdl'
citation: 'Ziting Wen, Oscar Pizarro, and Stefan B. Williams. "Feature Alignment: Rethinking Efficient Active Learning via Proxy in the Context of Pre-trained Models." Transactions on Machine Learning Research (2024).'
image: "/images/asvp_img.png"
---

Key observations:

1. Active learning based on a proxy model (an MLP classifier with pre-trained feature inputs) can improve computational efficiency but may reduce AL accuracy and lead to higher overall costs,
2. Not all differences in sample selection between the proxy model and the fine-tuned model contribute to differences in Active Learning performance,
3. When the number of labeled samples is small, adopting LP-FT (linear probing followed by fine-tuning) for final model training can help mitigate AL performance gaps. However, when more labels are available, fine-tuning is necessary to update the pre-computed features.

<img src="../images/asvp_img.png" alt="Alt text for image" style="width:500px;">
