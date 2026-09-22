---
type: lecture
date: 2026-09-22T13:00:00
title: "Lecture 08: Multiclass Classification and Backpropagation"
tldr: "Forward Pass"
stat: lec
# for lectures stat: lec
description: We review neural classification using an MLP. We see that cross-entropy is a better loss helping us make differentiable risk. We can deploy that by interpreting the output of a neural network to be probability of each label. At the second part of the course, we discuss computation graphs. We see that the flow of information in a NN is similar to a computation graph. We could use this fact to build an algorithmic approach based on chain-rule to compute the gradient of the loss with respect to each weight in the network, this algorithm is called Backpropagation. We develop this algorithm for an MLP and see that it's dual to the forward pass.
videoID: Rpt846AD5Vw
hide_from_announcments: false
---
**Lecture Notes:**
- [Lecture 3]({{ site.baseurl }}/assets/Notes/L03_handout.pdf)

**Further Reads:**
* [Deep FNNs](https://www.deeplearningbook.org/): Chapter 6 - Sections 6.3 and 6.4 of [[GYC]](https://www.deeplearningbook.org/)
* [Backpropagation](https://www.bishopbook.com/): Chapter 8 of [[BB]](https://www.bishopbook.com/)
* [Backpropagation of Error](https://www.nature.com/articles/323533a0) Paper _Learning representations by back-propagating errors_ published in _Nature_ by _D. Rumelhart, G. Hinton and R. Williams_ in 1986 advocating the idea of systematic gradient computation of a computation graph