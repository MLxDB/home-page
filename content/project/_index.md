---
title: Projects
type: page
tags:
  - preface

view: compact

banner:
  caption: ''
  image: ''
---

## Overview of Our Research

{{< figure src="ml4db-overview.png" >}}

### Database Access Methods
Indexing techniques can significantly improve query efficiency. We use machine learning techniques to optimize various index structure based on the data distribution and workload patterns.

Publications:
-  [Effectively Learning Spatial Indexes with a Support for Updates](https://github.com/MLxDB/MLxDB.github.io/blob/master/publication/sigmod23-rlr-tree/rlr.pdf) SIGMOD 2023.
-  [Learned Index Benefits: Machine Learning Based Index Performance Estimation](https://www.vldb.org/pvldb/vol15/p3950-shi.pdf) VLDB 2023.

### Query Optimization
Query optimizer is at the core of a data management system. Traditional query optimizer requires a huge amount of work to build, and yet performs sub-optimally. We explore opportunities to enhance query optimizers with learning-based techniques, e.g., leared cardinalitiy estimation, multi-query optimization.

Publications:
-  [A Unified Deep Model of Learning from both Data and Queries for Cardinality Estimation.](https://dl.acm.org/doi/10.1145/3448016.3452830) SIGMOD 2021.
-   [Unsupervised Selectivity Estimation by Integrating Gaussian Mixture Models and an Autoregressive Model.](https://openproceedings.org/2022/conf/edbt/paper-65.pdf) EDBT 2022.

### ML4DB Foundation
The foundation of applying machine learning to problems like cardinality estimation/ query optimization is to have an effective representation of the query plans.

Publications:
-  [QueryFormer: a tree transformer model for query plan representation](http://www.vldb.org/pvldb/https://www.vldb.org/pvldb/vol15/p1658-zhao.pdf) VLDB 2022.
### Database Testing and Tools
There are plenty of other application of machine learning in data management systems. For example, we studied database generation from query workloads, which enables cloud database benchmarking and stress testing.

Publications:
-  [SAM: Database Generation from Query Workloads with Supervised Autoregressive Models.](https://dl.acm.org/doi/abs/10.1145/3514221.3526168) SIGMOD 2022.

## List of Projects