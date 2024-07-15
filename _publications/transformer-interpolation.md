---
title: "Upper and lower memory capacity bounds of transformers for next-token prediction"
collection: publications
permalink: /publications/transformer-interpolation
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2024-01-01
venue: 'Arxiv'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://arxiv.org/pdf/2405.13718'
citation: 'Madden, L; Fox, C; Thrampoulidis, C. Upper and lower memory capacity bounds
of transformers for next-token prediction. arXiv preprint arXiv:2405.13718, 2024'
---

Given a sequence of tokens, such as words, the task of next-token prediction is to predict the next-token conditional probability distribution. Decoder-only transformers have become effective models for this task, but their properties are still not fully understood. In particular, the largest number of distinct context sequences that a decoder-only transformer can interpolate next-token distributions for has not been established. To fill this gap, we prove upper and lower bounds on this number, which are equal up to a multiplicative constant. We prove these bounds in the general setting where next-token distributions can be arbitrary as well as the empirical setting where they are calculated from a finite number of document sequences. Our lower bounds are for one-layer transformers and our proofs highlight an important injectivity property satisfied by self-attention. Furthermore, we provide numerical evidence that the minimal number of parameters for memorization is sufficient for being able to train the model to the entropy lower bound.