---
layout: page
title: Materials
permalink: /materials/
---

## Lecture Notes
The lecture notes are uploaded through the semester. For each chapter, the notes are provided section by section. 
### Chapter 0: Course Overview and Logistics
* [Handouts]({{site.baseurl}}/assets/Notes/CH0/CH0.pdf): All Sections included in a single file

### Chapter 1: Fundamentals of Deep Learning
* [Section 1]({{site.baseurl}}/assets/Notes/CH1/CH1_Sec1.pdf): Motivation to Learn DL
* [Section 2]({{site.baseurl}}/assets/Notes/CH1/CH1_Sec2.pdf): Learning from Data: _Basics_
* [Section 3]({{site.baseurl}}/assets/Notes/CH1/CH1_Sec3.pdf): Perceptron Machine
* [Section 4]({{site.baseurl}}/assets/Notes/CH1/CH1_Sec4.pdf): Deep Neural Networks
* [Section 5]({{site.baseurl}}/assets/Notes/CH1/CH1_Sec5.pdf): Function Optimization

### Chapter 2: Feedforward NNs
* [Section 1]({{site.baseurl}}/assets/Notes/CH2/CH2_Sec1.pdf): Forward Pass in MLPs
* [Section 2]({{site.baseurl}}/assets/Notes/CH2/CH2_Sec2.pdf): Computing Gradient via _Backpropagation_ on Computation Graph
* [Section 3]({{site.baseurl}}/assets/Notes/CH2/CH2_Sec3.pdf): Multiclass Classification
* [Section 4]({{site.baseurl}}/assets/Notes/CH2/CH2_Sec4.pdf): Mini-batch Training and SGD Algorithm




<!-- ## Tutorial Notebooks -->
<!-- The tutorial notebooks can be accessed below.
* [Tutorial 1]({{site.baseurl}}/assets/Tutorials/Tutorial_1.ipynb): PyTorch Overview, Batch Training, Embedding, and Tokenization, by __Amir Hossein Mobasheri__ -->


## Book

There is indeed no single textbook for this course, and we use various resources in the course. The following textbooks have covered the key notions in the course. 

* [[GYC] Goodfellow, Ian, et al. _Deep Learning._ MIT Press, 2016.](https://www.deeplearningbook.org/)
* [[BB] Bishop, Christopher M., and Hugh Bishop. _Deep Learning: Foundations and Concepts._ Springer Nature, 2023.](https://www.bishopbook.com/)
* [[Ag] C. Aggarwal. _Neural Networks and Deep Learning._ Springer, 2018.](https://link.springer.com/book/10.1007/978-3-319-94463-0)

The following textbooks are also good resources for __practicing hands-on skills.__ Note that we are __not__ simply learning to implement only! We study the fundamentals of deep learning. Of course, we try to get our hands dirty as well and learn how to do implementation.

* [Chollet, Francois. _Deep learning with Python._ Manning Publications, 2021.](https://www.manning.com/books/deep-learning-with-python)
* [Müller, Andreas, and Sarah Guido. _Introduction to Machine Learning with Python._ O'Reilly Media, Inc., 2016.](https://www.oreilly.com/library/view/introduction-to-machine/9781449369880/)


## Reading List

This section will be completed gradually through the semester.


### Chapter 1: Preliminaries
#### Introduction to DL
* [Motivation](https://www.bishopbook.com/): Chapter 1 - Section 1.1 of [[BB]](https://www.bishopbook.com/)

#### ML Components
* [Review on Linear Algebra](https://www.deeplearningbook.org/): Chapter 2 of [[GYC]](https://www.deeplearningbook.org/)
* [ML Components](https://www.bishopbook.com/): Chapter 1 - Sections 1.2.1 to 1.2.4 of [[BB]](https://www.bishopbook.com/)
* [ML Basics](https://www.deeplearningbook.org/): Chapter 5 of [[GYC]](https://www.deeplearningbook.org/)

#### Review on Probability Theory
* [Probability Theory](https://www.bishopbook.com/): Chapter 2 of [[BB]](https://www.bishopbook.com/)
* [Probability Review](https://www.deeplearningbook.org/): Chapter 3 of [[GYC]](https://www.deeplearningbook.org/)


#### Classification Problem
* [Binary Classification](https://www.bishopbook.com/): Chapter 5 - Sections 5.1 and 5.2 of [[BB]](https://www.bishopbook.com/)
* [McCulloch-Pitts Model](https://link.springer.com/article/10.1007/BF02478259): Paper _A logical calculus of the ideas immanent in nervous activity_ published in the _Bulletin of Mathematical Biophysics_ by _Warren McCulloch and Walter Pitts_ in 1943, proposing a computational model for neuron. This paper is treated as the pioneer study leading to the idea of _artificial neuron_

#### Training via Risk Minimization
* [Overview on Risk Minimization](https://ieeexplore.ieee.org/abstract/document/788640): Paper _An overview of statistical learning theory_ published as an overview of his life-going developments in ML in the _IEEE Transactions on Neural Networks_ by _Vladimir N. Vapnik_ in 1999

#### Perceptron Algorithm 
* [Perceptron Simulation Experiments](https://ieeexplore.ieee.org/document/4066017): Paper _Perceptron Simulation Experiments_ presented by _Frank Rosenblatt_ in Proceedings of IRE in 1960
* [Perceptron](https://link.springer.com/book/10.1007/978-3-319-94463-0): Chapter 1 - Section 1.2.1 of [[Ag]](https://link.springer.com/book/10.1007/978-3-319-94463-0)

#### Universal Approximation Theorem
* [Universal Approximation](https://link.springer.com/article/10.1007/BF02551274): Paper _Approximation by superpositions of a sigmoidal function_ published in _Mathematics of Control, Signals and Systems_ by _George V. Cybenko_ in 1989

#### Deep NNs
* [DNNs](https://www.bishopbook.com/): Chapter 6 - Sections 6.2 and 6.3 of [[BB]](https://www.bishopbook.com/)

#### Optimization via Gradient Descent
* [Gradient-based Optimization](https://www.deeplearningbook.org/): Chapter 4 - Sections 4.3 and 4.4 of [[GYC]](https://www.deeplearningbook.org/)
* [Gradient Descent](https://www.bishopbook.com/): Chapter 7 - Sections 7.1 to 7.2 of [[BB]](https://www.bishopbook.com/)


### Chapter 2: Fully-connected FNNs
#### Forward Propagation
* [Deep FNNs](https://www.deeplearningbook.org/): Chapter 6 - Sections 6.3 and 6.4 of [[GYC]](https://www.deeplearningbook.org/)

#### Backpropagation
* [Backpropagation](https://www.deeplearningbook.org/): Chapter 6 - Section 6.5 of [[GYC]](https://www.deeplearningbook.org/)
* [Backpropagation](https://www.bishopbook.com/): Chapter 8 of [[BB]](https://www.bishopbook.com/)
[Backpropagation of Error](https://www.nature.com/articles/323533a0) Paper _Learning representations by back-propagating errors_ published in _Nature_ by _D. Rumelhart, G. Hinton and R. Williams_ in 1986 advocating the idea of systematic gradient computation of a computation graph

#### Multi-class Classification
* [Multi-class Models](https://link.springer.com/book/10.1007/978-3-319-94463-0): Chapter 2 - Section 2.3 of [[Ag]](https://link.springer.com/book/10.1007/978-3-319-94463-0)

#### Full-batch, sample-level and mini-batch SGD
* [SGD](https://www.deeplearningbook.org/): Chapter 5 - Section 5.9 of [[GYC]](https://www.deeplearningbook.org/)
* [SGD](https://www.bishopbook.com/): Chapter 7 - Section 7.2 of [[BB]](https://www.bishopbook.com/)