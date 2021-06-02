---
title: "SPADE: A Semi-supervised Probabilistic Approach for Detecting Errors in Tables"
collection: publications
permalink: /publication/ijcai-2021
date: 2019-12-09
venue: '30th International Joint Conference on Artificial Intelligence (IJCAI 2021)'
citation: '<b>Minh Pham</b>, Craig A. Knoblock, Muhao Chen, Binh Vu, and Jay Pujara. (2021).'
---
[[Paper]](http://minhptx.github.io/files/bigdata2019.pdf) | [[Github]](https://github.com/minhptx/ieee-bigdata2019-transformation)
## Abstract
Data collected from heterogeneous sources often
have inconsistencies in data format and thus require transformation
before the data can be used. A major issue of existing
approaches is their dependency on parallel input-output data to
learn the transformations. However, parallel data are not always
available, and annotation requires excessive human interaction
because of format diversity. Therefore, these approaches have
limitations when applied to large-scale real-world problems. To
address this issue, we introduce UDATA, a novel unsupervised
system for non-parallel data transformation. Because the transforming
data usually share common syntactic patterns, UDATA
discovers common syntactic patterns from input/output examples
and synthesizes the transformations between the patterns. Moreover,
in UDATA, transformation results are verified by an active
learning model and ambiguous results are reported to users for
labeling. UDATA achieves accuracy close to other state-of-the-art
supervised systems without the need for any labeled data.