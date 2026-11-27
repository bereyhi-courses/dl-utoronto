---
type: lecture
date: 2026-11-24T13:10:00
title: "Lecture 11: Autoencoding and VAEs"
tldr: "AEs I"
stat: lec
# for lectures stat: lec
description: We discuss the problem of representation. We see that using symmetric encoder and decoder we can learn an efficient representation known as latent. This is indeed a nonlinear version of the PCA. We look into vanilla, sparse, and denoising AEs and understand their functionality. We also discuss the special case of Variational AEs which enables us to sample from data distribution. This makes us capable of generating new data samples. 
videoID: FuXYsJznA8o
hide_from_announcments: false
---
**Lecture Notes:**
- [Lecture 11]({{ site.baseurl }}/assets/Notes/L11_handout.pdf)

**Further Reads:**
* [Representation](https://ieeexplore.ieee.org/abstract/document/6790375) Paper _Nonlinear component analysis as a kernel eigenvalue problem_ published in 1998 by _B. Schölkopf et al._ 
* [Nonlinear PCA via NNs](https://web.archive.org/web/20111003131045id_/http://pca.narod.ru/2MainGorbanKeglWunschZin.pdf) Paper _Nonlinear Principal Component Analysis: Neural Network Models and Applications_ published in 2008 by _M. Scholz et al._
* [Vanilla AEs](https://dbirman.github.io/learn/hierarchy/pdfs/Hinton2006.pdf) Paper _Reducing the Dimensionality of Data with Neural Networks_ published in 2006 by _G. Hinton and R. Salakhutdinov_ 
* [Denoising AEs](https://dl.acm.org/doi/pdf/10.1145/1390156.1390294) Paper _Extracting and Composing Robust Features with Denoising Autoencoders_ published in 2008 by _P. Vincent et al._
* [Variational AEs](https://indico.math.cnrs.fr/event/11377/attachments/4589/6915/18012024_Kingma-and-Welling-2022%20Auto-Encoding%20Variational%20Bayes.pdf) Paper _Auto-Encoding Variational Bayes_ published in 2008 by _D. Kingma and P. Welling_ proposing VAE idea