---
title: "NICE: Noise Injection and Clamping Estimation for Neural Network Quantization"
collection: publications
permalink: /publication/nice
excerpt: ''
date: 2018-10-01
venue: ''
paperurl: 'https://arxiv.org/pdf/1810.00162'
authors: 'Baskin, C., Liss, N., Chai, Y., Zheltonozhskii, E., Schwartz, E., Giryes, R., Mendelson, A., & Bronstein, A. M.'
---
Convolutional Neural Networks (CNN) are very popular in many fields including computer vision, speech recognition, natural language processing, to name a few. Though deep learning leads to groundbreaking performance in these domains, the networks used are very demanding computationally and are far from real-time even on a GPU, which is not power efficient and therefore does not suit low power systems such as mobile devices. To overcome this challenge, some solutions have been proposed for quantizing the weights and activations of these networks, which accelerate the runtime significantly. Yet, this acceleration comes at the cost of a larger error. The \uniqname method proposed in this work trains quantized neural networks by noise injection and a learned clamping, which improve the accuracy. This leads to state-of-the-art results on various regression and classification tasks, e.g., ImageNet classification with architectures such as ResNet-18/34/50 with low as 3-bit weights and activations. We implement the proposed solution on an FPGA to demonstrate its applicability for low power real-time applications. 