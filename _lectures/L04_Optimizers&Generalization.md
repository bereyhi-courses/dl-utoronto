---
type: lecture
date: 2026-09-29T13:10:00
title: "Lecture 4: Optimizers and Generalization"
tldr: "Optimizer & Overfitting"
stat: lec
# for lectures stat: lec
description: We study the SGD algorithm. We see that using mini-batches we can control the tradeoff between variance and complexity of gradient computation. We then take a look at extensions of SGD, namely momentum method and Rprop, RMSprop, and Adam. In the second part, we study the overfitting, its main sources, and practical means to handle it, i.e., cross-validation, data augmentation, and regularization.
videoID: azie9ZAX9dg
hide_from_announcments: false
---
**Lecture Notes:**
- [Lecture 4]({{ site.baseurl }}/assets/Notes/L04_handout.pdf)

**Further Reads:**
* [SGD](https://www.deeplearningbook.org/): Chapter 5 - Section 5.9 of [[GYC]](https://www.deeplearningbook.org/)
* [Regularization](https://www.deeplearningbook.org/): Chapter 7 of [[GYC]](https://www.deeplearningbook.org/)
* [Learning Rate Scheduling](https://ieeexplore.ieee.org/abstract/document/7926641) Paper _Cyclical Learning Rates for Training Neural Networks_ published in _Winter Conference on Applications of Computer Vision (WACV)_ by _Leslie N. Smith_ in 2017 discussing learning rate scheduling
* [Rprop](https://ieeexplore.ieee.org/document/298623) Paper _A direct adaptive method for faster backpropagation learning: the RPROP algorithm_ published in _IEEE International Conference on Neural Networks_ by _M. Riedmiller and H. Braun_ in 1993 proposing Rprop algorithm
* [Dropout 1](https://arxiv.org/abs/1207.0580) Paper _Improving neural networks by preventing co-adaptation of feature detectors_ published in 2012 by _G. Hinton et al._ proposing Dropout
* [Dropout 2](https://jmlr.org/papers/v15/srivastava14a.html) Paper _Dropout: A Simple Way to Prevent Neural Networks from Overfitting_ published in 2014 by _N. Srivastava et al._ providing some analysis and illustrations on Dropout