---
title: "Constructing a smoothed Leaky ReLU using a linear combination of the smoothed ReLU and identity function"
collection: publications
category: manuscripts
permalink: /publication/2025-03-01-leakypflu
excerpt: 'This paper is about activation functions.'
date: 2025-03-01
venue: 'Neural Computing and Applications'
slidesurl: ''
arXivurl: ''
GitHuburl: 'https://github.com/mengzhu0308/LPFLU'
paperurl: '/files/papers/2025-03-01-leakypflu.pdf'
citation: 'Meng Zhu, Weidong Min*, Jiahao Li, et al. Constructing a smoothed Leaky ReLU using a linear combination of the smoothed ReLU and identity function. Neural Computing and Applications, 2025: 1-14. DOI: 10.1007/s00521-024-10935-3.'
---

# Abstract

Convolutional neural networks (CNNs) have made tremendous progress in solving many challenging problems. Good activation functions can improve the performance of CNNs. The existing activation functions exhibit inconsistent per-formance gains across different training settings, models, datasets and tasks. To solve this problem, we propose a general smoothed approximation for the maximum function maxðxi; axiÞ using the linear combination of the smoothed rectiﬁed linear unit and the identity function. And we use exponential moving average to training the negative slope in this smoothed approximation. To validate the effectiveness of our approach, we also present a smoothed approximation case named leaky power function linear unit (LPFLU) to compare with the current state-of-the-art activation functions. Experimental results demonstrate that our LPFLU outperforms the existing state-of-the-art activation functions in improved robustness across different training settings, models, datasets and tasks.