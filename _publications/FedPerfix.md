---
title: "FedPerfix: Towards Partial Model Personalization of Vision Transformers in Federated Learning"
collection: publications
permalink: /publication/FedPerfix
<!-- excerpt: 'This paper is about the number 1. The number 2 is left for future work.' -->
# date: 2023-09-17
# venue: "2017 IEEE International Conference on Image Processing"
# paperurl: "https://ieeexplore.ieee.org/document/8296754"
# citation: 'Young-Gun Lee, <b>Zheng Tang</b>, Jenq-Neng Hwang and Zhijun Fang. "Inter-Camera Tracking Based on Fully Unsupervised Online Learning". <i>Proceedings of 2017 IEEE International Conference on Image Processing (ICIP 2017)</i>. pp. 2607-2611. 2017.'
---
# FedPerfix: Towards Partial Model Personalization of Vision Transformers in Federated Learning

[<a href='https://arxiv.org/abs/2308.09160'>Paper</a>]
[<a href='https://github.com/imguangyu/FedPerfix'>Code</a>]


## Abstract
Personalized Federated Learning (PFL) represents a promising solution for decentralized learning in heterogeneous data environments. Partial model personalization has been proposed to improve the efficiency of PFL by selectively updating local model parameters instead of aggregating all of them. However, previous work on partial model personalization has mainly focused on Convolutional Neural Networks (CNNs), leaving a gap in understanding how it can be applied to other popular models such as Vision Transformers (ViTs).
In this work, we investigate where and how to partially personalize a ViT model. Specifically, we empirically evaluate the sensitivity to data distribution of each type of layer. Based on the insights that the self-attention layer and the classification head are the most sensitive parts of a ViT, we propose a novel approach called FedPerfix, which leverages plugins to transfer information from the aggregated model to the local client as a personalization. Finally, we evaluate the proposed approach on CIFAR-100, OrganAMNIST, and Office-Home datasets and demonstrate its effectiveness in improving the model's performance compared to several advanced PFL methods.

## Citation
Coming Soon.