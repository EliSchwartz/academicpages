---
title: "StarNet: towards weakly supervised few-shot detection and explainable few-shot classification"
collection: publications
permalink: /publication/starnet
excerpt: ''
date: 2020-03-01
venue: ''
paperurl: 'https://arxiv.org/abs/2003.06798'
authors: 'L. Karlinsky*, J. Shtok*, A. Alfassy*, M. Lichtenstein*, S. Harary, E. Schwartz, S. Doveh, P. Sattigeri, R. Feris, A. Bronstein, R. Giryes'
---
In this paper, we propose a new few-shot learning method called StarNet, which is an end-to-end trainable non-parametric starmodel few-shot classifier. While being meta-trained using only image level class labels, StarNet learns not only to predict the class labels for each query image of a few-shot task, but also to localize (via a heatmap)
what it believes to be the key image regions supporting its prediction, thus effectively detecting the instances of the novel categories. The localization is enabled by the StarNet’s ability to find large, arbitrarily
shaped, semantically matching regions between all pairs of support and query images of a few-shot task. We evaluate StarNet on multiple few-shot classification benchmarks attaining significant state-of-the-art improvement on the CUB and ImageNetLOC-FS, and smaller improvements on other benchmarks. At the same time, in many cases, StarNet provides plausible explanations for its class label predictions, by highlighting the correctly paired novel category instances on the query and on its best matching support (for the predicted class). In addition, we test the proposed approach on the previously unexplored and challenging task of Weakly Supervised Few-Shot Object Detection (WS-FSOD), obtaining significant improvements over the baselines.