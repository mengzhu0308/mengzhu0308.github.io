---
title: "ShuffleNeMt: Modern lightweight convolutional neural network architecture"
collection: publications
category: manuscripts
permalink: /publication/2024-12-01-shufflenemt
excerpt: 'This paper is about lightweight convolutional neural networks.'
date: 2024-12-01
venue: 'Pattern Analysis and Applications'
slidesurl: ''
arXivurl: ''
GitHuburl: 'https://github.com/mengzhu0308/ShuffleNeMt'
paperurl: '/files/papers/2024-12-01-shufflenemt.pdf'
citation: 'Meng Zhu, Weidong Min*, Qing Han, et al. ShuffleNeMt: Modern lightweight convolutional neural network architecture. Pattern Analysis and Applications, 2024, 27 (4): 123-134. DOI: 10.1007/s10044-024-01327-3.'
---

# Abstract

Lightweight convolutional neural networks (CNNs) are specifically designed for mobile devices and embedded systems, being aimed at achieving lower resource and faster inference speed. However, these networks are limited in their ability to capture long-range dependencies due to the local nature of convolutional operations. The introduction of self-attention into these CNNs can effectively capture global information, but it comes at the cost of significantly slower inference speed. To solve these problems, we propose a novel lightweight network called as ShuffleNeMt. Our ShuffleNeMt involves modernizing ShuffleNetV2 by incorporating several strategies, including pre-norm residual learning, scaling the residual depth, visual self-attention and non-monotonic activation functions. The visual self-attention is used for only one layer and positioned in the middle of the network. Using this way, ShuffleNeMt not only can achieve efficient resource utilization and fast inference speed, but also can capture long-range spatial dependencies. Extensive experimental results demonstrate the superiority of ShuffleNeMt over the existing lightweight architectures. E.g., On the CIFAR-100 image classification dataset, ShuffleN-eMt-1.5 achieved top-1 error rate of 34.05% using 2.588M parameters, which is better than the top-1 error rate of 36.86% achieved by MobileNetV3-Large-0.8 using 2.809M parameters.