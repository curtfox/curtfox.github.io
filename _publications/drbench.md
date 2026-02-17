---
title: "DRBench: A Realistic Benchmark for Enterprise Deep Research"
collection: publications
permalink: /publications/drbench
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2026-01-01
venue: 'ICLR'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://openreview.net/forum?id=IGYQ4c92e2'
citation: 'A. Abaskohi, T. Chen, M. Muñoz-Mármol, C. Fox, A. V. Ramesh, É. Marcotte, X. H. Lù, N. Chapados, S. Gella, C. Pal, A. Drouin, I. H. Laradji. "DRBench: A Realistic Benchmark for Enterprise Deep Research". ICLR, 2026'
---

We introduce DRBench, a benchmark for evaluating AI agents on complex, open-ended deep research tasks in enterprise settings. Unlike prior benchmarks that focus on simple questions or web-only queries, DRBench evaluates agents on multi-step queries (for example, "What changes should we make to our product roadmap to ensure compliance with this standard?") that require identifying supporting facts from both the public web and private company knowledge base. Each task is grounded in realistic user personas and enterprise context, spanning a heterogeneous search space that includes productivity software, cloud file systems, emails, chat conversations, and the open web. Tasks are generated through a carefully designed synthesis pipeline with human-in-the-loop verification, and agents are evaluated on their ability to recall relevant insights, maintain factual accuracy, and produce coherent, well-structured reports. We release 100 deep research tasks across 10 domains, such as Sales, Cybersecurity, and Compliance. We demonstrate the effectiveness of DRBench by evaluating diverse DR agents across open- and closed-source models (such as GPT, Llama, and Qwen) and DR strategies, highlighting their strengths, weaknesses, and the critical path for advancing enterprise deep research.