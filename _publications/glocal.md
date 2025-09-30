---
title: "Glocal Smoothness: Line Search can really help!"
collection: publications
permalink: /publications/glocal
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2025-01-01
venue: 'Arxiv'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://www.arxiv.org/pdf/2506.12648'
citation: 'C. Fox, A. Mishkin, S. Vaswani, M. Schmidt. "Glocal Smoothness: Line Search can really help!". arXiv preprint arXiv:2506.12648, 2025'
---

Iteration complexities for first-order optimization algorithms are typically stated in terms of a global Lipschitz constant of the gradient, and near-optimal results are achieved using fixed step sizes. But
many objective functions that arise in practice have regions with small Lipschitz constants where larger step sizes can be used. Many local Lipschitz assumptions have been proposed, which have lead to
results showing that adaptive step sizes and/or line searches yield improved convergence rates over fixed step sizes. However, these faster rates tend to depend on the iterates of the algorithm, which makes it
difficult to compare the iteration complexities of different methods. We consider a simple characterization of global and local ("glocal”) smoothness that only depends on properties of the function. This allows
upper bounds on iteration complexities in terms of iterate-independent constants and enables us to compare iteration complexities between algorithms. Under this assumption it is straightforward to show the advantages of line searches over fixed step sizes, and that in some settings, gradient descent with line search has a better iteration complexity than accelerated methods with fixed step sizes. We further show that glocal smoothness can lead to improved complexities for the Polyak and AdGD step sizes, as well other algorithms including coordinate optimization, stochastic gradient methods, accelerated gradient methods, and non-linear conjugate gradient methods.
