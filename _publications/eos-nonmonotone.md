---
title: "Nonmonotone Line Searches Operate at the Edge of Stability"
collection: publications
permalink: /publications/eos-nonmonotone
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2024-01-01
venue: 'NeurIPS OPT Workshop'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://opt-ml.org/papers/2024/paper16.pdf'
citation: 'C. Fox, L. Galli, M. Schmidt, H. Rauhut. "Nonmonotone Line Searches Operate at the Edge of Stability". NeurIPS OPT Workshop, 2024'
---

The traditional convergence analysis of Gradient Descent (GD) assumes the step size to be bounded from above by twice the reciprocal of the sharpness, i.e., the largest eigenvalue of the Hessian of
the objective function. However, recent numerical observations on neural networks have shown that GD also converges with larger step sizes. In this case, GD may enter into the so-called edge
of stability phase in which the objective function decreases faster than with smaller steps, but nonmonotonically. Interestingly enough, this same behaviour was already observed roughly 40
years ago when the first nonmonotone line search was proposed. These methods are designed to accept larger steps than their monotone counterparts (e.g., Armijo) as they do not impose a
decrease in the objective function, while still being provably convergent. In this paper, we show that nonmonotone line searches are able to operate at the edge of stability regime right from the start
of the training. Moreover, we design a new resetting technique that speeds up training and yields flatter solutions, by keeping GD at the edge of stability without requiring hyperparameter-tuning
or prior knowledge of problem-dependent constants. To conclude, we observe that the large steps yielded by our method seem to mimic the behavior of the well-known Barzilai-Borwein method.