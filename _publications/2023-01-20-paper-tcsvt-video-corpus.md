---
title: "Video Corpus Moment Retrieval via Deformable Multigranularity Feature Fusion and Adversarial Training"
collection: publications
category: manuscripts
permalink: /publication/2023-01-20-paper-tcsvt-video-corpus
excerpt:
date: 2023-07-12
venue: 'IEEE Transactions on Circuits and Systems for Video Technology'
slidesurl: 'https://ieeexplore.ieee.org/document/10179965'
paperurl: 'https://ieeexplore.ieee.org/document/10179965'
citation: 'Zhang, Xuemei and Zhao, Peng and <u><strong>Ji, Jinsheng</strong></u> and Lu, Xiankai and Yin, Yilong, "Video Corpus Moment Retrieval via Deformable Multigranularity Feature Fusion and Adversarial Training," in IEEE Transactions on Circuits and Systems for Video Technology, vol. 34, no. 8, pp. 6686-6698, Aug. 2024, doi: 10.1109/TCSVT.2023.3294567.'
---
As a new emerging task, video corpus moment retrieval (VCMR) aims to find the video segments relevant to a given natural language query from a large number of untrimmed videos. It mainly includes two subtasks, finding the most relevant video based on the query text (video retrieval), and locating the segment most relevant to a given query in a video (moment localization). At the same time, since videos often contain rich multi-modal information such as audio, text, and images, how to align and interact with the multi-modal information of videos and the text information of natural language queries across modalities is the core issue of this task. This article proposes a Deformable Multigranularity Feature Fusion with Adversarial Training Network (DMFAT), first inputs the subtitle and frame multi-modal information of the video into our Multi-Scale Deformable Attention module and performs multi-granularity feature fusion through Deformable Attention respectively. Then, guided by the query, adaptive weights are generated to fuse the two multi-granularity modality features of the video. Finally, the cross-modal representation of the query and video features is obtained through a bidirectional attention module, and an adversarial contrastive learning objective is introduced to enhance more precise moment localization. Our model is evaluated on two representative video corpus moment retrieval benchmarks: TVR and DiDeMo. Extensive experiments have been conducted to demonstrate that our method outperforms existing work.
