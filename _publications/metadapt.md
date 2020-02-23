---
title: "MetAdapt: Meta-Learned Task-Adaptive Architecture for Few-Shot Classification"
collection: publications
permalink: /publication/metadapt
excerpt: ''
date: 2019-12-01
venue: 'Arxiv'
paperurl: 'https://arxiv.org/pdf/1912.00412'
authors: 'Sivan Doveh*, Eli Schwartz*, Chao Xue, Rogerio Feris, Alex Bronstein, Raja Giryes, Leonid Karlinsky'
---
Few-Shot Learning (FSL) is a topic of rapidly growing interest. Typically, in FSL a model is trained on a dataset consisting of many small tasks (meta-tasks) and learns to adapt to novel tasks that it will encounter during test time. This is also referred to as meta-learning. So far, meta-learning FSL methods have focused on optimizing parameters of pre-defined network architectures, in order to make them easily adaptable to novel tasks. Moreover, it was observed that, in general, larger architectures perform better than smaller ones up to a certain saturation point (and even degrade due to over-fitting). However, little attention has been given to explicitly optimizing the architectures for FSL, nor to an adaptation of the architecture at test time to particular novel tasks. In this work, we propose to employ tools borrowed from the Differentiable Neural Architecture Search (D-NAS) literature in order to optimize the architecture for FSL without over-fitting. Additionally, to make the architecture task adaptive, we propose the concept of `MetAdapt Controller' modules. These modules are added to the model and are meta-trained to predict the optimal network connections for a given novel task. Using the proposed approach we observe state-of-the-art results on two popular few-shot benchmarks: miniImageNet and FC100.