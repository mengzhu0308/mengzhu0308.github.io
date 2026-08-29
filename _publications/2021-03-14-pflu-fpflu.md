---
title: "PFLU and FPFLU: Two novel non-monotonic activation functions in convolutional neural networks"
collection: publications
category: manuscripts
permalink: /publication/2021-03-14-pflu-fpflu
excerpt: 'This paper is about activation functions.'
date: 2021-03-14
venue: 'Neurocomputing'
slidesurl: ''
arXivurl: ''
GitHuburl: 'https://github.com/mengzhu0308/PFLU-FPFLU'
paperurl: '/files/papers/2021-03-14-pflu-fpflu.pdf'
citation: 'Meng Zhu, Weidong Min*, Qi Wang, et al. PFLU and FPFLU: Two novel non-monotonic activation functions in convolutional neural networks. Neurocomputing, 2021, 429: 110-117. DOI: 10.1016/j.neucom.2020.11.068.'
---

# Abstract

The choice of activation functions in Convolutional Neural Networks (CNNs) is very important. Rectiﬁed Linear Unit (ReLU) has been widely-used in most CNNs. Recently, a series of non-monotonic activation functions gradually become the new standard to enhance performance of CNNs. Inspired by them, this paper ﬁrstly proposes a novel non-monotonic activation function called Power Function Linear Unit (PFLU). The negative part of PFLU is non-monotonic and closer to zero with the negative input decreasing, which can maintain sparsity of the negative part while introducing negative activation values and non-zero derivative values for the negative part. The positive part of PFLU does not use identity mapping but is closer to identity mapping with the positive input increasing, which can bring non-linearity property for the positive part. Next, this paper proposes faster PFLU (FPFLU). A wide range of classiﬁcation experi-ments show that PFLU tends to work better than current state-of-the-art non-monotonic activation func-tions, and FPFLU can run faster than most non-monotonic activation functions.