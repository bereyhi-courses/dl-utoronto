---
type: lecture
date: 2026-10-20T13:10:00
title: "Lecture 7: Normalization and Residual Learning"
tldr: "ResNet"
stat: lec
# for lectures stat: lec
description: We discuss major means for handling vanishing gradient. We first discuss normalization, namely input, batch, and layer normalization. We see how they impact forward and backpropagation. We then discuss residual learning and skip connection which lead to the introduction of ResNet. 
videoID: cbzIUOoDP0E
hide_from_announcments: false
---
**Lecture Notes:**
- [Lecture 7]({{ site.baseurl }}/assets/Notes/L07_handout.pdf)

**Further Reads:**
* [Batch-Norm](https://proceedings.mlr.press/v37/ioffe15.html) Paper _Batch Normalization: Accelerating Deep Network Training by Reducing Internal Covariate Shift_ published in 2015 by _S. Ioffe and C. Szegedy_ proposing Batch Normalization
* [Batch-Norm Meaning](https://proceedings.neurips.cc/paper/2018/hash/905056c1ac1dad141560467e0a99e1cf-Abstract.html) Paper _How Does Batch Normalization Help Optimization?_ published in 2018 by _S. Santurkar et al._ discussing why Batch Normalization works: they claim that the main reason is that loss landscape is getting much smoother
* [ResNet](https://arxiv.org/abs/1512.03385) Paper _Deep Residual Learning for Image Recognition_ published in 2015 by _K. He et al._ proposing ResNet