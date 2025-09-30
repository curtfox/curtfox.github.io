---
title: "Upper and lower memory capacity bounds of transformers for next-token prediction"
collection: publications
permalink: /publications/transformer-interpolation
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2025-01-01
venue: 'IEEE Transactions on Information Theory'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://ieeexplore.ieee.org/document/11063403'
citation: 'L. Madden, C. Fox, C. Thrampoulidis. "Next-token Prediction Capacity: General Upper Bounds and a Lower Bound for Transformers". IEEE Transactions on Information Theory, 2025'
---

Given a sequence of tokens, such as words, the task of next-token prediction is to predict the next-token conditional probability distribution. Decoder-only transformers have become effective models for this task, but their properties are still not fully understood. In particular, the largest number of distinct context sequences that a decoder-only transformer can interpolate next-token distributions for has not been established. To fill this gap, we prove upper and lower bounds on this number, which are equal up to a multiplicative constant. We prove these bounds in the general setting where next-token distributions can be arbitrary as well as the empirical setting where they are calculated from a finite number of document sequences. Our lower bounds are for one-layer multi-head decoder-only transformers and our proofs highlight an important injectivity property satisfied by self-attention. Furthermore, we provide numerical evidence that the minimal number of parameters for memorization is sufficient for being able to train the model to the entropy lower bound.