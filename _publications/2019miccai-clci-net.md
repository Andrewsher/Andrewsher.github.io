---
title: "CLCI-Net: Cross-Level Fusion and Context Inference Networks for Lesion Segmentation of Chronic Stroke"
collection: publication
permalink: /publication/2019miccai-clci-net
excerpt: 'HaoYang, Weijian Huang, **Kehan Qi**, Cheng Li, Xinfeng Liu, Meiyun Wang, Hairong Zheng, and Shanshan Wang*'
date: 2019-10-13
venue: 'Medical Image Computing and Computer Assisted Intervention–MICCAI'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
authors: 'HaoYang, Weijian Huang, **Kehan Qi**, Cheng Li, Xinfeng Liu, Meiyun Wang, Hairong Zheng, and Shanshan Wang*'
paperurl: 'https://arxiv.org/pdf/1907.07008'
codeurl: 'https://github.com/YH0517/CLCI_Net'
---


Segmenting stroke lesions from T1-weighted MR images is of great value for large-scale stroke rehabilitation neuroimaging analy ses. Nevertheless, there are great challenges with this task, such as large range of stroke lesion scales and the tissue intensity similarity. The fa mous encoder-decoder convolutional neural network, which although has made great achievements in medical image segmentation areas, may fail to address these challenges due to the insufficient uses of multi-scale fea tures and context information. To address these challenges, this paper proposes a Cross-Level fusion and Context Inference Network (CLCI Net) for the chronic stroke lesion segmentation from T1-weighted MR images. Specifically, a Cross-Level feature Fusion (CLF) strategy was developed to make full use of different scale features across different lev els; Extending Atrous Spatial Pyramid Pooling (ASPP) with CLF, we have enriched multi-scale features to handle the different lesion sizes; In addition, convolutional long short-term memory (ConvLSTM) is em ployed to infer context information and thus capture fine structures to address the intensity similarity issue. The proposed approach was evalu ated on an open-source dataset, the Anatomical Tracings of Lesions After Stroke (ATLAS) with the results showing that our network outperforms f ive state-of-the-art methods. We make our code and models available at [https://github.com/YH0517/CLCI_Net](https://github.com/YH0517/CLCI_Net).