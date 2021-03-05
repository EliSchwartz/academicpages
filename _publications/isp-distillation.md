---
title: "ISP Distillation"
collection: publications
permalink: /publication/isp-distillation
excerpt: ''
date: 2021-01-25
venue: 'Arxiv'
paperurl: 'https://arxiv.org/abs/2101.10203'
authors: 'E. Schwartz, A. M. Bronstein and R. Giryes'
---
Nowadays, many of the images captured are "observed" by machines only and not by humans, for example, robots' or autonomous cars' cameras. High-level machine vision models, such as object recognition, assume images are transformed to some canonical image space by the camera ISP. However, the camera ISP is optimized for producing visually pleasing images to human observers and not for machines, thus, one may spare the ISP compute time and apply the vision models directly to the raw data. Yet, it has been shown that training such models directly on the RAW images results in a performance drop. To mitigate this drop in performance (without the need to annotate RAW data), we use a dataset of RAW and RGB image pairs, which can be easily acquired with no human labeling. We then train a model that is applied directly to the RAW data by using knowledge distillation such that the model predictions for RAW images will be aligned with the predictions of an off-the-shelf pre-trained model for processed RGB images. Our experiments show that our performance on RAW images is significantly better than a model trained on labeled RAW images. It also reasonably matches the predictions of a pre-trained model on processed RGB images, while saving the ISP compute overhead.