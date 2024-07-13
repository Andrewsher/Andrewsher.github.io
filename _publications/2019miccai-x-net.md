---
title: "X-Net: Brain Stroke Lesion Segmentation Based on Depthwise Separable Convolution and Long-range Dependencies"
collection: publication
permalink: /publication/2019miccai-x-net
excerpt: '**Kehan Qi**, Hao Yang, Cheng Li, Zaiyi Liu, Meiyun Wang, Qiegen Liu, and Shanshan Wang*'
date: 2019-10-13
venue: 'Medical Image Computing and Computer Assisted Intervention–MICCAI'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
authors: '**Kehan Qi**, Hao Yang, Cheng Li, Zaiyi Liu, Meiyun Wang, Qiegen Liu, and Shanshan Wang*'
paperurl: 'https://arxiv.org/pdf/1907.07000'
codeurl: 'https://github.com/Andrewsher/X-Net'
---


The morbidity of brain stroke increased rapidly in the past few years. To help specialists in lesion measurements and treatment plan ning, automatic segmentation methods are critically required for clinical practices. Recently, approaches based on deep learning and methods for contextual information extraction have served in many image segmen tation tasks. However, their performances are limited due to the insu cient training of a large number of parameters, which sometimes fail in capturing long-range dependencies. To address these issues, we propose a depthwise separable convolution based X-Net that designs a nonlocal op eration namely Feature Similarity Module (FSM) to capture long-range dependencies. The adopted depthwise convolution allows to reduce the network size, while the developed FSM provides a more e ective, dense contextual information extraction and thus facilitates better segmen tation. The e ectiveness of X-Net was evaluated on an open dataset Anatomical Tracings of Lesions After Stroke (ATLAS) with encouraging performance achieved compared to other six state-of-the-art approaches. We make our code available at [https://github.com/Andrewsher/X-Net](https://github.com/Andrewsher/X-Net).