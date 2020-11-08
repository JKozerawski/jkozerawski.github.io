---
title: "BLT: Balancing Long-Tailed Datasets with Adversarially-Perturbed Images"
excerpt: "Studying problem of real world long-tail datasets with a focus on increasing the accuracy among tail categories."
<br/><img src='/images/BLT.png'>"
collection: research
---

Accepted to ACCV 2020

Real visual-world datasets tend to have few classes with large numbers of samples (i.e., head classes) and many others with smaller numbers of samples (i.e., tail classes). Unfortunately, this imbalance enables a visual recognition system to perform well on head classes but poorly on tail classes. To alleviate this imbalance, we present BLT, a novel data augmentation technique that generates extra training samples for tail classes to improve the generalization performance of a classifier. Unlike prior long-tail approaches that rely on generative models (e.g., GANs or VQ-VAEs) to augment a dataset, BLT uses a gradient-ascent-based image generation algorithm that requires significantly less training time and computational resources. BLT avoids the use of dedicated generative networks, which adds significant computational overhead and require elaborate training procedures. Our experiments on natural and synthetic long-tailed datasets and across different network architectures demonstrate that BLT consistently improves the average classification performance of tail classes by 11% w.r.t. the common approach that balances the dataset by oversampling tail-class images. BLT maintains the accuracy on head classes while improving the performance on tail classes.

[Code available here](https://github.com/JKozerawski/BLT)

[Download paper here](http://jkozerawski.github.io/files/ACCV_2020.pdf)


