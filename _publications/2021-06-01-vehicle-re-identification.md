---
title: "Viewpoint adaptation learning with cross-view distance metric for robust vehicle re-identification"
collection: publications
category: manuscripts
permalink: /publication/2021-06-01-vehicle-re-identification
excerpt: 'This paper is about vehicle re-identification.'
date: 2021-06-01
venue: 'Information Sciences'
slidesurl: ''
arXivurl: ''
GitHuburl: ''
paperurl: '/files/papers/2021-06-01-vehicle-re-identification.pdf'
citation: 'Qi Wang, Weidong Min*, Qing Han, Ziyuan Yang, Xin Xiong, Meng Zhu, Haoyu Zhao. Viewpoint adaptation learning with cross-view distance metric for robust vehicle re-identification. Information Sciences, 2021, 564: 71-84. DOI: 10.1016/j.ins.2021.02.013.'
---

# Abstract

Many vehicle re-identiﬁcation (Re-ID) problems require the robust recognition of vehicle instances across multiple viewpoints. Existing approaches for dealing with the vehicle re-ID problem are insufﬁciently robust because they cannot distinguish among vehicles of the same type nor recognize high-level representations in deep networks for identical vehicles with various views. To address these issues, this paper proposes a viewpoint adap-tation network (VANet) with a cross-view distance metric for robust vehicle Re-ID. This method consists of two modules. The ﬁrst module is the VANet with cross-view label smoothing regularization (CVLSR), which abstracts different levels of a vehicle’s visual pat-terns and subsequently integrates multi-level features. In particular, CVLSR based on color domains assigns a virtual label to the generated data to smooth image-image translation noise. Accordingly, this module supplies the viewing angle information of the training data and provides strong robust capability for vehicles across different viewpoints. The second module is the cross-view distance metric, which designs a cascaded cross-view matching approach to combine the original features with the generated ones, and thus, obtain addi-tional supplementary viewpoint information for the multi-view matching of vehicles. Results of extensive experiments on two large scale vehicle Re-ID datasets, namely, VeRi-776 and VehiclelD demonstrate that the performance of the proposed method is robust and superior to other state-of-the-art Re-ID methods across multiple viewpoints.