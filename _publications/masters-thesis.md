---
title: "Study of the Edge of Stability in Deep Learning"
collection: publications
permalink: /publications/masters-thesis
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2023-01-01
venue: "Master's Thesis"
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://open.library.ubc.ca/media/stream/pdf/24/1.0435607/4'
citation: "Fox, C. A Study of the Edge of Stability in Deep Learning. Master's Thesis, 2023"
---

Optimization of deep neural networks has been studied extensively, but our understanding of it is still very limited. In particular, it is still unclear how to optimally set hyperparameters such as the step size for gradient descent when training neural networks. We explore the issue of tuning the step size for full batch gradient descent, examining a proposed phenomenon in the literature called the "edge of stability". This refers to a phase of training for neural networks when the training loss non-monotonically decreases over time while the sharpness (the maximum eigenvalue of the Hessian matrix) oscillates around the threshold of precisely two divided by the step size. In this thesis, we start by providing the necessary background to understand the current state of the art in this area. We then perform various experiments on the sharpness, and study its trajectory over the course of training with full batch gradient descent. Unlike the vast majority of the previous literature, we focus on investigating the sharpness with respect to the various layers of neural networks individually. We observe that different layers of a neural network have differing behavior in their sharpness trajectories. We focus on fully connected networks and examine how varying hyperparameters of the network, such as the number of layers or hidden units per layer, impact the sharpness. Finally, we explore how various architecture choices impact step size selection when training with gradient descent. We see that changing just one parameter of a deep neural network, such as the non-linear activation functions used in each layer, can greatly impact which step sizes can lead to divergence during training. This motivates further investigation into how architecture choices affect hyperparameter selection.