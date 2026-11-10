---
type: lecture
date: 2026-11-10T13:00:00
title: "Lecture 9: Seq2Seq Models and Transformer"
tldr: "Transformer"
stat: lec
# for lectures stat: lec
description: We build a a basic language model. We see how we can train it. We use our basic LM to build an caption generator machine. This is a simple example of an encoding-decoding architecture. We see that despite its theoretical soundness, NMT with basic Enc-Dec suffers from lack of attention. We hence build a computational mechanism that provides the decoder possibility to attend to related tokens at the encoder. This is what we know as Attention Mechanism. Interestingly, we can ignore the time connection and perform the complete process in parallel with high efficiency through self-attention. We can use the self-attention module to build a deep sequence processor. This is what we call Transformer. 
videoID: NJZhiiJlMpo
hide_from_announcments: false
---
**Lecture Notes:**
- [Lecture 9]({{ site.baseurl }}/assets/Notes/L09_handout.pdf)

**Further Reads:**
* [Basic LM](https://www.jmlr.org/papers/volume3/bengio03a/bengio03a.pdf) Paper _A Neural Probabilistic Language Model_ published in 2003 by _Y. Bengio_ developing frist really-functioning LM
* [Attention](https://arxiv.org/abs/1409.0473) Paper _Neural Machine Translation by Jointly Learning to Align and Translate_ published in 2015 by _D. Bahdanau et al._ proposing Attention mechanism
* [Attention NMT](hhttps://arxiv.org/abs/1508.04025) Paper _Effective Approaches to Attention-based Neural Machine Translation_ published in 2015 by _M. Loung et al._ proposing Attention-based NMT
* [Transformer](https://proceedings.neurips.cc/paper/2017/hash/3f5ee243547dee91fbd053c1c4a845aa-Abstract.html) Paper _Attention is All You Need_ published in 2017 by _A. Vaswani et al._ proposing Transformer (cited 282K times to this date)
