---
title: "Structure-aware multi-view image inpainting using dual consistency attention"
collection: publications
category: manuscripts
permalink: /publication/2023-12-01-image-inpainting
excerpt: 'This paper is about image inpainting.'
date: 2023-12-01
venue: 'Information Fusion'
slidesurl: ''
arXivurl: ''
GitHuburl: ''
paperurl: '/files/papers/2023-12-01-image-inpainting.pdf'
citation: 'Hongyue Xiang, Weidong Min*, Qing Han, Cheng Zha, Qian Liu, Meng Zhu. Structure-aware multi-view image inpainting using dual consistency attention. Information Fusion, 2024, 104: 1-11. DOI: 10.1016/j.inffus.2023.102174.'
---

# Abstract

Image inpainting based on deep learning has made remarkable progress and is widely used in image editing, cultural relic preservation, etc. However, most image inpainting methods are implemented based on single-view images. This does not fully utilize the known information and leads to unsatisfactory inpainting results. Moreover, these methods usually ignore the importance of image consistency and the surrounding regions, leading to irrelevant contents and visual artifacts in the inpainting results. To solve these problems, a structure-aware multi-view image inpainting method using dual consistency attention (SM-DCA) is proposed in this paper. It consists of two parts. The first part is the structure-aware multi-view image inpainting. This part constructs structure views as additional views to assist image inpainting. It is implemented by two networks: a structure inpainting network with strong constraints (SSC) and an image inpainting network with dual consistency attention (IDCA). SSC is used to repair structure views and make them closely resemble the ground truth through strong constraints. IDCA improves the consistency between the generated content and the whole image, making the repaired image more reasonable. The second part is image refinement, implemented by an image local refinement network (ILR). It can focus on the surrounding regions, eliminating boundary artifacts and obtaining finer local details. In Paris StreetView, SM-DCA achieves 22.0194, 0.7457 and 0.0557 in terms of PSNR, SSIM and MAE at 50%–60% damage. The corresponding values in CelebA are 22.5526, 0.8623 and 0.0453, respectively. The extensive experimental results on the Paris StreetView and CelebA datasets demonstrate the superiority of SM-DCA.