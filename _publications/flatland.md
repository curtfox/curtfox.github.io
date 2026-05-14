---
title: "Flatland: The Adventures of Gradient Descent with Large Step Sizes"
collection: publications
permalink: /publications/flatland
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2026-01-01
venue: 'ICML'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
# paperurl: '...' - FILL IN LATER
citation: 'L. Galli, C. Fox, W. Bartolomaeus, M. Schmidt, H. Rauhut. "Flatland: The Adventures of Gradient Descent with Large Step Sizes". ICML, 2026'
---

The training of neural networks often entails objective functions that are not globally L-smooth. For these functions, it is both theoretically and practically difficult to reply to the question: what is the largest possible step size that ensures the convergence of gradient descent (GD)? We address this longstanding open question in deep learning by providing a unifying definition of "large" step sizes that requires only local Lipschitz (or even Hölder) continuity of the gradient. We design first-order adaptive methods that provably yield large step sizes and show that they operate at the edge of stability (EoS) right from the start of the training. In particular, the loss decreases nonmonotonically and the product between the step size and sharpness, i.e., the largest eigenvalue of the hessian, stays above the EoS threshold of 2 throughout training. Using our method, we are also able to minimize the sharpness all the way down to its global minimum. Contrary to expectation, we find that encountering globally-flat regions too early in the training may both slow down convergence and jeopardize the generalization ability of the network. Exploiting a self-stabilization argument, we allow GD to enter slightly sharper valleys and turn unsuccessful training runs into very successful ones.