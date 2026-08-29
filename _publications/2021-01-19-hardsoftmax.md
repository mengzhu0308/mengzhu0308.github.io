---
title: "基于HardSoftmax的并行选择核注意力"
collection: publications
category: manuscripts
permalink: /publication/2021-01-19-hardsoftmax
excerpt: 'This paper is about branch attention.'
date: 2021-01-19
venue: '计算机工程与应用'
slidesurl: ''
arXivurl: ''
GitHuburl: 'https://github.com/mengzhu0308/PSK-Attention'
paperurl: '/files/papers/2021-01-19-hardsoftmax.pdf'
citation: 'Meng Zhu, Weidong Min*, Qi Wang, et al. PFLU and FPFLU: Two novel non-monotonic activation functions in convolutional neural networks. Neurocomputing, 2021, 429: 110-117. DOI: 10.1016/j.neucom.2020.11.068 
---

# 摘要

注意力被广泛地运用在卷积神经网络中，并有效地提升了卷积神经网络的性能。同时，注意力是非常轻量的，且几乎不需要改变卷积神经网络原来的架构。本文提出了基于 HardSoftmax 的并行选择核注意力。首先，针对 Softmax 包含指数运算，对于较大的正输入很容易发生计算溢出的问题，本文提出了计算更安全的 HardSoftmax 来替换 Softmax。然后，不同于选择核注意力将全局特征的提取和转换放在特征融合之后，并行选择核注意力将全局特征的提取和转换单独放在一个分支，与具有不同核大小的多个分支构成并行结构。同时，并行选择核注意力的全局特征转换使用分组卷积，进一步减少参数量和计算量。最后，并行选择核注意力通过 HardSoftmax 注意来关注不同核大小的多个分支。一系列的图像分类实验表明，只是简单地用Hardsoftmax 替换 Softmax，也能保持或提升原注意力的性能。HardSoftmax 的运行速度在实验中也比 Softmax更快速。并行选择核注意力能够以更少的参数量和计算量追平或超越选择核注意力。 