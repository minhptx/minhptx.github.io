---
title: "SPADE: A Semi-supervised Probabilistic Approach for Detecting Errors in Tables"
collection: publications
permalink: /publication/ijcai-2021
date: 2021-08-19
venue: '30th International Joint Conference on Artificial Intelligence (IJCAI 2021)'
citation: '<b>Minh Pham</b>, Craig A. Knoblock, Muhao Chen, Binh Vu, and Jay Pujara. (2021).'
---
[[Paper]](http://minhptx.github.io/files/ijcai2021.pdf) | [[Github]](https://github.com/minhptx/spade)
## Abstract
Error detection is one of the most important steps in data cleaning and usually requires extensive human interaction to ensure quality. Existing supervised methods in error detection require a significant amount of training data while unsupervised methods rely on fixed inductive biases, which are usually hard to generalize, to solve the problem. In this paper, we present SPADE, a novel semi-supervised probabilistic approach for error detection. SPADE  introduces a novel probabilistic active learning model, where the system suggests examples to be labeled based on the agreements between user labels and indicative signals, which are designed to capture potential errors. SPADE uses a two-phase data augmentation process to enrich a dataset before training a deep-learning classifier to detect unlabeled errors. In our evaluation, SPADE achieves an average F1-score of 0.91 over five datasets and yields a 10% improvement compared with the state-of-the-art systems.