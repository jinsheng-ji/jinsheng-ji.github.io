---
title: "Self-supervised monocular depth and visual odometry learning with scale-consistent geometric constraints"
collection: publications
category: conferences
selected: false
permalink: /publication/2020-01-20-paper-ijcai-monocular-depth
excerpt: ""
date: 2020-01-20
venue: 'IJCAI'
slidesurl: null
paperurl: 'https://dl.acm.org/doi/abs/10.5555/3491440.3491574'
citation: 'Xiong, Mingkang and Zhang, Zhenghong and Zhong, Weilin and <u><strong>Ji, Jinsheng</strong></u> and Liu, Jiyuan and Xiong, Huilin, "Remote Sensing Scene Classification via Pseudo-Category-Relationand Orthogonal Feature Learning," in Proceedings of the Twenty-Ninth International Joint Conference on Artificial Intelligence (IJCAI'20). Article 134, 963–969.'
---
The self-supervised learning-based depth and visual odometry (VO) estimators trained on monocular videos without ground truth have drawn significant attention recently. Prior works use photometric consistency as supervision, which is fragile under complex realistic environments due to illumination variations. More importantly, it suffers from scale inconsistency in the depth and pose estimation results. In this paper, robust geometric losses are proposed to deal with this problem. Specifically, we first align the scales of two reconstructed depth maps estimated from the adjacent image frames, and then enforce forward-backward relative pose consistency to formulate scale-consistent geometric constraints. Finally, a novel training framework is constructed to implement the proposed losses. Extensive evaluations on KITTI and Make3D datasets demonstrate that, i) by incorporating the proposed constraints as supervision, the depth estimation model can achieve state-of-theart (SOTA) performance among the self-supervised methods, and ii) it is effective to use the proposed training framework to obtain a uniform global scale VO model.
