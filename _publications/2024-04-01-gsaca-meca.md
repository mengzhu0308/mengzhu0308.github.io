---
title: "Improved channel attention methods via hierarchical pooling and reducing information loss"
collection: publications
category: manuscripts
permalink: /publication/2024-04-01-gsaca-meca
excerpt: 'This paper is about channel attention.'
date: 2024-04-01
venue: 'Pattern Recognition'
slidesurl: ''
arXivurl: ''
GitHuburl: 'https://github.com/mengzhu0308/GSACA-MECA'
paperurl: '/files/papers/2024-04-01-gsaca-meca.pdf'
citation: 'Meng Zhu, Weidong Min*, Junwei Han, et al. Improved channel attention methods via hierarchical pooling and reducing information loss. Pattern Recognition, 2024, 148: 1-9. DOI: 10.1016/j.patcog.2023.110148.'
---

# Abstract

Channel attention has been demonstrated to improve performance of convolutional neural networks. Most existing channel attention methods lower channel dimension for reducing computational complexity. However, the dimension reduction causes information loss, thus resulting in performance loss. To alleviate the paradox of complexity and performance trade-off, we propose two novel channel attention methods named Grouping-Shuffle-Aggregation Channel Attention (GSACA) method and Mixed Encoding Channel Attention (MECA) method, respectively. Our GSACA method partitions channel variables into several groups and performs the independent matrix multiplication without the dimension reduction to each group. Our GSACA method enables interaction between all groups using a "channel shuffle" operator. After these, our GSACA method performs the independent matrix multiplication each group again and aggregates all channel correlations. Our MECA method encodes channel information through dual path architectures to benefit from both path topology where one uses the multilayer perception with dimension reduction to encode channel information and the other uses channel information encoding method without dimension reduction. Furthermore, a novel pooling operator named hierarchical pooling is presented and applied to our GSACA and MECA methods. The experimental results showed that our GSACA method almost consistently outperformed most existing channel attention methods and that our MECA method consistently outperformed the existing channel attention methods.