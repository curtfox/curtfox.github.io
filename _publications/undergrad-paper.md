---
title: "Deep Learning of Immune Cell Differentiation"
collection: publications
permalink: /publications/undergrad-paper
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2020-01-01
venue: 'Proceedings of the National Academy of Sciences of the United States of America'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://www.pnas.org/doi/epdf/10.1073/pnas.2011795117'
citation: 'Maslova, A; Ramirez, R; Ma, K; Schmutz, H; Wang, C; Fox, C; Ng, B; Benoist, C; Mostafavi, S; The Immunological Genome Project. Deep Learning of Immune Cell Differentiation. Proceedings of the National Academy of Sciences of the United States of America, 2020'
---

Although we know many sequence-specific transcription factors (TFs), how the DNA sequence of cis-regulatory elements is decoded and orchestrated on the genome scale to determine immune cell differentiation is beyond our grasp. Leveraging a granular atlas of chromatin accessibility across 81 immune cell types, we asked if a convolutional neural network (CNN) could learn to infer cell type-specific chromatin accessibility solely from regulatory DNA sequences. With a tailored architecture and an ensemble approach to CNN parameter interpretation, we show that our trained network ("AI-TAC") does so by rediscovering ab initio the binding motifs for known regulators and some unknown ones. Motifs whose importance is learned virtually as functionally important overlap strikingly well with positions determined by chromatin immunoprecipitation for several TFs. AI-TAC establishes a hierarchy of TFs and their interactions that drives lineage specification and also identifies stage-specific interactions, like Pax5/Ebf1 vs. Pax5/Prdm1, or the role of different NF-κB dimers in different cell types. AI-TAC assigns Spi1/Cebp and Pax5/Ebf1 as the drivers necessary for myeloid and B lineage fates, respectively, but no factors seemed as dominantly required for T cell differentiation, which may represent a fall-back pathway. Mouse-trained AI-TAC can parse human DNA, revealing a strikingly similar ranking of influential TFs and providing additional support that AI-TAC is a generalizable regulatory sequence decoder. Thus, deep learning can reveal the regulatory syntax predictive of the full differentiative complexity of the immune system.