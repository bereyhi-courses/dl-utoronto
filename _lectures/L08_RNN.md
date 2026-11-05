---
type: lecture
date: 2026-11-03T13:10:00
title: "RNN"
tldr: "RNNs and Gated Architectures"
stat: lec
# for lectures stat: lec
description: We study sequence data and their processing by NNs. We see that due to temporal connection, we cannot process them separately. We hence need to develop a sequence model. We study the most basic design for sequence processing, i.e., a recurrent NN. We see that by sequential processing of data, we need to backpropagate through time. This leads to finite memory due to the vanishing gradient behavior. We then learn the gating principle as a key idea to extend the memory through time. This idea leads to gated architectures, such as LSTM and GRU.
videoID: g3xIg15y4rw
hide_from_announcments: false
---
**Lecture Notes:**
- [Lecture 8]({{ site.baseurl }}/assets/Notes/L08_handout.pdf)

**Further Reads:**
* [Jordan Network](https://escholarship.org/uc/item/1fg2j76h) Paper _Attractor dynamics and parallelism in a connectionist sequential machine_ published in 1986 by _M. Jordan_ proposing his RNN
* [Elman Network](https://doi.org/10.1207/s15516709cog1402_1) Paper _Finding structure in time_ published in 1990 by _J. Elman_ proposing a revision to Jordan Network
* [BPTT](https://ieeexplore.ieee.org/abstract/document/58337) Paper _Backpropagation through time: What it does and how to do it_ published in 2002 by _P. Werbos_ explaining BPTT
* [LSTM](https://ieeexplore.ieee.org/abstract/document/6795963) Paper _Long short-term memory_ published in 1997 by _S. Hochreiter and J. Schmidhuber_ proposing LSTM
