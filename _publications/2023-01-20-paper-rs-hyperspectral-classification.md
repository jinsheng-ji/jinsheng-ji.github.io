---
title: "Random Shuffling Data for Hyperspectral Image Classification with Siamese and Knowledge Distillation Network"
collection: publications
category: manuscripts
permalink: /publication/2023-01-20-paper-rs-hyperspectral-classification
excerpt: 'This paper is about hyperspectral image classificaion.'
date: 2023-08-18
venue: 'Remote Sensing'
slidesurl: 'https://www.mdpi.com/2072-4292/15/16/4078'
paperurl: 'https://www.mdpi.com/2072-4292/15/16/4078'
citation: 'Yang, Zhen and Cao, Ying and Zhou, Xin and Liu, Junya and Zhang, Tao and Ji, Jinsheng, "Random Shuffling Data for Hyperspectral Image Classification with Siamese and Knowledge Distillation Network. Remote Sensing," in Remote Sensing. 2023; 15(16):4078. https://doi.org/10.3390/rs15164078.'
---
Hyperspectral images (HSIs) are characterized by hundreds of spectral bands. The goal of HSI is to associate the pixel with a corresponding category label by analyzing subtle differences in the spectrum. Due to their excellent local context modeling capabilities, Convolutional Neural Network (CNN)-based methods are often adopted to complete the classification task. To verify whether the patch-data-based CNN methods depend on the homogeneity of patch data during the training process in HSI classification, we designed a random shuffling strategy to disrupt the data homogeneity of the patch data, which is randomly assigning the pixels from the original dataset to other positions to form a new dataset. Based on this random shuffling strategy, we propose a sub-branch to extract features on the reconstructed dataset and fuse the loss rates (RFL). The loss rate calculated by RFL in the new patch data is cross combined with the loss value calculated by another sub-branch in the original patch data. Moreover, we construct a new hyperspectral classification network based on the Siamese and Knowledge Distillation Network (SKDN) that can improve the classification accuracy on randomly shuffled data. In addition, RFL is introduced into the original model for hyperspectral classification tasks in the original dataset. The experimental results show that the improved model is also better than the original model, which indicates that RFL is effective and feasible. Experiments on four real-world datasets show that, as the proportion of randomly shuffling data increases, the latest patch-data-based CNN methods cannot extract more abundant local contextual information for HSI classification, while the proposed sub-branch RFL can alleviate this problem and improve the network’s recognition ability.
