---
title: "Multi-level dictionary learning for fine-grained images categorization with attention model"
collection: publications
category: manuscripts
selected: false
permalink: /publication/2021-09-17-paper-neurcom-fine-grained-classification
excerpt: ""
date: 2021-09-17
venue: 'Neurocomputing'
slidesurl: null
paperurl: 'https://www.sciencedirect.com/science/article/abs/pii/S0925231221001107'
citation: '<u><strong>Ji, Jinsheng</strong></u>, Yiyou Guo, Zhen Yang, Tao Zhang, Xiankai Lu, "Multi-level dictionary learning for fine-grained images categorization with attention model," in Neurocomputing, Volume 453, 2021, Pages 403-412, ISSN 0925-2312, doi.org/10.1016/j.neucom.2020.07.147.'
---
Fine-grained image categorization is a challenging task due to the difficulty of localizing the discriminative regions for different sub-categories. Previous works mainly focus on using the manual annotations or the attention algorithm to localize these regions, which is demanding and complex in practical applications. This paper proposes a method of using a multi-level attention model (MLA-CNN) which has been trained on the full-size image train set of current tasks to localize the most discriminative regions. Intuitively, three typical receptive field sizes are selected for the multi-level attention maps. Then, multi-level dictionary learning is introduced to extract discriminative features from these localized regions. Our method explores a new thought about how to use the neural activations to generate multi-scale regions which are helpful for the fine-grained categorization. The method can be achieved in two steps. The first step is to select the neurons that have the max activation in the selected three feature maps. These feature maps are the outputs of the pre-trained CNN model by feeding the full-size images into the model. Then, we generate the discriminative regions according to the receptive field size of the selected neurons. The second step is to train the subtle networks with these multi-scale regions. One scaled discriminative region can be regarded as one typical dictionary feature. Then these results are integrated for final prediction. We evaluate our method on three challenging fine-grained image datasets, CUB-200-2011, Stanford Dogs, and Stanford Cars. The experimental results demonstrate that our method outperforms many state-of-the-art methods, using extra object/parts annotations and attention-based methods.
