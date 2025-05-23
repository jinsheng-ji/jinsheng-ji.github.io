---
title: "Adversarial erasing attention for fine-grained image classification"
collection: publications
category: manuscripts
selected: false
permalink: /publication/2020-01-30-paper-mta-fine-grained-classification
excerpt: ""
date: 2020-01-30
venue: 'Multimedia Tools and Applications'
slidesurl: null
paperurl: 'https://link.springer.com/article/10.1007/s11042-020-08666-3'
citation: '<u><strong>Ji, Jinsheng</strong></u> and Jiang, Linfeng and Zhang, Tao and Zhong, Weilin and Xiong, Huilin, "Adversarial erasing attention for fine-grained image classification," in Multimed Tools Appl 80, 22867–22889 (2021). https://doi.org/10.1007/s11042-020-08666-3'
---
Recognizing fine-grained subcategories is a challenging task due to the large intra-class diversities and small inter-class variances of the fine-grained images. The common thought is to find out the parts that can distinguish similar subcategories efficiently. Most previous works rely on the manual annotations or attention technologies to localize the discriminative parts and have achieved great progress. However, these manual annotations are demanding in practical applications and some complicated constrains on the loss functions have to be adopted to localize the discriminative parts for building multi-view feature representations. To handle the challenges above, the strategy of adversarial erasing is applied on the attention module in this paper, which learns to localize different discriminative parts by erasing the most one from the image. Without the complicated loss functions, the proposed attention module can localize the discriminative parts more efficiently. Different from many part based methods, the classification network which consists of three subnetworks is introduced, and the subnetworks are trained by the original image and two discriminative parts respectively. Moreover, features learned from the three subnetworks are then fused in a more efficiently way to build better feature representations. Four mostly used datasets of CUB-200-2011, Stanford Dogs, Stanford Cars and FGVC-Aircraft are utilized to evaluate the proposed method and experimental results show that it can outperform some state-of-the-art methods without using the manual annotations.
