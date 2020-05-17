---
title: "One-Shot One-Class image recognition"
excerpt: "CLEAR: Cumulative LEARning for one-shot one-class image recognition (CVPR 2018)
<br/><img src='/images/CLEAR.png'>"
collection: research
---

This work addresses the novel problem of one-shot one-class classification. The goal is to estimate a classification decision boundary for a novel class based on a single image example. Our method exploits transfer learning to model the transformation from a representation of the input, extracted by a Convolutional Neural Network, to a classification decision boundary. We use a deep neural network to learn this transformation from a large labelled dataset of images and their associated class decision boundaries generated from ImageNet, and then apply the learned decision boundary to classify subsequent query images. We tested our approach on several benchmark datasets and significantly outperformed the baseline methods.

Link to Github repository can be found [here](https://github.com/JKozerawski/CLEAR-osoc)

Our CVPR 2018 poster can be found [here](https://jkozerawski.github.io/files/CVPR_2018_poster.pdf)
